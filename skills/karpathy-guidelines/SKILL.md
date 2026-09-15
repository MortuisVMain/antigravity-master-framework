---
name: karpathy-guidelines
description: 'Enforce Andrej Karpathy''s 4 principles: Think Before Coding, Simplicity First (200->50), Surgical Changes, and Goal-Driven.'
user-invocable: true
---

# Karpathy-Inspired Coding Guidelines

Behavioral framework derived from Andrej Karpathy's analysis of LLM coding pathologies. Biases toward caution, simplicity, and surgical precision.

---

## 1. Think Before Coding
**Don't assume. Don't hide confusion. Surface tradeoffs.**
- **State assumptions explicitly:** If uncertain about any detail, ask rather than guess.
- **Present multiple interpretations:** If ambiguity exists, show options — do not pick silently.
- **Push back when warranted:** If a simpler approach exists, propose it and challenge overcomplicated designs.
- **Stop when confused:** Name what is unclear and request clarification before editing code.

---

## 2. Simplicity First
**Minimum code that solves the problem. Nothing speculative.**
- No features beyond what was asked.
- No abstractions for single-use code.
- No "flexibility" or "configurability" that wasn't requested.
- No defensive error handling for impossible runtime scenarios.
- If 200 lines could be 50, rewrite it in 50.
- **Senior Engineer Test:** *"Would a senior engineer say this is overcomplicated?"* If yes, simplify.

---

## 3. Surgical Changes
**Touch only what you must. Clean up only your own mess.**
- When editing existing code:
  - Do NOT "improve" adjacent code, comments, or formatting.
  - Do NOT refactor things that are not broken.
  - Match existing project style, even if you would do it differently.
  - If you notice unrelated dead code, mention it in the chat — do NOT delete it.
- When changes create orphans:
  - Remove imports, variables, and functions that YOUR changes made unused.
  - Do NOT remove pre-existing dead code unless asked.
- **Verification:** Every changed line in the diff must trace directly to the user's request.

---

## 4. Goal-Driven Execution
**Define success criteria. Loop until verified.**
- Transform tasks into verifiable goals:
  - *"Add validation"* ➔ *"Write tests for invalid inputs, then make them pass"*.
  - *"Fix the bug"* ➔ *"Write a test that reproduces it, then make it pass"*.
  - *"Refactor X"* ➔ *"Ensure tests pass before and after"*.
- For multi-step tasks, state a brief plan:
  ```text
  1. [Step] -> verify: [check]
  2. [Step] -> verify: [check]
  ```
- Strong success criteria let you verify independently with exit code 0.
