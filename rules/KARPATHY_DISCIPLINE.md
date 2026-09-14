# ⚡ The 4 Andrej Karpathy Coding Principles

Enforced across all coding operations to eliminate AI overengineering, code bloat, and fragile abstractions:

---

## 1. Think Before Coding
* Never assume silently. State assumptions explicitly.
* Surface trade-offs before typing code.
* Challenge overcomplicated designs proactively.
* Stop and ask when requirements are ambiguous.

## 2. Simplicity First
* Minimum code that solves the problem. Nothing speculative.
* No single-use abstractions, helper classes, or unrequested "configurability".
* **The 200 -> 50 Test:** If 200 lines can be written in 50, rewrite in 50.
* *The Senior Engineer Test:* "Would a senior engineer say this is overcomplicated?" If yes, simplify.

## 3. Surgical Changes
* Touch only what you must.
* Never "improve" adjacent code, formatting, or comments in untouched functions.
* Clean up only your own orphans.
* Every single changed line in a git diff must trace directly to the task requirements.

## 4. Goal-Driven Execution
* Transform every task into an objective verification criterion before writing code.
* Run tests and inspect terminal logs. Loop until verified with `exit code 0`.
* **Zero Premature Success:** Never say "fixed" or "ready" without terminal verification proof.
