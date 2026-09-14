# 🧰 Antigravity Skills Catalog (132+ Production Skills)

Welcome to the **Antigravity Skills Catalog** — the world's most comprehensive collection of specialized engineering, architecture, design, alignment, and automation skills for AI coding agents.

Each skill is a self-contained instruction bundle (`SKILL.md` + scripts/templates) that an agent autonomously absorbs to enforce domain-level best practices.

---

## ⚡ Featured: The Matt Pocock Alignment & Architecture Arsenal

In addition to the studio's core production skills, this catalog incorporates all **37 skills from Matt Pocock** (`aihero.dev` / `mattpocock/skills`):
* 🎯 **`/grill-me` & `/grill-with-docs`:** Relentless multi-round interview exploring the design tree frontier before writing a single line of code.
* 🏛 **`/improve-codebase-architecture`:** John Ousterhout deep modules audit with interactive HTML reports and Mermaid diagrams.
* 🗺 **`/wayfinder`:** Visual ticket decision maps for massive multi-session features (context rot defense).
* 💬 **`/wait-what`:** Instant reset to re-pitch explanations in plain human terms.

---

## 🚀 How to Install a Skill

### For Antigravity Agent / Google AGY:
```bash
# Clone the repository
git clone https://github.com/MortuisVMain/antigravity-master-framework.git

# Copy any individual skill into your local skills directory:
mkdir -p ~/.gemini/config/skills/<skill-name>
cp -r antigravity-master-framework/skills/<skill-name>/* ~/.gemini/config/skills/<skill-name>/

# Or install ALL 132 skills at once:
cp -r antigravity-master-framework/skills/* ~/.gemini/config/skills/
```

### For Claude Code / Cursor:
```bash
# Symlink or copy matching skill into Claude Code skills:
mkdir -p ~/.claude/skills/<skill-name>
cp -r antigravity-master-framework/skills/<skill-name>/* ~/.claude/skills/<skill-name>/
```

---

## 🗂️ Categorized Directory

### 🎯 Alignment, Grilling & Strategic POV

