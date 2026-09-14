---
name: web-design-guidelines
description: Review and enforce Vercel Web Interface Guidelines compliance. Checks UI code for hit targets, keyboard accessibility, focus states, hydration safety, mobile inputs, loading buttons, and anti-patterns. Use when building or reviewing UI, components, or web apps.
---

# Vercel Web Interface Guidelines & Audit Skill

This skill enforces the official **Vercel Web Interface Guidelines** across all frontend code, HTML artifacts, and React components.

---

## 🎯 Mandatory Engineering Rules

### 1. Touch Targets & Hit Areas
- Exception: If the visual target is `< 24px`, expand its hit target to `≥ 24px` (`relative after:absolute after:-inset-2`).
- On mobile screens, the minimum touch target is `44px–48px`.
- Checkboxes & radio buttons: label + control share single hit target without dead zones.

### 2. Mobile Inputs & Zoom
- `<input>` font size must be `≥ 16px` on mobile (`text-base` in Tailwind) to prevent iOS Safari auto-zoom/pan on focus.
- Never set `user-scalable=no` or `maximum-scale=1` in `<meta name="viewport">`. Never disable browser zoom.
- Never block paste: do not call `e.preventDefault()` on `onPaste`.

### 3. Focus & Keyboard Accessibility
- Interactive elements need visible focus ring: prefer `:focus-visible` over `:focus` to avoid distracting mouse users.
- Never write `outline-none` or `outline: none` without a clear `:focus-visible:ring-*` replacement.
- Sticky headers, banners, and overlays must NEVER obscure the focused element.
- Use `<button>` for actions, `<a>`/`<Link>` for navigation. Never `<div onClick>`.

### 4. Loading States & Buttons
- Submit button stays enabled until request starts; show spinner during request and keep original label.
- Minimum loading-state duration: when showing a spinner or skeleton, add short show-delay (~150–300ms) and minimum visible time (~300–500ms) to avoid flicker on fast networks.
- Menu options that open dialogs require ellipsis: `"Rename…"`, `"Export…"`. Loading states: `"Saving…"`.

### 5. Hydration & Safe Inputs
- Inputs must not lose focus or value after React SSR hydration.
- Text inputs with `value` require `onChange` (or use `defaultValue` for uncontrolled inputs).

### 6. Animation Performance
- Animate `transform` and `opacity` only (GPU compositor-friendly).
- Never use `transition: all` — list properties explicitly (`transition-colors`, `transition-transform`).
- Respect `prefers-reduced-motion` media queries.

### 7. Dark Mode & Theming
- `color-scheme: dark` on `<html>` for dark themes (fixes native scrollbars and inputs).
- `<meta name="theme-color">` matches page background.

---

## 🔍 How to Audit Code

When reviewing UI files:
1. Scan for anti-patterns: `outline-none` without ring, `transition: all`, `<div onClick>`, missing `aria-label` on icon buttons.
2. Check input font size (`text-base` on mobile).
3. Report issues in terse `file:line: issue - recommendation` format and provide the exact fix.
