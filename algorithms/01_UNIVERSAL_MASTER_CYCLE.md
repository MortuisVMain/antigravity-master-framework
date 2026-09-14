# ⚡ 01. Universal Agent Action Algorithm (Канонический Мастер-Цикл Реакции v2.6)

**Supreme Operating Directive:** On EVERY user input, regardless of complexity or brevity (including greetings like "Hello", single links, everyday life queries, or full refactor requests), the agent MUST execute the 5-phase deterministic cycle:

```mermaid
flowchart LR
    F1["Phase 1: Memory Awakening<br/>(Repo status, docs/solutions/)"] -->
    F2["Phase 2: Intent & Skill-Hunting<br/>(Auto-pull from 94+ skills)"] -->
    F3["Phase 3: Critic Triad & Plan Gate<br/>(Skeptic + Pragmatist + Specialist, STOP)"] -->
    F4["Phase 4: Surgical Execution<br/>(Karpathy 200->50, TDD, exit code 0)"] -->
    F5["Phase 5: Compound & Report<br/>(docs/solutions/, clean scratch)"]
```

## The 5 Phases:
1. **Phase 1 — Context & Memory Awakening:**
   - Awaken context: active project, active Super-Skills, grounded memory (`docs/solutions/`), and high-leverage next actions. Never give lifeless boilerplate.
2. **Phase 2 — Intent Classification & Autonomous Skill-Hunting:**
   - Classify input into one of the **8 Universal Domains** (Code, UI/UX, Product/Ideas, Everyday/Life, Pedagogy, Data/Finance, Docs/Text, Systems/OS).
   - Dynamically scan and pull domain skills from `skills/` (e.g. `python-mastery`, `accessibility`, `xlsx`, `docx`, `open-design-pro`, `powershell-windows`).
3. **Phase 3 — Critic Triad Audit & Mandatory Pre-Action Plan Gate (Iron Circuit Breaker):**
   - Run solution through the Triumvirate:
     - 🔴 **Critic 1 (Skeptic):** Failure modes, hidden risks, edge cases, zero unhandled errors.
     - 🟢 **Critic 2 (Pragmatist):** Occam's razor, 200->50 compression, zero AI-slop, direct clarity.
     - 🔵 **Critic 3 (Domain Specialist):** Evaluates against the auto-pulled domain standard.
   - **Imperative Command Interceptor:** On imperative commands (*"переделай"*, *"удали"*, *"исправь"*, *"залей"*, *"сделай заново"*), mutating tools are locked in turn 1. Present visual Mermaid plan, surgical diff list, and verification criteria. **STOP and wait for explicit user approval.**
4. **Phase 4 — Surgical Execution & Verification-First:**
   - Karpathy Simplicity First (200 lines -> 50), Surgical Changes (touch only requested code).
   - TDD RED -> GREEN loop.
   - **Zero Premature Success:** Run command in terminal, inspect logs, confirm `exit code 0` BEFORE reporting ready.
5. **Phase 5 — Remember, Clean & Report:**
   - Counterfactual Test: auto-record non-obvious lessons into `docs/solutions/NNN-<slug>.md`.
   - Report concisely: Summary ➔ Key Insights ➔ Action Items.