| Skill | Description | Direct Link |
| :--- | :--- | :---: |
| **`grill-me`** | A relentless interview to sharpen a plan or design. | [`skills/grill-me/`](./grill-me/SKILL.md) |
| **`grill-with-docs`** | A relentless interview to sharpen a plan or design, which also creates docs (ADR's and glossary) as we go. | [`skills/grill-with-docs/`](./grill-with-docs/SKILL.md) |
| **`grilling`** | Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'g... | [`skills/grilling/`](./grilling/SKILL.md) |
| **`ce-strategy`** | "Create or update STRATEGY.md. Use when starting a product, adding a strategy doc to an existing repo, changing direction or roadm... | [`skills/ce-strategy/`](./ce-strategy/SKILL.md) |
| **`ce-brainstorm`** | "Explore vague or ambitious ideas into a right-sized requirements-only unified plan. Use when the user wants to brainstorm, scope ... | [`skills/ce-brainstorm/`](./ce-brainstorm/SKILL.md) |
| **`ce-pov`** | "Give a decisive, project-grounded point of view: a graded verdict on an external-adoption question, a holistic take on a document... | [`skills/ce-pov/`](./ce-pov/SKILL.md) |
| **`ce-ideate`** | "Generate and evaluate grounded ideas. Use when the user wants ideas, improvements, or surprising directions before choosing one t... | [`skills/ce-ideate/`](./ce-ideate/SKILL.md) |
| **`critic-triad`** | "Global 3-Critic Supreme Council & Autonomous Skill-Hunter. Dynamically summons a Triad of adversarial critics (1: Red-Team Skepti... | [`skills/critic-triad/`](./critic-triad/SKILL.md) |

### 🏛 Architecture & Codebase Design

| Skill | Description | Direct Link |
| :--- | :--- | :---: |
| **`improve-codebase-architecture`** | Scan a codebase for deepening opportunities, present them as a visual HTML report, then grill through whichever one you pick. | [`skills/improve-codebase-architecture/`](./improve-codebase-architecture/SKILL.md) |
| **`codebase-design`** | Shared vocabulary for designing deep modules. Use when the user wants to design or improve a module's interface, find deepening op... | [`skills/codebase-design/`](./codebase-design/SKILL.md) |
| **`domain-modeling`** | Build and sharpen a project's domain model. Use when discussing codebase terminology, writing or editing a CONTEXT.md, or recordin... | [`skills/domain-modeling/`](./domain-modeling/SKILL.md) |
| **`architecture-patterns`** | Design, implement, and refactor Ports & Adapters systems with clear domain boundaries, dependency inversion, and testable use-case... | [`skills/architecture-patterns/`](./architecture-patterns/SKILL.md) |
| **`architecture-decision-records`** | Capture architectural decisions made during Claude Code sessions as structured ADRs. Auto-detects decision moments, records contex... | [`skills/architecture-decision-records/`](./architecture-decision-records/SKILL.md) |
| **`senior-architect`** | ﻿--- | [`skills/senior-architect/`](./senior-architect/SKILL.md) |
| **`setup-ts-deep-modules`** | Wire dependency-cruiser into a TypeScript repo so each package is a deep module, with implementation hidden in subfolders and reac... | [`skills/setup-ts-deep-modules/`](./setup-ts-deep-modules/SKILL.md) |

### 💻 Languages, Backends & Frameworks

| Skill | Description | Direct Link |
| :--- | :--- | :---: |
| **`python-mastery`** | "Master modern Python 3.12+ engineering and architecture. Fuses idiomatic Python patterns, high-performance asyncio concurrency, P... | [`skills/python-mastery/`](./python-mastery/SKILL.md) |
| **`python-patterns`** | ﻿--- | [`skills/python-patterns/`](./python-patterns/SKILL.md) |
| **`typescript-expert`** | ﻿--- | [`skills/typescript-expert/`](./typescript-expert/SKILL.md) |
| **`javascript-mastery`** | ﻿--- | [`skills/javascript-mastery/`](./javascript-mastery/SKILL.md) |
| **`fastapi-pro`** | ﻿--- | [`skills/fastapi-pro/`](./fastapi-pro/SKILL.md) |
| **`django-pro`** | ﻿--- | [`skills/django-pro/`](./django-pro/SKILL.md) |
| **`rust-patterns`** | Idiomatic Rust patterns, ownership, error handling, traits, concurrency, and best practices for building safe, performant applicat... | [`skills/rust-patterns/`](./rust-patterns/SKILL.md) |
| **`cpp-pro`** | C++ coding standards based on the C++ Core Guidelines (isocpp.github.io). Use when writing, reviewing, or refactoring C++ code to ... | [`skills/cpp-pro/`](./cpp-pro/SKILL.md) |
| **`react-patterns`** | ﻿--- | [`skills/react-patterns/`](./react-patterns/SKILL.md) |
| **`nextjs-best-practices`** | ﻿--- | [`skills/nextjs-best-practices/`](./nextjs-best-practices/SKILL.md) |
| **`react-best-practices`** | ﻿--- | [`skills/react-best-practices/`](./react-best-practices/SKILL.md) |

### 🎨 UI/UX, Design Systems & Frontend

| Skill | Description | Direct Link |
| :--- | :--- | :---: |
| **`open-design-pro`** | "Master design engineering and anti-slop frontend engine. Fuses DESIGN.md token contracts (OKLCH, typography, elevation), Taste-dr... | [`skills/open-design-pro/`](./open-design-pro/SKILL.md) |
| **`taste-skill`** | Anti-slop frontend skill for landing pages, portfolios, and redesigns. The agent reads the brief, infers the right design directio... | [`skills/taste-skill/`](./taste-skill/SKILL.md) |
| **`ui-ux-pro-max`** | ﻿--- | [`skills/ui-ux-pro-max/`](./ui-ux-pro-max/SKILL.md) |
| **`design-to-code`** | ﻿--- | [`skills/design-to-code/`](./design-to-code/SKILL.md) |
| **`image-to-code`** | Elite website image-to-code skill for Codex. For visually important web tasks, it must first generate the design image(s) itself, ... | [`skills/image-to-code/`](./image-to-code/SKILL.md) |
| **`figma-implement-design`** | ﻿--- | [`skills/figma-implement-design/`](./figma-implement-design/SKILL.md) |
| **`accessibility`** | ﻿--- | [`skills/accessibility/`](./accessibility/SKILL.md) |
| **`core-web-vitals`** | ﻿--- | [`skills/core-web-vitals/`](./core-web-vitals/SKILL.md) |
| **`web-design-guidelines`** | Review and enforce Vercel Web Interface Guidelines compliance. Checks UI code for hit targets, keyboard accessibility, focus state... | [`skills/web-design-guidelines/`](./web-design-guidelines/SKILL.md) |
| **`web-quality-audit`** | ﻿--- | [`skills/web-quality-audit/`](./web-quality-audit/SKILL.md) |
| **`react-ui-patterns`** | ﻿--- | [`skills/react-ui-patterns/`](./react-ui-patterns/SKILL.md) |
| **`senior-frontend`** | ﻿--- | [`skills/senior-frontend/`](./senior-frontend/SKILL.md) |

### 🧪 Testing, Quality & Systematic Debugging

| Skill | Description | Direct Link |
| :--- | :--- | :---: |
| **`tdd-workflow`** | Use this skill when writing new features, fixing bugs, or refactoring code. Enforces test-driven development with 80%+ coverage in... | [`skills/tdd-workflow/`](./tdd-workflow/SKILL.md) |
| **`tdd`** | Test-driven development. Use when the user wants to build features or fix bugs test-first, mentions "red-green-refactor", or wants... | [`skills/tdd/`](./tdd/SKILL.md) |
| **`systematic-debugger`** | "Master systematic debugging and error diagnosis engine. Fuses first-principles root cause analysis, reproducible test creation (T... | [`skills/systematic-debugger/`](./systematic-debugger/SKILL.md) |
| **`diagnosing-bugs`** | Diagnosis loop for hard bugs and performance regressions. Use when the user says "diagnose"/"debug this", or reports something bro... | [`skills/diagnosing-bugs/`](./diagnosing-bugs/SKILL.md) |
| **`code-reviewer-pro`** | "Master code review, refactoring, and code simplification engine. Fuses Clean Code standards (SOLID, DRY, immutability), Multi-Age... | [`skills/code-reviewer-pro/`](./code-reviewer-pro/SKILL.md) |
| **`ce-code-review`** | "Structured code review for bugs, regressions, tests, and standards. Use before PRs or when asked to review code. Use when the use... | [`skills/ce-code-review/`](./ce-code-review/SKILL.md) |
| **`code-review`** | "Review the changes since a fixed point (commit, branch, tag, or merge-base) along two axes: Standards (does the code follow this ... | [`skills/code-review/`](./code-review/SKILL.md) |
| **`python-testing-patterns`** | Python testing strategies using pytest, TDD methodology, fixtures, mocking, parametrization, and coverage requirements. Use when w... | [`skills/python-testing-patterns/`](./python-testing-patterns/SKILL.md) |
| **`csharp-testing`** | C# and .NET testing patterns with xUnit, FluentAssertions, mocking, integration tests, and test organization best practices. Use w... | [`skills/csharp-testing/`](./csharp-testing/SKILL.md) |
| **`cpp-testing`** | Use only when writing/updating/fixing C++ tests, configuring GoogleTest/CTest, diagnosing failing or flaky tests, or adding covera... | [`skills/cpp-testing/`](./cpp-testing/SKILL.md) |
| **`rust-testing`** | Rust testing patterns including unit tests, integration tests, async testing, property-based testing, mocking, and coverage. Follo... | [`skills/rust-testing/`](./rust-testing/SKILL.md) |
| **`windows-desktop-e2e`** | E2E testing for Windows native desktop apps (WPF, WinForms, Win32/MFC, Qt) using pywinauto and Windows UI Automation. Use when wri... | [`skills/windows-desktop-e2e/`](./windows-desktop-e2e/SKILL.md) |
| **`senior-qa`** | ﻿--- | [`skills/senior-qa/`](./senior-qa/SKILL.md) |
| **`skill-repair`** | \| | [`skills/skill-repair/`](./skill-repair/SKILL.md) |
| **`ce-test-browser`** | Run browser tests for pages affected by the current branch or PR. Use when asked to run or check browser tests for the current cha... | [`skills/ce-test-browser/`](./ce-test-browser/SKILL.md) |
| **`ce-resolve-pr-feedback`** | Resolve PR review feedback. Use when addressing feedback already left on a PR. Not for reviewing the code before feedback exists; ... | [`skills/ce-resolve-pr-feedback/`](./ce-resolve-pr-feedback/SKILL.md) |

### 🗺 Planning, Wayfinding, Tickets & Execution

| Skill | Description | Direct Link |
| :--- | :--- | :---: |
| **`execution-planner`** | "Master engineering execution planner and architectural design engine. Fuses proactive requirement grilling (/grill-me mode), trad... | [`skills/execution-planner/`](./execution-planner/SKILL.md) |
| **`wayfinder`** | Plan a huge chunk of work (more than one agent session can hold) as a shared map of decision tickets on your issue tracker, and re... | [`skills/wayfinder/`](./wayfinder/SKILL.md) |
| **`to-spec`** | "Turn the current conversation into a spec and publish it to the project issue tracker: no interview, just synthesis of what you'v... | [`skills/to-spec/`](./to-spec/SKILL.md) |
| **`to-tickets`** | Break a plan, spec, or the current conversation into a set of tracer-bullet tickets, each declaring its blocking edges, published ... | [`skills/to-tickets/`](./to-tickets/SKILL.md) |
| **`triage`** | Move issues and external PRs through a state machine of triage roles, categorise, verify, grill if needed, and write agent-ready b... | [`skills/triage/`](./triage/SKILL.md) |
| **`prototype`** | Build a throwaway prototype to answer a design question. Use when the user wants to sanity-check whether a state model or logic fe... | [`skills/prototype/`](./prototype/SKILL.md) |
| **`ce-prototype`** | Build a throwaway prototype to answer how something should work, feel, or read. Use when committing the wrong answer would be expe... | [`skills/ce-prototype/`](./ce-prototype/SKILL.md) |
| **`prd`** | "Generate a Product Requirements Document (PRD) for a new feature. Use when planning a feature, starting a new project, or when as... | [`skills/prd/`](./prd/SKILL.md) |
| **`ralph`** | "Convert PRDs to prd.json format for the Ralph autonomous agent system. Use when you have an existing PRD and need to convert it t... | [`skills/ralph/`](./ralph/SKILL.md) |
| **`ce-work`** | Execute a plan or concrete work prompt end-to-end. Use when implementing from a plan document, a spec path, or a clear build reque... | [`skills/ce-work/`](./ce-work/SKILL.md) |
| **`lfg`** | "Run the full autonomous shipping pipeline end-to-end, hands-off with no check-ins. Use only when the user explicitly asks to buil... | [`skills/lfg/`](./lfg/SKILL.md) |
| **`implement`** | "Implement a piece of work based on a spec or set of tickets." | [`skills/implement/`](./implement/SKILL.md) |
| **`implement-spec`** | "Implement a specification in code." | [`skills/implement-spec/`](./implement-spec/SKILL.md) |
| **`ce-worktree`** | Set up isolated git worktrees — create a new branch for fresh work, or attach a worktree to an existing branch, PR, or commit. Use... | [`skills/ce-worktree/`](./ce-worktree/SKILL.md) |
| **`ask-matt`** | Ask which skill or flow fits your situation. A router over the skills in this repo. | [`skills/ask-matt/`](./ask-matt/SKILL.md) |

### ✍️ Productivity, Communication, Pedagogy & Docs

| Skill | Description | Direct Link |
| :--- | :--- | :---: |
| **`wait-what`** | "Stop. That last message did not land: re-pitch it." | [`skills/wait-what/`](./wait-what/SKILL.md) |
| **`teach`** | Teach the user a new skill or concept, within this workspace. | [`skills/teach/`](./teach/SKILL.md) |
| **`to-questionnaire`** | Turn a decision you can't fully answer into a questionnaire for someone else to fill in. | [`skills/to-questionnaire/`](./to-questionnaire/SKILL.md) |
| **`writing-for-agents`** | Writing documents for agents. Use when creating or editing skills, or modifying AGENTS.md or CLAUDE.md. | [`skills/writing-for-agents/`](./writing-for-agents/SKILL.md) |
| **`writing-beats`** | Writing, exploit; assemble raw material into a journey of beats, grounding each term before a beat leans on it. | [`skills/writing-beats/`](./writing-beats/SKILL.md) |
| **`writing-fragments`** | "Writing, explore: mine raw fragments, no structure yet." | [`skills/writing-fragments/`](./writing-fragments/SKILL.md) |
| **`writing-shape`** | "Writing, exploit: shape raw material into an article, paragraph by paragraph." | [`skills/writing-shape/`](./writing-shape/SKILL.md) |
| **`ce-explain`** | "Create a durable visual teaching artifact for something worth learning. Use when the user wants to be taught, wants a deep explai... | [`skills/ce-explain/`](./ce-explain/SKILL.md) |
| **`ce-doc-review`** | Review requirements, plans, or specs with role-specific lenses. Use when the user wants to improve an existing planning document. | [`skills/ce-doc-review/`](./ce-doc-review/SKILL.md) |
| **`ce-polish`** | "Polish a working feature through user-directed live browser feedback. Use when a functional feature needs focused UX refinement b... | [`skills/ce-polish/`](./ce-polish/SKILL.md) |
| **`handoff`** | Compact the current conversation into a handoff document for another agent to pick up. | [`skills/handoff/`](./handoff/SKILL.md) |
| **`claude-handoff`** | Hand the current conversation off to a fresh background agent that picks up the work immediately. | [`skills/claude-handoff/`](./claude-handoff/SKILL.md) |
| **`ce-handoff`** | Create a session handoff for another agent, or resume, find, and read any user-selected continuity source. Use when work or conver... | [`skills/ce-handoff/`](./ce-handoff/SKILL.md) |
| **`retro`** | "Conduct a retrospective on a coding session." | [`skills/retro/`](./retro/SKILL.md) |
| **`loop-me`** | Grill me about specs for the workflows I want to build, within this workspace. | [`skills/loop-me/`](./loop-me/SKILL.md) |
| **`docx`** | ﻿--- | [`skills/docx/`](./docx/SKILL.md) |
| **`pdf-processing-pro`** | ﻿--- | [`skills/pdf-processing-pro/`](./pdf-processing-pro/SKILL.md) |
| **`ce-compound`** | Document a solved problem as a durable repo learning. Use when verified work produced non-obvious reasoning absent from its final ... | [`skills/ce-compound/`](./ce-compound/SKILL.md) |
| **`ce-compound-refresh`** | Refresh the repo's captured learnings against the current codebase. Use when auditing stale, overlapping, superseded, or drifted l... | [`skills/ce-compound-refresh/`](./ce-compound-refresh/SKILL.md) |

### 📊 Data Science, Analytics, ML & Databases

| Skill | Description | Direct Link |
| :--- | :--- | :---: |
| **`xlsx`** | ﻿--- | [`skills/xlsx/`](./xlsx/SKILL.md) |
| **`senior-data-scientist`** | ﻿--- | [`skills/senior-data-scientist/`](./senior-data-scientist/SKILL.md) |
| **`senior-ml-engineer`** | ﻿--- | [`skills/senior-ml-engineer/`](./senior-ml-engineer/SKILL.md) |
| **`ml-best-practices`** | \| | [`skills/ml-best-practices/`](./ml-best-practices/SKILL.md) |
| **`database-schema-designer`** | ﻿--- | [`skills/database-schema-designer/`](./database-schema-designer/SKILL.md) |
| **`database-migrations`** | Database migration best practices for schema changes, data migrations, rollbacks, and zero-downtime deployments across PostgreSQL,... | [`skills/database-migrations/`](./database-migrations/SKILL.md) |
| **`api-platform-builder`** | ﻿--- | [`skills/api-platform-builder/`](./api-platform-builder/SKILL.md) |
| **`senior-backend`** | ﻿--- | [`skills/senior-backend/`](./senior-backend/SKILL.md) |
| **`senior-fullstack`** | ﻿--- | [`skills/senior-fullstack/`](./senior-fullstack/SKILL.md) |
| **`ce-optimize`** | "Optimize a named target with a measured loop: attribute a workload's cost, or score variants and keep winners. Use when a working... | [`skills/ce-optimize/`](./ce-optimize/SKILL.md) |

### ⚙️ DevOps, Cloud, Automation & Tooling

| Skill | Description | Direct Link |
| :--- | :--- | :---: |
| **`powershell-windows`** | ﻿--- | [`skills/powershell-windows/`](./powershell-windows/SKILL.md) |
| **`bash-pro`** | ﻿--- | [`skills/bash-pro/`](./bash-pro/SKILL.md) |
| **`docker-expert`** | ﻿--- | [`skills/docker-expert/`](./docker-expert/SKILL.md) |
| **`devops-and-cloud`** | ﻿--- | [`skills/devops-and-cloud/`](./devops-and-cloud/SKILL.md) |
| **`senior-devops`** | ﻿--- | [`skills/senior-devops/`](./senior-devops/SKILL.md) |
| **`senior-security`** | ﻿--- | [`skills/senior-security/`](./senior-security/SKILL.md) |
| **`git-guardrails-claude-code`** | Set up Claude Code hooks to block dangerous git commands (push, reset --hard, clean, branch -D, etc.) before they execute. Use whe... | [`skills/git-guardrails-claude-code/`](./git-guardrails-claude-code/SKILL.md) |
| **`setup-pre-commit`** | Set up Husky pre-commit hooks with lint-staged (Prettier), type checking, and tests in the current repo. Use when user wants to ad... | [`skills/setup-pre-commit/`](./setup-pre-commit/SKILL.md) |
| **`setup-matt-pocock-skills`** | "Configure this repo for the engineering skills: set up its issue tracker, triage label vocabulary, and domain doc layout. Run onc... | [`skills/setup-matt-pocock-skills/`](./setup-matt-pocock-skills/SKILL.md) |
| **`resolving-merge-conflicts`** | "Use when you need to resolve an in-progress git merge/rebase conflict." | [`skills/resolving-merge-conflicts/`](./resolving-merge-conflicts/SKILL.md) |
| **`wizard`** | Generate an interactive bash wizard that walks a human through steps only they can perform. Use when provisioning infrastructure, ... | [`skills/wizard/`](./wizard/SKILL.md) |
| **`migrate-to-shoehorn`** | Migrate test files from `as` type assertions to @total-typescript/shoehorn. Use when user mentions shoehorn, wants to replace `as`... | [`skills/migrate-to-shoehorn/`](./migrate-to-shoehorn/SKILL.md) |
| **`scaffold-exercises`** | Create exercise directory structures with sections, problems, solutions, and explainers that pass linting. Use when user wants to ... | [`skills/scaffold-exercises/`](./scaffold-exercises/SKILL.md) |
| **`file-organizer`** | ﻿--- | [`skills/file-organizer/`](./file-organizer/SKILL.md) |
| **`benchmark-optimization-loop`** | Use when the user asks to make something faster, try many variants, run recursive optimization, benchmark latency/throughput/cost,... | [`skills/benchmark-optimization-loop/`](./benchmark-optimization-loop/SKILL.md) |
| **`performance`** | ﻿--- | [`skills/performance/`](./performance/SKILL.md) |
| **`video-downloader`** | ﻿--- | [`skills/video-downloader/`](./video-downloader/SKILL.md) |
| **`image-enhancer`** | ﻿--- | [`skills/image-enhancer/`](./image-enhancer/SKILL.md) |
| **`web-to-markdown`** | ﻿--- | [`skills/web-to-markdown/`](./web-to-markdown/SKILL.md) |
| **`playwright`** | ﻿--- | [`skills/playwright/`](./playwright/SKILL.md) |
| **`research`** | Investigate a question against high-trust primary sources and capture the findings as a Markdown file in the repo. Use when the us... | [`skills/research/`](./research/SKILL.md) |
| **`game-development`** | ﻿--- | [`skills/game-development/`](./game-development/SKILL.md) |
| **`blender-motion-state-inspection`** | Use this skill when inspecting Blender characters, rigs, poses, animation retargeting, ground contact, facing direction, or model-... | [`skills/blender-motion-state-inspection/`](./blender-motion-state-inspection/SKILL.md) |
| **`screenshot-feature-extractor`** | ﻿--- | [`skills/screenshot-feature-extractor/`](./screenshot-feature-extractor/SKILL.md) |
| **`personal-tool-builder`** | ﻿--- | [`skills/personal-tool-builder/`](./personal-tool-builder/SKILL.md) |
| **`seo`** | ﻿--- | [`skills/seo/`](./seo/SKILL.md) |
| **`accidental-data-loss-prevention`** | \| | [`skills/accidental-data-loss-prevention/`](./accidental-data-loss-prevention/SKILL.md) |
| **`clean-code`** | Baseline cross-project coding conventions for naming, readability, immutability, and code-quality review. Use detailed frontend or... | [`skills/clean-code/`](./clean-code/SKILL.md) |
| **`karpathy-guidelines`** | "Enforce Andrej Karpathy's 4 core coding principles: Think Before Coding, Simplicity First, Surgical Changes, and Goal-Driven Exec... | [`skills/karpathy-guidelines/`](./karpathy-guidelines/SKILL.md) |
| **`lavish`** | Turn complex or visual agent responses into rich, reviewable HTML artifacts the user can annotate and send feedback on, using the ... | [`skills/lavish/`](./lavish/SKILL.md) |
| **`mermaid-diagrams`** | ﻿--- | [`skills/mermaid-diagrams/`](./mermaid-diagrams/SKILL.md) |
| **`senior-prompt-engineer`** | ﻿--- | [`skills/senior-prompt-engineer/`](./senior-prompt-engineer/SKILL.md) |
| **`ce-setup`** | "Check Compound Engineering health and repo-local config." | [`skills/ce-setup/`](./ce-setup/SKILL.md) |

---

## 📚 Complete Alphabetical Skills Directory (132 Skills)

| # | Skill Name | Description | Path |
| :-: | :--- | :--- | :---: |
| 1 | **`accessibility`** | ﻿--- | [`skills/accessibility/`](./accessibility/SKILL.md) |
| 2 | **`accidental-data-loss-prevention`** | \| | [`skills/accidental-data-loss-prevention/`](./accidental-data-loss-prevention/SKILL.md) |
| 3 | **`api-platform-builder`** | ﻿--- | [`skills/api-platform-builder/`](./api-platform-builder/SKILL.md) |
| 4 | **`architecture-decision-records`** | Capture architectural decisions made during Claude Code sessions as structured ADRs. Auto-detects decision moments, records contex... | [`skills/architecture-decision-records/`](./architecture-decision-records/SKILL.md) |
| 5 | **`architecture-patterns`** | Design, implement, and refactor Ports & Adapters systems with clear domain boundaries, dependency inversion, and testable use-case... | [`skills/architecture-patterns/`](./architecture-patterns/SKILL.md) |
| 6 | **`ask-matt`** | Ask which skill or flow fits your situation. A router over the skills in this repo. | [`skills/ask-matt/`](./ask-matt/SKILL.md) |
| 7 | **`bash-pro`** | ﻿--- | [`skills/bash-pro/`](./bash-pro/SKILL.md) |
| 8 | **`benchmark-optimization-loop`** | Use when the user asks to make something faster, try many variants, run recursive optimization, benchmark latency/throughput/cost,... | [`skills/benchmark-optimization-loop/`](./benchmark-optimization-loop/SKILL.md) |
| 9 | **`blender-motion-state-inspection`** | Use this skill when inspecting Blender characters, rigs, poses, animation retargeting, ground contact, facing direction, or model-... | [`skills/blender-motion-state-inspection/`](./blender-motion-state-inspection/SKILL.md) |
| 10 | **`ce-brainstorm`** | "Explore vague or ambitious ideas into a right-sized requirements-only unified plan. Use when the user wants to brainstorm, scope ... | [`skills/ce-brainstorm/`](./ce-brainstorm/SKILL.md) |
| 11 | **`ce-code-review`** | "Structured code review for bugs, regressions, tests, and standards. Use before PRs or when asked to review code. Use when the use... | [`skills/ce-code-review/`](./ce-code-review/SKILL.md) |
| 12 | **`ce-commit-push-pr`** | Commit, push, and open a PR. Use when asked to ship/open a PR, or for PR-description-only flows like writing, rewriting, or descri... | [`skills/ce-commit-push-pr/`](./ce-commit-push-pr/SKILL.md) |
| 13 | **`ce-compound`** | Document a solved problem as a durable repo learning. Use when verified work produced non-obvious reasoning absent from its final ... | [`skills/ce-compound/`](./ce-compound/SKILL.md) |
| 14 | **`ce-compound-refresh`** | Refresh the repo's captured learnings against the current codebase. Use when auditing stale, overlapping, superseded, or drifted l... | [`skills/ce-compound-refresh/`](./ce-compound-refresh/SKILL.md) |
| 15 | **`ce-doc-review`** | Review requirements, plans, or specs with role-specific lenses. Use when the user wants to improve an existing planning document. | [`skills/ce-doc-review/`](./ce-doc-review/SKILL.md) |
| 16 | **`ce-explain`** | "Create a durable visual teaching artifact for something worth learning. Use when the user wants to be taught, wants a deep explai... | [`skills/ce-explain/`](./ce-explain/SKILL.md) |
| 17 | **`ce-handoff`** | Create a session handoff for another agent, or resume, find, and read any user-selected continuity source. Use when work or conver... | [`skills/ce-handoff/`](./ce-handoff/SKILL.md) |
| 18 | **`ce-ideate`** | "Generate and evaluate grounded ideas. Use when the user wants ideas, improvements, or surprising directions before choosing one t... | [`skills/ce-ideate/`](./ce-ideate/SKILL.md) |
| 19 | **`ce-optimize`** | "Optimize a named target with a measured loop: attribute a workload's cost, or score variants and keep winners. Use when a working... | [`skills/ce-optimize/`](./ce-optimize/SKILL.md) |
| 20 | **`ce-polish`** | "Polish a working feature through user-directed live browser feedback. Use when a functional feature needs focused UX refinement b... | [`skills/ce-polish/`](./ce-polish/SKILL.md) |
| 21 | **`ce-pov`** | "Give a decisive, project-grounded point of view: a graded verdict on an external-adoption question, a holistic take on a document... | [`skills/ce-pov/`](./ce-pov/SKILL.md) |
| 22 | **`ce-prototype`** | Build a throwaway prototype to answer how something should work, feel, or read. Use when committing the wrong answer would be expe... | [`skills/ce-prototype/`](./ce-prototype/SKILL.md) |
| 23 | **`ce-resolve-pr-feedback`** | Resolve PR review feedback. Use when addressing feedback already left on a PR. Not for reviewing the code before feedback exists; ... | [`skills/ce-resolve-pr-feedback/`](./ce-resolve-pr-feedback/SKILL.md) |
| 24 | **`ce-setup`** | "Check Compound Engineering health and repo-local config." | [`skills/ce-setup/`](./ce-setup/SKILL.md) |
| 25 | **`ce-strategy`** | "Create or update STRATEGY.md. Use when starting a product, adding a strategy doc to an existing repo, changing direction or roadm... | [`skills/ce-strategy/`](./ce-strategy/SKILL.md) |
| 26 | **`ce-test-browser`** | Run browser tests for pages affected by the current branch or PR. Use when asked to run or check browser tests for the current cha... | [`skills/ce-test-browser/`](./ce-test-browser/SKILL.md) |
| 27 | **`ce-work`** | Execute a plan or concrete work prompt end-to-end. Use when implementing from a plan document, a spec path, or a clear build reque... | [`skills/ce-work/`](./ce-work/SKILL.md) |
| 28 | **`ce-worktree`** | Set up isolated git worktrees — create a new branch for fresh work, or attach a worktree to an existing branch, PR, or commit. Use... | [`skills/ce-worktree/`](./ce-worktree/SKILL.md) |
| 29 | **`claude-handoff`** | Hand the current conversation off to a fresh background agent that picks up the work immediately. | [`skills/claude-handoff/`](./claude-handoff/SKILL.md) |
| 30 | **`clean-code`** | Baseline cross-project coding conventions for naming, readability, immutability, and code-quality review. Use detailed frontend or... | [`skills/clean-code/`](./clean-code/SKILL.md) |
| 31 | **`code-review`** | "Review the changes since a fixed point (commit, branch, tag, or merge-base) along two axes: Standards (does the code follow this ... | [`skills/code-review/`](./code-review/SKILL.md) |
| 32 | **`code-reviewer-pro`** | "Master code review, refactoring, and code simplification engine. Fuses Clean Code standards (SOLID, DRY, immutability), Multi-Age... | [`skills/code-reviewer-pro/`](./code-reviewer-pro/SKILL.md) |
| 33 | **`codebase-design`** | Shared vocabulary for designing deep modules. Use when the user wants to design or improve a module's interface, find deepening op... | [`skills/codebase-design/`](./codebase-design/SKILL.md) |
| 34 | **`core-web-vitals`** | ﻿--- | [`skills/core-web-vitals/`](./core-web-vitals/SKILL.md) |
| 35 | **`cpp-pro`** | C++ coding standards based on the C++ Core Guidelines (isocpp.github.io). Use when writing, reviewing, or refactoring C++ code to ... | [`skills/cpp-pro/`](./cpp-pro/SKILL.md) |
| 36 | **`cpp-testing`** | Use only when writing/updating/fixing C++ tests, configuring GoogleTest/CTest, diagnosing failing or flaky tests, or adding covera... | [`skills/cpp-testing/`](./cpp-testing/SKILL.md) |
| 37 | **`critic-triad`** | "Global 3-Critic Supreme Council & Autonomous Skill-Hunter. Dynamically summons a Triad of adversarial critics (1: Red-Team Skepti... | [`skills/critic-triad/`](./critic-triad/SKILL.md) |
| 38 | **`csharp-testing`** | C# and .NET testing patterns with xUnit, FluentAssertions, mocking, integration tests, and test organization best practices. Use w... | [`skills/csharp-testing/`](./csharp-testing/SKILL.md) |
| 39 | **`database-migrations`** | Database migration best practices for schema changes, data migrations, rollbacks, and zero-downtime deployments across PostgreSQL,... | [`skills/database-migrations/`](./database-migrations/SKILL.md) |
| 40 | **`database-schema-designer`** | ﻿--- | [`skills/database-schema-designer/`](./database-schema-designer/SKILL.md) |
| 41 | **`design-to-code`** | ﻿--- | [`skills/design-to-code/`](./design-to-code/SKILL.md) |
| 42 | **`devops-and-cloud`** | ﻿--- | [`skills/devops-and-cloud/`](./devops-and-cloud/SKILL.md) |
| 43 | **`diagnosing-bugs`** | Diagnosis loop for hard bugs and performance regressions. Use when the user says "diagnose"/"debug this", or reports something bro... | [`skills/diagnosing-bugs/`](./diagnosing-bugs/SKILL.md) |
| 44 | **`django-pro`** | ﻿--- | [`skills/django-pro/`](./django-pro/SKILL.md) |
| 45 | **`docker-expert`** | ﻿--- | [`skills/docker-expert/`](./docker-expert/SKILL.md) |
| 46 | **`docx`** | ﻿--- | [`skills/docx/`](./docx/SKILL.md) |
| 47 | **`domain-modeling`** | Build and sharpen a project's domain model. Use when discussing codebase terminology, writing or editing a CONTEXT.md, or recordin... | [`skills/domain-modeling/`](./domain-modeling/SKILL.md) |
| 48 | **`execution-planner`** | "Master engineering execution planner and architectural design engine. Fuses proactive requirement grilling (/grill-me mode), trad... | [`skills/execution-planner/`](./execution-planner/SKILL.md) |
| 49 | **`fastapi-pro`** | ﻿--- | [`skills/fastapi-pro/`](./fastapi-pro/SKILL.md) |
| 50 | **`figma-implement-design`** | ﻿--- | [`skills/figma-implement-design/`](./figma-implement-design/SKILL.md) |
| 51 | **`file-organizer`** | ﻿--- | [`skills/file-organizer/`](./file-organizer/SKILL.md) |
| 52 | **`game-development`** | ﻿--- | [`skills/game-development/`](./game-development/SKILL.md) |
| 53 | **`git-guardrails-claude-code`** | Set up Claude Code hooks to block dangerous git commands (push, reset --hard, clean, branch -D, etc.) before they execute. Use whe... | [`skills/git-guardrails-claude-code/`](./git-guardrails-claude-code/SKILL.md) |
| 54 | **`grill-me`** | A relentless interview to sharpen a plan or design. | [`skills/grill-me/`](./grill-me/SKILL.md) |
| 55 | **`grill-with-docs`** | A relentless interview to sharpen a plan or design, which also creates docs (ADR's and glossary) as we go. | [`skills/grill-with-docs/`](./grill-with-docs/SKILL.md) |
| 56 | **`grilling`** | Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'g... | [`skills/grilling/`](./grilling/SKILL.md) |
| 57 | **`handoff`** | Compact the current conversation into a handoff document for another agent to pick up. | [`skills/handoff/`](./handoff/SKILL.md) |
| 58 | **`image-enhancer`** | ﻿--- | [`skills/image-enhancer/`](./image-enhancer/SKILL.md) |
| 59 | **`image-to-code`** | Elite website image-to-code skill for Codex. For visually important web tasks, it must first generate the design image(s) itself, ... | [`skills/image-to-code/`](./image-to-code/SKILL.md) |
| 60 | **`implement`** | "Implement a piece of work based on a spec or set of tickets." | [`skills/implement/`](./implement/SKILL.md) |
| 61 | **`implement-spec`** | "Implement a specification in code." | [`skills/implement-spec/`](./implement-spec/SKILL.md) |
| 62 | **`improve-codebase-architecture`** | Scan a codebase for deepening opportunities, present them as a visual HTML report, then grill through whichever one you pick. | [`skills/improve-codebase-architecture/`](./improve-codebase-architecture/SKILL.md) |
| 63 | **`javascript-mastery`** | ﻿--- | [`skills/javascript-mastery/`](./javascript-mastery/SKILL.md) |
| 64 | **`karpathy-guidelines`** | "Enforce Andrej Karpathy's 4 core coding principles: Think Before Coding, Simplicity First, Surgical Changes, and Goal-Driven Exec... | [`skills/karpathy-guidelines/`](./karpathy-guidelines/SKILL.md) |
| 65 | **`lavish`** | Turn complex or visual agent responses into rich, reviewable HTML artifacts the user can annotate and send feedback on, using the ... | [`skills/lavish/`](./lavish/SKILL.md) |
| 66 | **`lfg`** | "Run the full autonomous shipping pipeline end-to-end, hands-off with no check-ins. Use only when the user explicitly asks to buil... | [`skills/lfg/`](./lfg/SKILL.md) |
| 67 | **`loop-me`** | Grill me about specs for the workflows I want to build, within this workspace. | [`skills/loop-me/`](./loop-me/SKILL.md) |
| 68 | **`mermaid-diagrams`** | ﻿--- | [`skills/mermaid-diagrams/`](./mermaid-diagrams/SKILL.md) |
| 69 | **`migrate-to-shoehorn`** | Migrate test files from `as` type assertions to @total-typescript/shoehorn. Use when user mentions shoehorn, wants to replace `as`... | [`skills/migrate-to-shoehorn/`](./migrate-to-shoehorn/SKILL.md) |
| 70 | **`ml-best-practices`** | \| | [`skills/ml-best-practices/`](./ml-best-practices/SKILL.md) |
| 71 | **`nextjs-best-practices`** | ﻿--- | [`skills/nextjs-best-practices/`](./nextjs-best-practices/SKILL.md) |
| 72 | **`open-design-pro`** | "Master design engineering and anti-slop frontend engine. Fuses DESIGN.md token contracts (OKLCH, typography, elevation), Taste-dr... | [`skills/open-design-pro/`](./open-design-pro/SKILL.md) |
| 73 | **`pdf-processing-pro`** | ﻿--- | [`skills/pdf-processing-pro/`](./pdf-processing-pro/SKILL.md) |
| 74 | **`performance`** | ﻿--- | [`skills/performance/`](./performance/SKILL.md) |
| 75 | **`personal-tool-builder`** | ﻿--- | [`skills/personal-tool-builder/`](./personal-tool-builder/SKILL.md) |
| 76 | **`playwright`** | ﻿--- | [`skills/playwright/`](./playwright/SKILL.md) |
| 77 | **`powershell-windows`** | ﻿--- | [`skills/powershell-windows/`](./powershell-windows/SKILL.md) |
| 78 | **`prd`** | "Generate a Product Requirements Document (PRD) for a new feature. Use when planning a feature, starting a new project, or when as... | [`skills/prd/`](./prd/SKILL.md) |
| 79 | **`prototype`** | Build a throwaway prototype to answer a design question. Use when the user wants to sanity-check whether a state model or logic fe... | [`skills/prototype/`](./prototype/SKILL.md) |
| 80 | **`python-mastery`** | "Master modern Python 3.12+ engineering and architecture. Fuses idiomatic Python patterns, high-performance asyncio concurrency, P... | [`skills/python-mastery/`](./python-mastery/SKILL.md) |
| 81 | **`python-patterns`** | ﻿--- | [`skills/python-patterns/`](./python-patterns/SKILL.md) |
| 82 | **`python-testing-patterns`** | Python testing strategies using pytest, TDD methodology, fixtures, mocking, parametrization, and coverage requirements. Use when w... | [`skills/python-testing-patterns/`](./python-testing-patterns/SKILL.md) |
| 83 | **`ralph`** | "Convert PRDs to prd.json format for the Ralph autonomous agent system. Use when you have an existing PRD and need to convert it t... | [`skills/ralph/`](./ralph/SKILL.md) |
| 84 | **`react-best-practices`** | ﻿--- | [`skills/react-best-practices/`](./react-best-practices/SKILL.md) |
| 85 | **`react-patterns`** | ﻿--- | [`skills/react-patterns/`](./react-patterns/SKILL.md) |
| 86 | **`react-ui-patterns`** | ﻿--- | [`skills/react-ui-patterns/`](./react-ui-patterns/SKILL.md) |
| 87 | **`research`** | Investigate a question against high-trust primary sources and capture the findings as a Markdown file in the repo. Use when the us... | [`skills/research/`](./research/SKILL.md) |
| 88 | **`resolving-merge-conflicts`** | "Use when you need to resolve an in-progress git merge/rebase conflict." | [`skills/resolving-merge-conflicts/`](./resolving-merge-conflicts/SKILL.md) |
| 89 | **`retro`** | "Conduct a retrospective on a coding session." | [`skills/retro/`](./retro/SKILL.md) |
| 90 | **`rust-patterns`** | Idiomatic Rust patterns, ownership, error handling, traits, concurrency, and best practices for building safe, performant applicat... | [`skills/rust-patterns/`](./rust-patterns/SKILL.md) |
| 91 | **`rust-testing`** | Rust testing patterns including unit tests, integration tests, async testing, property-based testing, mocking, and coverage. Follo... | [`skills/rust-testing/`](./rust-testing/SKILL.md) |
| 92 | **`scaffold-exercises`** | Create exercise directory structures with sections, problems, solutions, and explainers that pass linting. Use when user wants to ... | [`skills/scaffold-exercises/`](./scaffold-exercises/SKILL.md) |
| 93 | **`screenshot-feature-extractor`** | ﻿--- | [`skills/screenshot-feature-extractor/`](./screenshot-feature-extractor/SKILL.md) |
| 94 | **`senior-architect`** | ﻿--- | [`skills/senior-architect/`](./senior-architect/SKILL.md) |
| 95 | **`senior-backend`** | ﻿--- | [`skills/senior-backend/`](./senior-backend/SKILL.md) |
| 96 | **`senior-data-scientist`** | ﻿--- | [`skills/senior-data-scientist/`](./senior-data-scientist/SKILL.md) |
| 97 | **`senior-devops`** | ﻿--- | [`skills/senior-devops/`](./senior-devops/SKILL.md) |
| 98 | **`senior-frontend`** | ﻿--- | [`skills/senior-frontend/`](./senior-frontend/SKILL.md) |
| 99 | **`senior-fullstack`** | ﻿--- | [`skills/senior-fullstack/`](./senior-fullstack/SKILL.md) |
| 100 | **`senior-ml-engineer`** | ﻿--- | [`skills/senior-ml-engineer/`](./senior-ml-engineer/SKILL.md) |
| 101 | **`senior-prompt-engineer`** | ﻿--- | [`skills/senior-prompt-engineer/`](./senior-prompt-engineer/SKILL.md) |
| 102 | **`senior-qa`** | ﻿--- | [`skills/senior-qa/`](./senior-qa/SKILL.md) |
| 103 | **`senior-security`** | ﻿--- | [`skills/senior-security/`](./senior-security/SKILL.md) |
| 104 | **`seo`** | ﻿--- | [`skills/seo/`](./seo/SKILL.md) |
| 105 | **`setup-matt-pocock-skills`** | "Configure this repo for the engineering skills: set up its issue tracker, triage label vocabulary, and domain doc layout. Run onc... | [`skills/setup-matt-pocock-skills/`](./setup-matt-pocock-skills/SKILL.md) |
| 106 | **`setup-pre-commit`** | Set up Husky pre-commit hooks with lint-staged (Prettier), type checking, and tests in the current repo. Use when user wants to ad... | [`skills/setup-pre-commit/`](./setup-pre-commit/SKILL.md) |
| 107 | **`setup-ts-deep-modules`** | Wire dependency-cruiser into a TypeScript repo so each package is a deep module, with implementation hidden in subfolders and reac... | [`skills/setup-ts-deep-modules/`](./setup-ts-deep-modules/SKILL.md) |
| 108 | **`skill-repair`** | \| | [`skills/skill-repair/`](./skill-repair/SKILL.md) |
| 109 | **`systematic-debugger`** | "Master systematic debugging and error diagnosis engine. Fuses first-principles root cause analysis, reproducible test creation (T... | [`skills/systematic-debugger/`](./systematic-debugger/SKILL.md) |
| 110 | **`taste-skill`** | Anti-slop frontend skill for landing pages, portfolios, and redesigns. The agent reads the brief, infers the right design directio... | [`skills/taste-skill/`](./taste-skill/SKILL.md) |
| 111 | **`tdd`** | Test-driven development. Use when the user wants to build features or fix bugs test-first, mentions "red-green-refactor", or wants... | [`skills/tdd/`](./tdd/SKILL.md) |
| 112 | **`tdd-workflow`** | Use this skill when writing new features, fixing bugs, or refactoring code. Enforces test-driven development with 80%+ coverage in... | [`skills/tdd-workflow/`](./tdd-workflow/SKILL.md) |
| 113 | **`teach`** | Teach the user a new skill or concept, within this workspace. | [`skills/teach/`](./teach/SKILL.md) |
| 114 | **`to-questionnaire`** | Turn a decision you can't fully answer into a questionnaire for someone else to fill in. | [`skills/to-questionnaire/`](./to-questionnaire/SKILL.md) |
| 115 | **`to-spec`** | "Turn the current conversation into a spec and publish it to the project issue tracker: no interview, just synthesis of what you'v... | [`skills/to-spec/`](./to-spec/SKILL.md) |
| 116 | **`to-tickets`** | Break a plan, spec, or the current conversation into a set of tracer-bullet tickets, each declaring its blocking edges, published ... | [`skills/to-tickets/`](./to-tickets/SKILL.md) |
| 117 | **`triage`** | Move issues and external PRs through a state machine of triage roles, categorise, verify, grill if needed, and write agent-ready b... | [`skills/triage/`](./triage/SKILL.md) |
| 118 | **`typescript-expert`** | ﻿--- | [`skills/typescript-expert/`](./typescript-expert/SKILL.md) |
| 119 | **`ui-ux-pro-max`** | ﻿--- | [`skills/ui-ux-pro-max/`](./ui-ux-pro-max/SKILL.md) |
| 120 | **`video-downloader`** | ﻿--- | [`skills/video-downloader/`](./video-downloader/SKILL.md) |
| 121 | **`wait-what`** | "Stop. That last message did not land: re-pitch it." | [`skills/wait-what/`](./wait-what/SKILL.md) |
| 122 | **`wayfinder`** | Plan a huge chunk of work (more than one agent session can hold) as a shared map of decision tickets on your issue tracker, and re... | [`skills/wayfinder/`](./wayfinder/SKILL.md) |
| 123 | **`web-design-guidelines`** | Review and enforce Vercel Web Interface Guidelines compliance. Checks UI code for hit targets, keyboard accessibility, focus state... | [`skills/web-design-guidelines/`](./web-design-guidelines/SKILL.md) |
| 124 | **`web-quality-audit`** | ﻿--- | [`skills/web-quality-audit/`](./web-quality-audit/SKILL.md) |
| 125 | **`web-to-markdown`** | ﻿--- | [`skills/web-to-markdown/`](./web-to-markdown/SKILL.md) |
| 126 | **`windows-desktop-e2e`** | E2E testing for Windows native desktop apps (WPF, WinForms, Win32/MFC, Qt) using pywinauto and Windows UI Automation. Use when wri... | [`skills/windows-desktop-e2e/`](./windows-desktop-e2e/SKILL.md) |
| 127 | **`wizard`** | Generate an interactive bash wizard that walks a human through steps only they can perform. Use when provisioning infrastructure, ... | [`skills/wizard/`](./wizard/SKILL.md) |
| 128 | **`writing-beats`** | Writing, exploit; assemble raw material into a journey of beats, grounding each term before a beat leans on it. | [`skills/writing-beats/`](./writing-beats/SKILL.md) |
| 129 | **`writing-for-agents`** | Writing documents for agents. Use when creating or editing skills, or modifying AGENTS.md or CLAUDE.md. | [`skills/writing-for-agents/`](./writing-for-agents/SKILL.md) |
| 130 | **`writing-fragments`** | "Writing, explore: mine raw fragments, no structure yet." | [`skills/writing-fragments/`](./writing-fragments/SKILL.md) |
| 131 | **`writing-shape`** | "Writing, exploit: shape raw material into an article, paragraph by paragraph." | [`skills/writing-shape/`](./writing-shape/SKILL.md) |
| 132 | **`xlsx`** | ﻿--- | [`skills/xlsx/`](./xlsx/SKILL.md) |

---

## 🛠 Adding Custom Skills
To add a new skill to the framework:
1. Create a directory: `skills/<your-skill-name>/`
2. Create `SKILL.md` with standard YAML frontmatter (`name:`, `description:`, `user-invocable:`).
3. Specify domain rules, anti-patterns, checklists, and code examples.
