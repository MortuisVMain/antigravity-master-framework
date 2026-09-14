# 🔁 07. Ralph Autonomous Execution Loop (Context Rot Defense)

When tasks take longer than 15 minutes or require dozens of tool calls, single LLM contexts suffer from severe cognitive decay (context rot).

```mermaid
flowchart LR
    PRD["prd.json<br/>(Atomic User Stories)"] -->
    AgentRun["Isolated Clean Agent Run<br/>(Focus on 1 User Story)"] -->
    GitCommit["Surgical Git Commit<br/>(Semantic Commit)"] -->
    Progress["progress.txt Update<br/>(Memory Handoff)"] -->
    NextStory["Next Story in Fresh Context"]
```

## Mechanics:
- Decompose complex workflows into atomic User Stories in `prd.json`.
- Execute each story in an isolated context window with automated tests.
- Commit to git immediately upon story completion.
- Pass memory forward via `progress.txt` and `docs/solutions/`.
