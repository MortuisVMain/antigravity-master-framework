# 🤖 The Antigravity Subagents Arsenal

Welcome to the **Antigravity Subagents Arsenal** — a collection of production-grade, specialized AI agent personas and configurations designed for parallel orchestration via `invoke_subagent` and `define_subagent`.

---

## 🎭 1. The Critic Triad (Supreme Advisory Council)
These three adversarial critics run in parallel to review plans, code, and decisions without mutual confirmation bias:

| Subagent | Role | Persona & Philosophy | Configuration File |
| :--- | :--- | :--- | :--- |
| **`critic_skeptic`** | 🔴 Red-Team Skeptic | Charlie Munger Inversion: hunts edge cases, race conditions, security holes, unstated assumptions. | [`critic-triad/critic_skeptic.md`](./critic-triad/critic_skeptic.md) |
| **`critic_pragmatist`** | 🟢 Karpathy Pragmatist | Occam's Razor: 200 lines -> 50, zero AI-slop, radical simplification, actionable brevity. | [`critic-triad/critic_pragmatist.md`](./critic-triad/critic_pragmatist.md) |
| **`critic_specialist`** | 🔵 Domain Specialist | Autonomous Skill-Hunter: pulls domain industry gold standards (Python, OKLCH, WCAG, etc.). | [`critic-triad/critic_specialist.md`](./critic-triad/critic_specialist.md) |

---

## 🛠️ 2. Specialized Engineering Subagents
Domain-level specialists for granular multi-agent execution:

| Subagent | Role | Mandate | File Link |
| :--- | :--- | :--- | :--- |
| **`architect`** | 🏛 System Architect | Ports & Adapters, system boundaries, distributed consistency, ADR creation. | [`specialists/architect.md`](./specialists/architect.md) |
| **`code_reviewer`** | 🧹 Clean Code Reviewer | Single responsibility, immutability, readability, cognitive complexity. | [`specialists/code_reviewer.md`](./specialists/code_reviewer.md) |
| **`security_reviewer`** | 🛡️ OWASP Security Auditor | Injection prevention, secret leak detection, boundary input sanitization. | [`specialists/security_reviewer.md`](./specialists/security_reviewer.md) |
| **`silent_failure_hunter`**| 🎯 Silent Failure Hunter | Zero tolerance for empty `try/except: pass`, swallowed errors, fake fallbacks. | [`specialists/silent_failure_hunter.md`](./specialists/silent_failure_hunter.md) |
| **`systematic_debugger`** | 🔬 Root-Cause Debugger | Hypothesis-deductive troubleshooting: reproducible test case before fix. | [`specialists/systematic_debugger.md`](./specialists/systematic_debugger.md) |
| **`qa_automator`** | 🧪 QA & Test Engineer | TDD red-green verification, unit/integration test generation, 80%+ coverage. | [`specialists/qa_automator.md`](./specialists/qa_automator.md) |

---

## 🚀 How to Invoke in Antigravity

```python
# Multi-subagent parallel fan-out via invoke_subagent tool:
invoke_subagent(
    Subagents=[
        {"TypeName": "critic_skeptic", "Role": "Red-Team Auditor", "Prompt": "Audit this proposal for hidden failure modes.", "Model": "pro"},
        {"TypeName": "critic_pragmatist", "Role": "Karpathy Simplifier", "Prompt": "Can this be 50 lines instead of 200? Remove all fluff.", "Model": "pro"},
        {"TypeName": "critic_specialist", "Role": "Domain Specialist", "Prompt": "Evaluate against the domain SKILL.md standards.", "Model": "pro"}
    ]
)
```
