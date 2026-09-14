# 🧪 04. Test-Driven Development (TDD) Discipline

## The Unbreakable Law
**NO production code is written without a failing test first.**

```mermaid
flowchart TD
    Red["1. RED Phase<br/>(Write test, run it, assert EXPECTED failure)"] --> 
    Green["2. GREEN Phase<br/>(Write minimal code to pass the test)"] --> 
    Refactor["3. REFACTOR Phase<br/>(Simplify 200->50, clean code, verify exit code 0)"]
    Refactor --> Red
```

## Core Standards:
- **80%+ Coverage Minimum** across business logic branches.
- **Never mock what you do not own.** Favor integration tests with ephemeral local servers over complex fake mocks.
- **Edge cases mandatory:** `None`, empty string `""`, negative numbers, max integer, network dropouts, rate limits.
- **Test Isolation:** Never write `api_key or os.getenv()`; always use `if api_key is not None:`.
