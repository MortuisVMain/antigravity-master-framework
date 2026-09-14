---
name: accessibility
description: Audit and improve web accessibility following WCAG 2.1 guidelines. Use when asked to "improve accessibility", "a11y audit", "WCAG compliance", "screen reader support", "keyboard navigation", or "make accessible".
license: MIT
metadata:
  author: web-quality-skills
  version: "1.0"
---

# Accessibility (a11y)

Comprehensive accessibility guidelines based on WCAG 2.1 and Lighthouse accessibility audits. Goal: make content usable by everyone, including people with disabilities.

## WCAG Principles: POUR

| Principle | Description |
|-----------|-------------|
| **P**erceivable | Content can be perceived through different senses |
| **O**perable | Interface can be operated by all users |
| **U**nderstandable | Content and interface are understandable |
| **R**obust | Content works with assistive technologies |

## Conformance levels

| Level | Requirement | Target |
|-------|-------------|--------|
| **A** | Minimum accessibility | Must pass |
| **AA** | Standard compliance | Should pass (legal requirement in many jurisdictions) |
| **AAA** | Enhanced accessibility | Nice to have |

---

## Perceivable

### Text alternatives (1.1)

**Images require alt text:**
```html
<!-- вќЊ Missing alt -->
<img src="chart.png">

<!-- вњ… Descriptive alt -->
<img src="chart.png" alt="Bar chart showing 40% increase in Q3 sales">

<!-- вњ… Decorative image (empty alt) -->
<img src="decorative-border.png" alt="" role="presentation">

<!-- вњ… Complex image with longer description -->
<figure>
  <img src="infographic.png" alt="2024 market trends infographic" 
       aria-describedby="infographic-desc">
  <figcaption id="infographic-desc">
    <!-- Detailed description -->
  </figcaption>
</figure>
```

**Icon buttons need accessible names:**
```html
<!-- вќЊ No accessible name -->
<button><svg><!-- menu icon --></svg></button>

<!-- вњ… Using aria-label -->
<button aria-label="Open menu">
  <svg aria-hidden="true"><!-- menu icon --></svg>
</button>

<!-- вњ… Using visually hidden text -->
<button>
  <svg aria-hidden="true"><!-- menu icon --></svg>
  <span class="visually-hidden">Open menu</span>
</button>
```

**Visually hidden class:**
```css
.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}
```

### Color contrast (1.4.3, 1.4.6)

| Text Size | AA minimum | AAA enhanced |
|-----------|------------|--------------|
| Normal text (< 18px / < 14px bold) | 4.5:1 | 7:1 |
| Large text (в‰Ґ 18px / в‰Ґ 14px bold) | 3:1 | 4.5:1 |
| UI components & graphics | 3:1 | 3:1 |

```css
/* вќЊ Low contrast (2.5:1) */
.low-contrast {
  color: #999;
  background: #fff;
}

/* вњ… Sufficient contrast (7:1) */
.high-contrast {
  color: #333;
  background: #fff;
}

/* вњ… Focus states need contrast too */
:focus-visible {
  outline: 2px solid #005fcc;
  outline-offset: 2px;
}
```

**Don't rely on color alone:**
```html
<!-- вќЊ Only color indicates error -->
<input class="error-border">
<style>.error-border { border-color: red; }</style>

<!-- вњ… Color + icon + text -->
<div class="field-error">
  <input aria-invalid="true" aria-describedby="email-error">
  <span id="email-error" class="error-message">
    <svg aria-hidden="true"><!-- error icon --></svg>
    Please enter a valid email address
  </span>
</div>
```

### Media alternatives (1.2)

```html
<!-- Video with captions -->
<video controls>
  <source src="video.mp4" type="video/mp4">
  <track kind="captions" src="captions.vtt" srclang="en" label="English" default>
  <track kind="descriptions" src="descriptions.vtt" srclang="en" label="Descriptions">
</video>

<!-- Audio with transcript -->
<audio controls>
  <source src="podcast.mp3" type="audio/mp3">
</audio>
<details>
  <summary>Transcript</summary>
  <p>Full transcript text...</p>
</details>
```

---

## Operable

### Keyboard accessible (2.1)

**All functionality must be keyboard accessible:**
```javascript
// вќЊ Only handles click
element.addEventListener('click', handleAction);

// вњ… Handles both click and keyboard
element.addEventListener('click', handleAction);
element.addEventListener('keydown', (e) => {
  if (e.key === 'Enter' || e.key === ' ') {
    e.preventDefault();
    handleAction();
  }
});
```

**No keyboard traps:**
```javascript
// Modal focus management
function openModal(modal) {
  const focusableElements = modal.querySelectorAll(
    'button, [href], input, select, textarea, [tabindex]:not([tabindex="-1"])'
  );
  const firstElement = focusableElements[0];
  const lastElement = focusableElements[focusableElements.length - 1];
  
  // Trap focus within modal
  modal.addEventListener('keydown', (e) => {
    if (e.key === 'Tab') {
      if (

