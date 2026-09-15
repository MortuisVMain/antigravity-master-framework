# 🧰 Каталог Специализированных Навыков Агента (132 Навыка)

> **Версия:** 2.6 Ultra-Optimized (Zero Context Limits)  
> **Статус:** 132/132 навыков активны без превышения контекстного бюджета  
> **Лицензия:** GNU AGPL v3.0  

Все навыки используют архитектуру **Progressive Disclosure** (Прогрессивное Раскрытие). Описания оптимизированы по стандарту Карпати (1–2 предложения, 90–140 символов), что исключает превышение лимитов промпта в IDE.

---

## 🗂 Навигация по Категориям

### 🎯 Alignment, Grilling & Strategic POV

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`grill-me`** | A relentless interview to sharpen a plan or design. | [`SKILL.md`](./grill-me/SKILL.md) |
| **`grill-with-docs`** | A relentless interview to sharpen a plan or design, which also creates docs (ADR's and glossary) as we go. | [`SKILL.md`](./grill-with-docs/SKILL.md) |
| **`grilling`** | Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'grill' trigger phrases. | [`SKILL.md`](./grilling/SKILL.md) |
| **`ce-strategy`** | Create or update STRATEGY.md for product vision, roadmaps, and high-level strategic alignment. | [`SKILL.md`](./ce-strategy/SKILL.md) |
| **`ce-brainstorm`** | Explore vague ideas into requirements, design alternatives, tradeoffs, and a unified plan before implementation. | [`SKILL.md`](./ce-brainstorm/SKILL.md) |
| **`ce-pov`** | Provide a decisive, grounded point of view or graded verdict on technology adoption, architecture choices, or documents. | [`SKILL.md`](./ce-pov/SKILL.md) |
| **`ce-ideate`** | Generate and evaluate grounded product ideas, creative directions, and architectural improvements before planning. | [`SKILL.md`](./ce-ideate/SKILL.md) |
| **`critic-triad`** | Global 3-Critic Supreme Council: Red-Team Skeptic, Karpathy Pragmatist, and Domain Specialist for any code, plan, or decision. | [`SKILL.md`](./critic-triad/SKILL.md) |

### 🏛 Architecture & Codebase Design

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`improve-codebase-architecture`** | Scan a codebase for deepening opportunities, present them as a visual HTML report, then grill through whichever one you pick. | [`SKILL.md`](./improve-codebase-architecture/SKILL.md) |
| **`codebase-design`** | Philosophy and shared vocabulary for designing deep modules with narrow interfaces and rich functionality. | [`SKILL.md`](./codebase-design/SKILL.md) |
| **`domain-modeling`** | Build and sharpen a project's domain model. Use when discussing codebase terminology, writing or editing a CONTEXT.md, or recording or editing an ADR. | [`SKILL.md`](./domain-modeling/SKILL.md) |
| **`architecture-patterns`** | Design, implement, and refactor Ports & Adapters (Hexagonal) architecture with clean domain boundaries and testable orchestration. | [`SKILL.md`](./architecture-patterns/SKILL.md) |
| **`architecture-decision-records`** | Capture architectural decisions made during development as structured ADRs in docs/adr/ with context and trade-offs. | [`SKILL.md`](./architecture-decision-records/SKILL.md) |
| **`setup-ts-deep-modules`** | Configure dependency-cruiser in TypeScript repositories to enforce deep module boundaries and narrow public interfaces. | [`SKILL.md`](./setup-ts-deep-modules/SKILL.md) |
| **`senior-architect`** | Software architecture, system design patterns, tech stack evaluation, and dependency analysis across frontend and backend. | [`SKILL.md`](./senior-architect/SKILL.md) |

### 📋 Planning, Specs & Decomposition

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`wayfinder`** | Decompose massive tasks into an issue-tracker dependency graph of decision tickets for step-by-step resolution. | [`SKILL.md`](./wayfinder/SKILL.md) |
| **`to-spec`** | Turn the current conversation into a spec and publish it to the project issue tracker: no interview, just synthesis of what you've already discussed. | [`SKILL.md`](./to-spec/SKILL.md) |
| **`to-tickets`** | Decompose plans or specs into tracer-bullet tickets with explicit dependency blocking edges for step-by-step progress. | [`SKILL.md`](./to-tickets/SKILL.md) |
| **`prd`** | Generate comprehensive Product Requirements Documents (PRD) with user stories, edge cases, and acceptance criteria. | [`SKILL.md`](./prd/SKILL.md) |
| **`ralph`** | Convert PRDs and task specs into prd.json format for autonomous agent loop execution without context rot. | [`SKILL.md`](./ralph/SKILL.md) |
| **`execution-planner`** | Engineering execution planning: /grill-me requirements grilling, trade-off evaluation, Mermaid diagrams, and exit code 0 gates. | [`SKILL.md`](./execution-planner/SKILL.md) |
| **`to-questionnaire`** | Turn a decision you can't fully answer into a questionnaire for someone else to fill in. | [`SKILL.md`](./to-questionnaire/SKILL.md) |

### 🧹 Clean Code, Review & Karpathy Simplicity

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`karpathy-guidelines`** | Enforce Andrej Karpathy's 4 principles: Think Before Coding, Simplicity First (200->50), Surgical Changes, and Goal-Driven. | [`SKILL.md`](./karpathy-guidelines/SKILL.md) |
| **`clean-code`** | Baseline coding conventions: SOLID, DRY, clear naming, readability, immutability, and modular separation of concerns. | [`SKILL.md`](./clean-code/SKILL.md) |
| **`code-review`** | Parallel standards and spec review of changes since a git commit, branch, or tag, reporting findings side by side. | [`SKILL.md`](./code-review/SKILL.md) |
| **`ce-code-review`** | Structured code review for bugs, regressions, test coverage, and standards before creating pull requests. | [`SKILL.md`](./ce-code-review/SKILL.md) |
| **`code-reviewer-pro`** | Master code review engine: Clean Code, Karpathy 200->50 compression, OWASP security audit, and silent failure hunting. | [`SKILL.md`](./code-reviewer-pro/SKILL.md) |
| **`ce-resolve-pr-feedback`** | Address and resolve review feedback comments left on a pull request systematically. | [`SKILL.md`](./ce-resolve-pr-feedback/SKILL.md) |
| **`ce-polish`** | Polish and refine user-facing features through interactive browser inspection and styling tweaks. | [`SKILL.md`](./ce-polish/SKILL.md) |
| **`systematic-debugger`** | Systematic debugging: first-principles root cause analysis, reproducible failing tests (RED), and surgical fixes (GREEN). | [`SKILL.md`](./systematic-debugger/SKILL.md) |
| **`diagnosing-bugs`** | Diagnosis loop for hard bugs and performance regressions. Use when the user says "diagnose"/"debug this", or reports something broken/throwing/failing/slow. | [`SKILL.md`](./diagnosing-bugs/SKILL.md) |
| **`triage`** | Move issues and external PRs through a state machine of triage roles, categorise, verify, grill if needed, and write agent-ready briefs. | [`SKILL.md`](./triage/SKILL.md) |
| **`retro`** | Conduct a retrospective on a coding session. | [`SKILL.md`](./retro/SKILL.md) |

### ⚡ Execution & Autonomous Workflows

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`ce-work`** | Execute an approved implementation plan, spec, or concrete task end-to-end with thorough local verification. | [`SKILL.md`](./ce-work/SKILL.md) |
| **`lfg`** | Run autonomous shipping pipeline end-to-end: build, verify, commit, push, and open a pull request without stopping. | [`SKILL.md`](./lfg/SKILL.md) |
| **`ce-commit-push-pr`** | Stage changes, create semantic git commits, push branch, and open structured pull requests. | [`SKILL.md`](./ce-commit-push-pr/SKILL.md) |
| **`implement`** | Implement a piece of work based on a spec or set of tickets. | [`SKILL.md`](./implement/SKILL.md) |
| **`implement-spec`** | Implement a specification in code. | [`SKILL.md`](./implement-spec/SKILL.md) |
| **`ce-worktree`** | Set up isolated git worktrees — create a new branch for fresh work, or attach a worktree to an existing branch, PR, or commit. Use when starting isolated work or isolating an existing ref. | [`SKILL.md`](./ce-worktree/SKILL.md) |
| **`claude-handoff`** | Hand the current conversation off to a fresh background agent that picks up the work immediately. | [`SKILL.md`](./claude-handoff/SKILL.md) |
| **`handoff`** | Compact the current conversation into a handoff document for another agent to pick up. | [`SKILL.md`](./handoff/SKILL.md) |
| **`ce-handoff`** | Create structured session handoff documents to transfer work and context to a new agent session. | [`SKILL.md`](./ce-handoff/SKILL.md) |
| **`resolving-merge-conflicts`** | Use when you need to resolve an in-progress git merge/rebase conflict. | [`SKILL.md`](./resolving-merge-conflicts/SKILL.md) |

### 🧪 Testing, QA & Verification

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`tdd`** | Test-driven development. Use when the user wants to build features or fix bugs test-first, mentions "red-green-refactor", or wants integration tests. | [`SKILL.md`](./tdd/SKILL.md) |
| **`tdd-workflow`** | Enforce Test-Driven Development (TDD) red-green-refactor loop with 80%+ unit, integration, and E2E coverage. | [`SKILL.md`](./tdd-workflow/SKILL.md) |
| **`python-testing-patterns`** | Python testing strategies using pytest, TDD methodology, fixtures, mocking, parametrization, and coverage requirements. Use when writing pytest tests — fixtures, mocks, parametrization, or coverage. | [`SKILL.md`](./python-testing-patterns/SKILL.md) |
| **`rust-testing`** | Rust testing patterns: unit tests, integration suites, property-based tests, mocks, and code coverage following TDD. | [`SKILL.md`](./rust-testing/SKILL.md) |
| **`cpp-testing`** | Use only when writing/updating/fixing C++ tests, configuring GoogleTest/CTest, diagnosing failing or flaky tests, or adding coverage/sanitizers. | [`SKILL.md`](./cpp-testing/SKILL.md) |
| **`csharp-testing`** | C# and .NET testing: xUnit, FluentAssertions, integration tests, mocks, and test organization best practices. | [`SKILL.md`](./csharp-testing/SKILL.md) |
| **`ce-test-browser`** | Execute Playwright and browser test suites for pages affected by current branch changes or pull requests. | [`SKILL.md`](./ce-test-browser/SKILL.md) |
| **`playwright`** | End-to-end browser automation, UI testing, form interaction, screenshot capture, and visual validation via Playwright. | [`SKILL.md`](./playwright/SKILL.md) |
| **`windows-desktop-e2e`** | End-to-end UI automation testing for Windows native desktop apps (WPF, WinForms, Win32, Qt) via pywinauto. | [`SKILL.md`](./windows-desktop-e2e/SKILL.md) |
| **`senior-qa`** | Quality assurance, automated test suite design, E2E testing strategies, coverage analysis, and quality metrics. | [`SKILL.md`](./senior-qa/SKILL.md) |

### 🎨 Frontend, UI/UX & Motion Engineering

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`open-design-pro`** | Design engineering engine: DESIGN.md token contracts, OKLCH, tactile UI, 21st.dev components, and Playwright verification. | [`SKILL.md`](./open-design-pro/SKILL.md) |
| **`taste-skill`** | Anti-slop frontend craftsmanship: infer aesthetic direction, typography, tactile details, and eliminate generic AI templates. | [`SKILL.md`](./taste-skill/SKILL.md) |
| **`design-to-code`** | Convert Figma designs into production-ready React, TypeScript, and Tailwind CSS components with high visual fidelity. | [`SKILL.md`](./design-to-code/SKILL.md) |
| **`figma-implement-design`** | Translate Figma designs, nodes, and component specs into production-ready frontend code with pixel-perfect fidelity. | [`SKILL.md`](./figma-implement-design/SKILL.md) |
| **`ui-ux-pro-max`** | UI/UX design intelligence: 50+ styles, 21 palettes, typography, responsive layouts, components (React, Tailwind, shadcn). | [`SKILL.md`](./ui-ux-pro-max/SKILL.md) |
| **`web-design-guidelines`** | Audit and enforce Vercel Web Interface Guidelines: hit targets >=48px, keyboard focus, mobile inputs >=16px, and loading states. | [`SKILL.md`](./web-design-guidelines/SKILL.md) |
| **`core-web-vitals`** | Optimize Core Web Vitals (LCP, INP, CLS): asset loading, layout shifts, rendering performance, and user responsiveness. | [`SKILL.md`](./core-web-vitals/SKILL.md) |
| **`accessibility`** | Audit and improve web accessibility following WCAG 2.1 AA guidelines: keyboard navigation, ARIA, and screen readers. | [`SKILL.md`](./accessibility/SKILL.md) |
| **`react-patterns`** | Modern React patterns and principles. Hooks, composition, performance, TypeScript best practices. | [`SKILL.md`](./react-patterns/SKILL.md) |
| **`nextjs-best-practices`** | Next.js App Router principles. Server Components, data fetching, routing patterns. | [`SKILL.md`](./nextjs-best-practices/SKILL.md) |
| **`react-best-practices`** | React and Next.js performance optimization guidelines from Vercel: Server Components, waterfalls, and re-renders. | [`SKILL.md`](./react-best-practices/SKILL.md) |
| **`react-ui-patterns`** | Modern React UI patterns for loading states, error handling, and data fetching. Use when building UI components, handling async data, or managing UI states. | [`SKILL.md`](./react-ui-patterns/SKILL.md) |
| **`senior-frontend`** | Modern performant frontend engineering: React, Next.js, TypeScript, Tailwind CSS, component architecture, and bundle tuning. | [`SKILL.md`](./senior-frontend/SKILL.md) |

### 💻 Polyglot Engineering & Systems

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`python-mastery`** | Modern Python 3.12+ engineering: asyncio concurrency, Pydantic V2 validation, clean architecture, and uv dependency workflows. | [`SKILL.md`](./python-mastery/SKILL.md) |
| **`fastapi-pro`** | Build high-performance async APIs with FastAPI, SQLAlchemy 2.0, and Pydantic V2. Master microservices, WebSockets, and modern Python async patterns. | [`SKILL.md`](./fastapi-pro/SKILL.md) |
| **`django-pro`** | Master Django 5.x with async views, DRF, Celery, and Django Channels. Build scalable web applications with proper architecture, testing, and deployment. | [`SKILL.md`](./django-pro/SKILL.md) |
| **`python-patterns`** | Python development principles and decision-making. Framework selection, async patterns, type hints, project structure. Teaches thinking, not copying. | [`SKILL.md`](./python-patterns/SKILL.md) |
| **`typescript-expert`** | TypeScript and JavaScript expert: type-level programming, performance optimization, monorepo architecture, and debugging. | [`SKILL.md`](./typescript-expert/SKILL.md) |
| **`javascript-mastery`** | Deep JavaScript reference: closures, event loop, async/await, prototypes, functional patterns, and performance tuning. | [`SKILL.md`](./javascript-mastery/SKILL.md) |
| **`rust-patterns`** | Idiomatic Rust patterns: ownership, lifetimes, error handling, traits, concurrency, and zero-cost abstractions. | [`SKILL.md`](./rust-patterns/SKILL.md) |
| **`cpp-pro`** | C++ coding standards based on the C++ Core Guidelines (isocpp.github.io). Use when writing, reviewing, or refactoring C++ code to enforce modern, safe, and idiomatic practices. | [`SKILL.md`](./cpp-pro/SKILL.md) |
| **`bash-pro`** | Master of defensive Bash scripting for production automation, CI/CD pipelines, and system utilities. Expert in safe, portable, and testable shell scripts. | [`SKILL.md`](./bash-pro/SKILL.md) |
| **`powershell-windows`** | PowerShell Windows patterns. Critical pitfalls, operator syntax, error handling. | [`SKILL.md`](./powershell-windows/SKILL.md) |
| **`senior-backend`** | Scalable backend architecture, API scaffolding, database optimization, auth/security, and performance tuning. | [`SKILL.md`](./senior-backend/SKILL.md) |
| **`senior-fullstack`** | Fullstack development: React, Next.js, Node.js, GraphQL, PostgreSQL, scalable architecture, and development workflows. | [`SKILL.md`](./senior-fullstack/SKILL.md) |

### 🚢 DevOps, Security, Data & Tool Building

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`devops-and-cloud`** | Docker containerization, multi-stage builds, docker-compose orchestration, GitHub Actions CI/CD pipelines, and cloud deployments. | [`SKILL.md`](./devops-and-cloud/SKILL.md) |
| **`docker-expert`** | Docker containerization: multi-stage builds, image size reduction, security hardening, and Docker Compose orchestration. | [`SKILL.md`](./docker-expert/SKILL.md) |
| **`senior-devops`** | DevOps and cloud infrastructure: CI/CD pipelines, Docker, Kubernetes, Terraform/IaC, deployment automation, and monitoring. | [`SKILL.md`](./senior-devops/SKILL.md) |
| **`senior-security`** | Application security, threat modeling, penetration testing, cryptography, boundary validation, and security auditing. | [`SKILL.md`](./senior-security/SKILL.md) |
| **`git-guardrails-claude-code`** | Configure safety hooks to block dangerous git operations (force push, hard reset, uncommitted clean) before execution. | [`SKILL.md`](./git-guardrails-claude-code/SKILL.md) |
| **`setup-pre-commit`** | Set up Husky pre-commit hooks with lint-staged, Prettier, TypeScript checks, and test runners in the repository. | [`SKILL.md`](./setup-pre-commit/SKILL.md) |
| **`setup-matt-pocock-skills`** | Initialize repository settings, issue tracker labels, and domain doc directories for engineering skills. | [`SKILL.md`](./setup-matt-pocock-skills/SKILL.md) |
| **`personal-tool-builder`** | Rapid prototyping and building of custom personal tools, CLI utilities, and local-first scripts to solve developer needs. | [`SKILL.md`](./personal-tool-builder/SKILL.md) |
| **`benchmark-optimization-loop`** | Use when the user asks to make something faster, try many variants, run recursive optimization, benchmark latency/throughput/cost, or choose the best implementation by repeated measured tests. | [`SKILL.md`](./benchmark-optimization-loop/SKILL.md) |
| **`ce-optimize`** | Targeted optimization loop: measure baseline, profile bottlenecks, score variants, and verify performance gains. | [`SKILL.md`](./ce-optimize/SKILL.md) |
| **`database-schema-designer`** | Design robust, scalable relational and NoSQL schemas: normalization, indexing strategy, foreign keys, and constraints. | [`SKILL.md`](./database-schema-designer/SKILL.md) |
| **`database-migrations`** | Database migrations: zero-downtime schema updates, data migrations, rollback safety, and ORM best practices. | [`SKILL.md`](./database-migrations/SKILL.md) |
| **`senior-data-scientist`** | Statistical modeling, experimentation, A/B testing, causal inference, and data analysis in Python and SQL. | [`SKILL.md`](./senior-data-scientist/SKILL.md) |
| **`senior-ml-engineer`** | Production ML engineering, MLOps, model deployment, monitoring, feature stores, and LLM/RAG integration. | [`SKILL.md`](./senior-ml-engineer/SKILL.md) |
| **`senior-prompt-engineer`** | World-class prompt engineering, few-shot patterns, structured outputs, evaluations, and agent system architectures. | [`SKILL.md`](./senior-prompt-engineer/SKILL.md) |
| **`ml-best-practices`** | Best practices for machine learning, model training, evaluation, classification, regression, clustering, and data analysis. | [`SKILL.md`](./ml-best-practices/SKILL.md) |

### 📚 Pedagogy, Documents, Research & Media

| Навык | Описание (Trigger & Capabilities) | Файл |
| :--- | :--- | :--- |
| **`teach`** | Teach the user a new skill or concept, within this workspace. | [`SKILL.md`](./teach/SKILL.md) |
| **`ask-matt`** | Ask which skill or flow fits your situation. A router over the skills in this repo. | [`SKILL.md`](./ask-matt/SKILL.md) |
| **`ce-explain`** | Create a durable visual teaching artifact and deep explainer for complex changes, architecture, or concepts. | [`SKILL.md`](./ce-explain/SKILL.md) |
| **`research`** | Investigate technical questions against primary documentation and sources, capturing structured findings in markdown. | [`SKILL.md`](./research/SKILL.md) |
| **`web-to-markdown`** | Fetch and convert web pages into clean Markdown using headless browser rendering (web2md CLI). | [`SKILL.md`](./web-to-markdown/SKILL.md) |
| **`writing-for-agents`** | Writing documents for agents. Use when creating or editing skills, or modifying AGENTS.md or CLAUDE.md. | [`SKILL.md`](./writing-for-agents/SKILL.md) |
| **`writing-beats`** | Writing, exploit; assemble raw material into a journey of beats, grounding each term before a beat leans on it. | [`SKILL.md`](./writing-beats/SKILL.md) |
| **`writing-fragments`** | Writing, explore: mine raw fragments, no structure yet. | [`SKILL.md`](./writing-fragments/SKILL.md) |
| **`writing-shape`** | Writing, exploit: shape raw material into an article, paragraph by paragraph. | [`SKILL.md`](./writing-shape/SKILL.md) |
| **`scaffold-exercises`** | Generate structured code exercise templates with problems, solutions, explainers, and passing linter suites. | [`SKILL.md`](./scaffold-exercises/SKILL.md) |
| **`migrate-to-shoehorn`** | Migrate test files from `as` type assertions to @total-typescript/shoehorn. Use when user mentions shoehorn, wants to replace `as` in tests, or needs partial test data. | [`SKILL.md`](./migrate-to-shoehorn/SKILL.md) |
| **`wait-what`** | Stop. That last message did not land: re-pitch it. | [`SKILL.md`](./wait-what/SKILL.md) |
| **`prototype`** | Build a throwaway prototype to answer a design question. Use when the user wants to sanity-check whether a state model or logic feels right, or explore what a UI should look like. | [`SKILL.md`](./prototype/SKILL.md) |
| **`ce-prototype`** | Build a fast throwaway prototype to validate interaction feel, state flow, or UX before full implementation. | [`SKILL.md`](./ce-prototype/SKILL.md) |
| **`lavish`** | Transform complex responses, diffs, and architectures into rich reviewable HTML artifacts with interactive annotations. | [`SKILL.md`](./lavish/SKILL.md) |
| **`pdf-processing-pro`** | Production-grade PDF processing: text/table extraction, forms, OCR, generation, page merging, and validation. | [`SKILL.md`](./pdf-processing-pro/SKILL.md) |
| **`docx`** | Create, read, edit, and format Word documents (.docx) with tables of contents, styling, headings, and pandoc integration. | [`SKILL.md`](./docx/SKILL.md) |
| **`xlsx`** | Create, inspect, edit, format and convert spreadsheets (.xlsx, .csv, .tsv) with zero formula errors and professional tables. | [`SKILL.md`](./xlsx/SKILL.md) |
| **`file-organizer`** | Intelligently organize directories, categorize files, detect duplicates, and restructure project folder layouts. | [`SKILL.md`](./file-organizer/SKILL.md) |
| **`video-downloader`** | Downloads videos from YouTube and other platforms for offline viewing, editing, or archival. Handles various formats and quality options. | [`SKILL.md`](./video-downloader/SKILL.md) |
| **`image-enhancer`** | Improves the quality of images, especially screenshots, by enhancing resolution, sharpness, and clarity. Perfect for preparing images for presentations, documentation, or social media posts. | [`SKILL.md`](./image-enhancer/SKILL.md) |
| **`image-to-code`** | Convert UI design images, mockups, and section screenshots into production-ready web frontend code with high fidelity. | [`SKILL.md`](./image-to-code/SKILL.md) |
| **`screenshot-feature-extractor`** | Analyze product screenshots and competitor UIs to extract feature lists and generate actionable development tasks. | [`SKILL.md`](./screenshot-feature-extractor/SKILL.md) |
| **`web-quality-audit`** | Comprehensive web quality audit covering performance, accessibility, SEO, Core Web Vitals, and best practices. | [`SKILL.md`](./web-quality-audit/SKILL.md) |
| **`seo`** | Technical SEO optimization: meta tags, Open Graph, structured JSON-LD data, sitemaps, and search engine visibility. | [`SKILL.md`](./seo/SKILL.md) |
| **`blender-motion-state-inspection`** | Use this skill when inspecting Blender characters, rigs, poses, animation retargeting, ground contact, facing direction, or model-vs-motion alignment where screenshots alone are not enough. | [`SKILL.md`](./blender-motion-state-inspection/SKILL.md) |
| **`wizard`** | Generate an interactive bash wizard walking a human through manual tasks like secret provisioning, credentials, or cutovers. | [`SKILL.md`](./wizard/SKILL.md) |
| **`skill-repair`** | Diagnose, fix, and reinstall corrupted or failed agent skills and repair manifest.json entries. | [`SKILL.md`](./skill-repair/SKILL.md) |
| **`accidental-data-loss-prevention`** | Mandatory verification gate and user confirmation before running destructive commands (SQL DROP, rm, deleting resources). | [`SKILL.md`](./accidental-data-loss-prevention/SKILL.md) |
| **`ce-compound`** | Document non-obvious engineering solutions and platform gotchas into docs/solutions/ as durable institutional memory. | [`SKILL.md`](./ce-compound/SKILL.md) |
| **`ce-compound-refresh`** | Audit, refresh, and deduplicate repository learnings in docs/solutions/ against the current codebase state. | [`SKILL.md`](./ce-compound-refresh/SKILL.md) |
| **`game-development`** | Game development orchestrator. Routes to platform-specific skills based on project needs. | [`SKILL.md`](./game-development/SKILL.md) |
| **`mermaid-diagrams`** | Create, visualize and document architecture diagrams, sequence flows, ERDs, class models and flowcharts using Mermaid syntax. | [`SKILL.md`](./mermaid-diagrams/SKILL.md) |

### 📦 Дополнительные Инструменты

| Навык | Описание | Файл |
| :--- | :--- | :--- |
| **`api-platform-builder`** | Master REST API design, FastAPI/Flask microservices, OpenAPI contracts, Pydantic V2 validation, JWT auth, and API stress testing. | [`SKILL.md`](./api-platform-builder/SKILL.md) |
| **`ce-doc-review`** | Review requirements, plans, or specs with role-specific lenses. Use when the user wants to improve an existing planning document. | [`SKILL.md`](./ce-doc-review/SKILL.md) |
| **`ce-setup`** | Check Compound Engineering health and repo-local config. | [`SKILL.md`](./ce-setup/SKILL.md) |
| **`loop-me`** | Grill me about specs for the workflows I want to build, within this workspace. | [`SKILL.md`](./loop-me/SKILL.md) |
| **`performance`** | Web performance optimization: bundle size reduction, asset caching, lazy loading, and runtime speed improvements. | [`SKILL.md`](./performance/SKILL.md) |

---

## 📋 Полный Алфавитный Реестр Навыков

| # | Навык | Назначение | Путь |
| :-: | :--- | :--- | :--- |
| 1 | **`accessibility`** | Audit and improve web accessibility following WCAG 2.1 AA guidelines: keyboard navigation, ARIA, and screen readers. | [`accessibility/SKILL.md`](./accessibility/SKILL.md) |
| 2 | **`accidental-data-loss-prevention`** | Mandatory verification gate and user confirmation before running destructive commands (SQL DROP, rm, deleting resources). | [`accidental-data-loss-prevention/SKILL.md`](./accidental-data-loss-prevention/SKILL.md) |
| 3 | **`api-platform-builder`** | Master REST API design, FastAPI/Flask microservices, OpenAPI contracts, Pydantic V2 validation, JWT auth, and API stress testing. | [`api-platform-builder/SKILL.md`](./api-platform-builder/SKILL.md) |
| 4 | **`architecture-decision-records`** | Capture architectural decisions made during development as structured ADRs in docs/adr/ with context and trade-offs. | [`architecture-decision-records/SKILL.md`](./architecture-decision-records/SKILL.md) |
| 5 | **`architecture-patterns`** | Design, implement, and refactor Ports & Adapters (Hexagonal) architecture with clean domain boundaries and testable orchestration. | [`architecture-patterns/SKILL.md`](./architecture-patterns/SKILL.md) |
| 6 | **`ask-matt`** | Ask which skill or flow fits your situation. A router over the skills in this repo. | [`ask-matt/SKILL.md`](./ask-matt/SKILL.md) |
| 7 | **`bash-pro`** | Master of defensive Bash scripting for production automation, CI/CD pipelines, and system utilities. Expert in safe, portable, and testable shell scripts. | [`bash-pro/SKILL.md`](./bash-pro/SKILL.md) |
| 8 | **`benchmark-optimization-loop`** | Use when the user asks to make something faster, try many variants, run recursive optimization, benchmark latency/throughput/cost, or choose the best implementation by repeated measured tests. | [`benchmark-optimization-loop/SKILL.md`](./benchmark-optimization-loop/SKILL.md) |
| 9 | **`blender-motion-state-inspection`** | Use this skill when inspecting Blender characters, rigs, poses, animation retargeting, ground contact, facing direction, or model-vs-motion alignment where screenshots alone are not enough. | [`blender-motion-state-inspection/SKILL.md`](./blender-motion-state-inspection/SKILL.md) |
| 10 | **`ce-brainstorm`** | Explore vague ideas into requirements, design alternatives, tradeoffs, and a unified plan before implementation. | [`ce-brainstorm/SKILL.md`](./ce-brainstorm/SKILL.md) |
| 11 | **`ce-code-review`** | Structured code review for bugs, regressions, test coverage, and standards before creating pull requests. | [`ce-code-review/SKILL.md`](./ce-code-review/SKILL.md) |
| 12 | **`ce-commit-push-pr`** | Stage changes, create semantic git commits, push branch, and open structured pull requests. | [`ce-commit-push-pr/SKILL.md`](./ce-commit-push-pr/SKILL.md) |
| 13 | **`ce-compound`** | Document non-obvious engineering solutions and platform gotchas into docs/solutions/ as durable institutional memory. | [`ce-compound/SKILL.md`](./ce-compound/SKILL.md) |
| 14 | **`ce-compound-refresh`** | Audit, refresh, and deduplicate repository learnings in docs/solutions/ against the current codebase state. | [`ce-compound-refresh/SKILL.md`](./ce-compound-refresh/SKILL.md) |
| 15 | **`ce-doc-review`** | Review requirements, plans, or specs with role-specific lenses. Use when the user wants to improve an existing planning document. | [`ce-doc-review/SKILL.md`](./ce-doc-review/SKILL.md) |
| 16 | **`ce-explain`** | Create a durable visual teaching artifact and deep explainer for complex changes, architecture, or concepts. | [`ce-explain/SKILL.md`](./ce-explain/SKILL.md) |
| 17 | **`ce-handoff`** | Create structured session handoff documents to transfer work and context to a new agent session. | [`ce-handoff/SKILL.md`](./ce-handoff/SKILL.md) |
| 18 | **`ce-ideate`** | Generate and evaluate grounded product ideas, creative directions, and architectural improvements before planning. | [`ce-ideate/SKILL.md`](./ce-ideate/SKILL.md) |
| 19 | **`ce-optimize`** | Targeted optimization loop: measure baseline, profile bottlenecks, score variants, and verify performance gains. | [`ce-optimize/SKILL.md`](./ce-optimize/SKILL.md) |
| 20 | **`ce-polish`** | Polish and refine user-facing features through interactive browser inspection and styling tweaks. | [`ce-polish/SKILL.md`](./ce-polish/SKILL.md) |
| 21 | **`ce-pov`** | Provide a decisive, grounded point of view or graded verdict on technology adoption, architecture choices, or documents. | [`ce-pov/SKILL.md`](./ce-pov/SKILL.md) |
| 22 | **`ce-prototype`** | Build a fast throwaway prototype to validate interaction feel, state flow, or UX before full implementation. | [`ce-prototype/SKILL.md`](./ce-prototype/SKILL.md) |
| 23 | **`ce-resolve-pr-feedback`** | Address and resolve review feedback comments left on a pull request systematically. | [`ce-resolve-pr-feedback/SKILL.md`](./ce-resolve-pr-feedback/SKILL.md) |
| 24 | **`ce-setup`** | Check Compound Engineering health and repo-local config. | [`ce-setup/SKILL.md`](./ce-setup/SKILL.md) |
| 25 | **`ce-strategy`** | Create or update STRATEGY.md for product vision, roadmaps, and high-level strategic alignment. | [`ce-strategy/SKILL.md`](./ce-strategy/SKILL.md) |
| 26 | **`ce-test-browser`** | Execute Playwright and browser test suites for pages affected by current branch changes or pull requests. | [`ce-test-browser/SKILL.md`](./ce-test-browser/SKILL.md) |
| 27 | **`ce-work`** | Execute an approved implementation plan, spec, or concrete task end-to-end with thorough local verification. | [`ce-work/SKILL.md`](./ce-work/SKILL.md) |
| 28 | **`ce-worktree`** | Set up isolated git worktrees — create a new branch for fresh work, or attach a worktree to an existing branch, PR, or commit. Use when starting isolated work or isolating an existing ref. | [`ce-worktree/SKILL.md`](./ce-worktree/SKILL.md) |
| 29 | **`claude-handoff`** | Hand the current conversation off to a fresh background agent that picks up the work immediately. | [`claude-handoff/SKILL.md`](./claude-handoff/SKILL.md) |
| 30 | **`clean-code`** | Baseline coding conventions: SOLID, DRY, clear naming, readability, immutability, and modular separation of concerns. | [`clean-code/SKILL.md`](./clean-code/SKILL.md) |
| 31 | **`code-review`** | Parallel standards and spec review of changes since a git commit, branch, or tag, reporting findings side by side. | [`code-review/SKILL.md`](./code-review/SKILL.md) |
| 32 | **`code-reviewer-pro`** | Master code review engine: Clean Code, Karpathy 200->50 compression, OWASP security audit, and silent failure hunting. | [`code-reviewer-pro/SKILL.md`](./code-reviewer-pro/SKILL.md) |
| 33 | **`codebase-design`** | Philosophy and shared vocabulary for designing deep modules with narrow interfaces and rich functionality. | [`codebase-design/SKILL.md`](./codebase-design/SKILL.md) |
| 34 | **`core-web-vitals`** | Optimize Core Web Vitals (LCP, INP, CLS): asset loading, layout shifts, rendering performance, and user responsiveness. | [`core-web-vitals/SKILL.md`](./core-web-vitals/SKILL.md) |
| 35 | **`cpp-pro`** | C++ coding standards based on the C++ Core Guidelines (isocpp.github.io). Use when writing, reviewing, or refactoring C++ code to enforce modern, safe, and idiomatic practices. | [`cpp-pro/SKILL.md`](./cpp-pro/SKILL.md) |
| 36 | **`cpp-testing`** | Use only when writing/updating/fixing C++ tests, configuring GoogleTest/CTest, diagnosing failing or flaky tests, or adding coverage/sanitizers. | [`cpp-testing/SKILL.md`](./cpp-testing/SKILL.md) |
| 37 | **`critic-triad`** | Global 3-Critic Supreme Council: Red-Team Skeptic, Karpathy Pragmatist, and Domain Specialist for any code, plan, or decision. | [`critic-triad/SKILL.md`](./critic-triad/SKILL.md) |
| 38 | **`csharp-testing`** | C# and .NET testing: xUnit, FluentAssertions, integration tests, mocks, and test organization best practices. | [`csharp-testing/SKILL.md`](./csharp-testing/SKILL.md) |
| 39 | **`database-migrations`** | Database migrations: zero-downtime schema updates, data migrations, rollback safety, and ORM best practices. | [`database-migrations/SKILL.md`](./database-migrations/SKILL.md) |
| 40 | **`database-schema-designer`** | Design robust, scalable relational and NoSQL schemas: normalization, indexing strategy, foreign keys, and constraints. | [`database-schema-designer/SKILL.md`](./database-schema-designer/SKILL.md) |
| 41 | **`design-to-code`** | Convert Figma designs into production-ready React, TypeScript, and Tailwind CSS components with high visual fidelity. | [`design-to-code/SKILL.md`](./design-to-code/SKILL.md) |
| 42 | **`devops-and-cloud`** | Docker containerization, multi-stage builds, docker-compose orchestration, GitHub Actions CI/CD pipelines, and cloud deployments. | [`devops-and-cloud/SKILL.md`](./devops-and-cloud/SKILL.md) |
| 43 | **`diagnosing-bugs`** | Diagnosis loop for hard bugs and performance regressions. Use when the user says "diagnose"/"debug this", or reports something broken/throwing/failing/slow. | [`diagnosing-bugs/SKILL.md`](./diagnosing-bugs/SKILL.md) |
| 44 | **`django-pro`** | Master Django 5.x with async views, DRF, Celery, and Django Channels. Build scalable web applications with proper architecture, testing, and deployment. | [`django-pro/SKILL.md`](./django-pro/SKILL.md) |
| 45 | **`docker-expert`** | Docker containerization: multi-stage builds, image size reduction, security hardening, and Docker Compose orchestration. | [`docker-expert/SKILL.md`](./docker-expert/SKILL.md) |
| 46 | **`docx`** | Create, read, edit, and format Word documents (.docx) with tables of contents, styling, headings, and pandoc integration. | [`docx/SKILL.md`](./docx/SKILL.md) |
| 47 | **`domain-modeling`** | Build and sharpen a project's domain model. Use when discussing codebase terminology, writing or editing a CONTEXT.md, or recording or editing an ADR. | [`domain-modeling/SKILL.md`](./domain-modeling/SKILL.md) |
| 48 | **`execution-planner`** | Engineering execution planning: /grill-me requirements grilling, trade-off evaluation, Mermaid diagrams, and exit code 0 gates. | [`execution-planner/SKILL.md`](./execution-planner/SKILL.md) |
| 49 | **`fastapi-pro`** | Build high-performance async APIs with FastAPI, SQLAlchemy 2.0, and Pydantic V2. Master microservices, WebSockets, and modern Python async patterns. | [`fastapi-pro/SKILL.md`](./fastapi-pro/SKILL.md) |
| 50 | **`figma-implement-design`** | Translate Figma designs, nodes, and component specs into production-ready frontend code with pixel-perfect fidelity. | [`figma-implement-design/SKILL.md`](./figma-implement-design/SKILL.md) |
| 51 | **`file-organizer`** | Intelligently organize directories, categorize files, detect duplicates, and restructure project folder layouts. | [`file-organizer/SKILL.md`](./file-organizer/SKILL.md) |
| 52 | **`game-development`** | Game development orchestrator. Routes to platform-specific skills based on project needs. | [`game-development/SKILL.md`](./game-development/SKILL.md) |
| 53 | **`git-guardrails-claude-code`** | Configure safety hooks to block dangerous git operations (force push, hard reset, uncommitted clean) before execution. | [`git-guardrails-claude-code/SKILL.md`](./git-guardrails-claude-code/SKILL.md) |
| 54 | **`grill-me`** | A relentless interview to sharpen a plan or design. | [`grill-me/SKILL.md`](./grill-me/SKILL.md) |
| 55 | **`grill-with-docs`** | A relentless interview to sharpen a plan or design, which also creates docs (ADR's and glossary) as we go. | [`grill-with-docs/SKILL.md`](./grill-with-docs/SKILL.md) |
| 56 | **`grilling`** | Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'grill' trigger phrases. | [`grilling/SKILL.md`](./grilling/SKILL.md) |
| 57 | **`handoff`** | Compact the current conversation into a handoff document for another agent to pick up. | [`handoff/SKILL.md`](./handoff/SKILL.md) |
| 58 | **`image-enhancer`** | Improves the quality of images, especially screenshots, by enhancing resolution, sharpness, and clarity. Perfect for preparing images for presentations, documentation, or social media posts. | [`image-enhancer/SKILL.md`](./image-enhancer/SKILL.md) |
| 59 | **`image-to-code`** | Convert UI design images, mockups, and section screenshots into production-ready web frontend code with high fidelity. | [`image-to-code/SKILL.md`](./image-to-code/SKILL.md) |
| 60 | **`implement`** | Implement a piece of work based on a spec or set of tickets. | [`implement/SKILL.md`](./implement/SKILL.md) |
| 61 | **`implement-spec`** | Implement a specification in code. | [`implement-spec/SKILL.md`](./implement-spec/SKILL.md) |
| 62 | **`improve-codebase-architecture`** | Scan a codebase for deepening opportunities, present them as a visual HTML report, then grill through whichever one you pick. | [`improve-codebase-architecture/SKILL.md`](./improve-codebase-architecture/SKILL.md) |
| 63 | **`javascript-mastery`** | Deep JavaScript reference: closures, event loop, async/await, prototypes, functional patterns, and performance tuning. | [`javascript-mastery/SKILL.md`](./javascript-mastery/SKILL.md) |
| 64 | **`karpathy-guidelines`** | Enforce Andrej Karpathy's 4 principles: Think Before Coding, Simplicity First (200->50), Surgical Changes, and Goal-Driven. | [`karpathy-guidelines/SKILL.md`](./karpathy-guidelines/SKILL.md) |
| 65 | **`lavish`** | Transform complex responses, diffs, and architectures into rich reviewable HTML artifacts with interactive annotations. | [`lavish/SKILL.md`](./lavish/SKILL.md) |
| 66 | **`lfg`** | Run autonomous shipping pipeline end-to-end: build, verify, commit, push, and open a pull request without stopping. | [`lfg/SKILL.md`](./lfg/SKILL.md) |
| 67 | **`loop-me`** | Grill me about specs for the workflows I want to build, within this workspace. | [`loop-me/SKILL.md`](./loop-me/SKILL.md) |
| 68 | **`mermaid-diagrams`** | Create, visualize and document architecture diagrams, sequence flows, ERDs, class models and flowcharts using Mermaid syntax. | [`mermaid-diagrams/SKILL.md`](./mermaid-diagrams/SKILL.md) |
| 69 | **`migrate-to-shoehorn`** | Migrate test files from `as` type assertions to @total-typescript/shoehorn. Use when user mentions shoehorn, wants to replace `as` in tests, or needs partial test data. | [`migrate-to-shoehorn/SKILL.md`](./migrate-to-shoehorn/SKILL.md) |
| 70 | **`ml-best-practices`** | Best practices for machine learning, model training, evaluation, classification, regression, clustering, and data analysis. | [`ml-best-practices/SKILL.md`](./ml-best-practices/SKILL.md) |
| 71 | **`nextjs-best-practices`** | Next.js App Router principles. Server Components, data fetching, routing patterns. | [`nextjs-best-practices/SKILL.md`](./nextjs-best-practices/SKILL.md) |
| 72 | **`open-design-pro`** | Design engineering engine: DESIGN.md token contracts, OKLCH, tactile UI, 21st.dev components, and Playwright verification. | [`open-design-pro/SKILL.md`](./open-design-pro/SKILL.md) |
| 73 | **`pdf-processing-pro`** | Production-grade PDF processing: text/table extraction, forms, OCR, generation, page merging, and validation. | [`pdf-processing-pro/SKILL.md`](./pdf-processing-pro/SKILL.md) |
| 74 | **`performance`** | Web performance optimization: bundle size reduction, asset caching, lazy loading, and runtime speed improvements. | [`performance/SKILL.md`](./performance/SKILL.md) |
| 75 | **`personal-tool-builder`** | Rapid prototyping and building of custom personal tools, CLI utilities, and local-first scripts to solve developer needs. | [`personal-tool-builder/SKILL.md`](./personal-tool-builder/SKILL.md) |
| 76 | **`playwright`** | End-to-end browser automation, UI testing, form interaction, screenshot capture, and visual validation via Playwright. | [`playwright/SKILL.md`](./playwright/SKILL.md) |
| 77 | **`powershell-windows`** | PowerShell Windows patterns. Critical pitfalls, operator syntax, error handling. | [`powershell-windows/SKILL.md`](./powershell-windows/SKILL.md) |
| 78 | **`prd`** | Generate comprehensive Product Requirements Documents (PRD) with user stories, edge cases, and acceptance criteria. | [`prd/SKILL.md`](./prd/SKILL.md) |
| 79 | **`prototype`** | Build a throwaway prototype to answer a design question. Use when the user wants to sanity-check whether a state model or logic feels right, or explore what a UI should look like. | [`prototype/SKILL.md`](./prototype/SKILL.md) |
| 80 | **`python-mastery`** | Modern Python 3.12+ engineering: asyncio concurrency, Pydantic V2 validation, clean architecture, and uv dependency workflows. | [`python-mastery/SKILL.md`](./python-mastery/SKILL.md) |
| 81 | **`python-patterns`** | Python development principles and decision-making. Framework selection, async patterns, type hints, project structure. Teaches thinking, not copying. | [`python-patterns/SKILL.md`](./python-patterns/SKILL.md) |
| 82 | **`python-testing-patterns`** | Python testing strategies using pytest, TDD methodology, fixtures, mocking, parametrization, and coverage requirements. Use when writing pytest tests — fixtures, mocks, parametrization, or coverage. | [`python-testing-patterns/SKILL.md`](./python-testing-patterns/SKILL.md) |
| 83 | **`ralph`** | Convert PRDs and task specs into prd.json format for autonomous agent loop execution without context rot. | [`ralph/SKILL.md`](./ralph/SKILL.md) |
| 84 | **`react-best-practices`** | React and Next.js performance optimization guidelines from Vercel: Server Components, waterfalls, and re-renders. | [`react-best-practices/SKILL.md`](./react-best-practices/SKILL.md) |
| 85 | **`react-patterns`** | Modern React patterns and principles. Hooks, composition, performance, TypeScript best practices. | [`react-patterns/SKILL.md`](./react-patterns/SKILL.md) |
| 86 | **`react-ui-patterns`** | Modern React UI patterns for loading states, error handling, and data fetching. Use when building UI components, handling async data, or managing UI states. | [`react-ui-patterns/SKILL.md`](./react-ui-patterns/SKILL.md) |
| 87 | **`research`** | Investigate technical questions against primary documentation and sources, capturing structured findings in markdown. | [`research/SKILL.md`](./research/SKILL.md) |
| 88 | **`resolving-merge-conflicts`** | Use when you need to resolve an in-progress git merge/rebase conflict. | [`resolving-merge-conflicts/SKILL.md`](./resolving-merge-conflicts/SKILL.md) |
| 89 | **`retro`** | Conduct a retrospective on a coding session. | [`retro/SKILL.md`](./retro/SKILL.md) |
| 90 | **`rust-patterns`** | Idiomatic Rust patterns: ownership, lifetimes, error handling, traits, concurrency, and zero-cost abstractions. | [`rust-patterns/SKILL.md`](./rust-patterns/SKILL.md) |
| 91 | **`rust-testing`** | Rust testing patterns: unit tests, integration suites, property-based tests, mocks, and code coverage following TDD. | [`rust-testing/SKILL.md`](./rust-testing/SKILL.md) |
| 92 | **`scaffold-exercises`** | Generate structured code exercise templates with problems, solutions, explainers, and passing linter suites. | [`scaffold-exercises/SKILL.md`](./scaffold-exercises/SKILL.md) |
| 93 | **`screenshot-feature-extractor`** | Analyze product screenshots and competitor UIs to extract feature lists and generate actionable development tasks. | [`screenshot-feature-extractor/SKILL.md`](./screenshot-feature-extractor/SKILL.md) |
| 94 | **`senior-architect`** | Software architecture, system design patterns, tech stack evaluation, and dependency analysis across frontend and backend. | [`senior-architect/SKILL.md`](./senior-architect/SKILL.md) |
| 95 | **`senior-backend`** | Scalable backend architecture, API scaffolding, database optimization, auth/security, and performance tuning. | [`senior-backend/SKILL.md`](./senior-backend/SKILL.md) |
| 96 | **`senior-data-scientist`** | Statistical modeling, experimentation, A/B testing, causal inference, and data analysis in Python and SQL. | [`senior-data-scientist/SKILL.md`](./senior-data-scientist/SKILL.md) |
| 97 | **`senior-devops`** | DevOps and cloud infrastructure: CI/CD pipelines, Docker, Kubernetes, Terraform/IaC, deployment automation, and monitoring. | [`senior-devops/SKILL.md`](./senior-devops/SKILL.md) |
| 98 | **`senior-frontend`** | Modern performant frontend engineering: React, Next.js, TypeScript, Tailwind CSS, component architecture, and bundle tuning. | [`senior-frontend/SKILL.md`](./senior-frontend/SKILL.md) |
| 99 | **`senior-fullstack`** | Fullstack development: React, Next.js, Node.js, GraphQL, PostgreSQL, scalable architecture, and development workflows. | [`senior-fullstack/SKILL.md`](./senior-fullstack/SKILL.md) |
| 100 | **`senior-ml-engineer`** | Production ML engineering, MLOps, model deployment, monitoring, feature stores, and LLM/RAG integration. | [`senior-ml-engineer/SKILL.md`](./senior-ml-engineer/SKILL.md) |
| 101 | **`senior-prompt-engineer`** | World-class prompt engineering, few-shot patterns, structured outputs, evaluations, and agent system architectures. | [`senior-prompt-engineer/SKILL.md`](./senior-prompt-engineer/SKILL.md) |
| 102 | **`senior-qa`** | Quality assurance, automated test suite design, E2E testing strategies, coverage analysis, and quality metrics. | [`senior-qa/SKILL.md`](./senior-qa/SKILL.md) |
| 103 | **`senior-security`** | Application security, threat modeling, penetration testing, cryptography, boundary validation, and security auditing. | [`senior-security/SKILL.md`](./senior-security/SKILL.md) |
| 104 | **`seo`** | Technical SEO optimization: meta tags, Open Graph, structured JSON-LD data, sitemaps, and search engine visibility. | [`seo/SKILL.md`](./seo/SKILL.md) |
| 105 | **`setup-matt-pocock-skills`** | Initialize repository settings, issue tracker labels, and domain doc directories for engineering skills. | [`setup-matt-pocock-skills/SKILL.md`](./setup-matt-pocock-skills/SKILL.md) |
| 106 | **`setup-pre-commit`** | Set up Husky pre-commit hooks with lint-staged, Prettier, TypeScript checks, and test runners in the repository. | [`setup-pre-commit/SKILL.md`](./setup-pre-commit/SKILL.md) |
| 107 | **`setup-ts-deep-modules`** | Configure dependency-cruiser in TypeScript repositories to enforce deep module boundaries and narrow public interfaces. | [`setup-ts-deep-modules/SKILL.md`](./setup-ts-deep-modules/SKILL.md) |
| 108 | **`skill-repair`** | Diagnose, fix, and reinstall corrupted or failed agent skills and repair manifest.json entries. | [`skill-repair/SKILL.md`](./skill-repair/SKILL.md) |
| 109 | **`systematic-debugger`** | Systematic debugging: first-principles root cause analysis, reproducible failing tests (RED), and surgical fixes (GREEN). | [`systematic-debugger/SKILL.md`](./systematic-debugger/SKILL.md) |
| 110 | **`taste-skill`** | Anti-slop frontend craftsmanship: infer aesthetic direction, typography, tactile details, and eliminate generic AI templates. | [`taste-skill/SKILL.md`](./taste-skill/SKILL.md) |
| 111 | **`tdd`** | Test-driven development. Use when the user wants to build features or fix bugs test-first, mentions "red-green-refactor", or wants integration tests. | [`tdd/SKILL.md`](./tdd/SKILL.md) |
| 112 | **`tdd-workflow`** | Enforce Test-Driven Development (TDD) red-green-refactor loop with 80%+ unit, integration, and E2E coverage. | [`tdd-workflow/SKILL.md`](./tdd-workflow/SKILL.md) |
| 113 | **`teach`** | Teach the user a new skill or concept, within this workspace. | [`teach/SKILL.md`](./teach/SKILL.md) |
| 114 | **`to-questionnaire`** | Turn a decision you can't fully answer into a questionnaire for someone else to fill in. | [`to-questionnaire/SKILL.md`](./to-questionnaire/SKILL.md) |
| 115 | **`to-spec`** | Turn the current conversation into a spec and publish it to the project issue tracker: no interview, just synthesis of what you've already discussed. | [`to-spec/SKILL.md`](./to-spec/SKILL.md) |
| 116 | **`to-tickets`** | Decompose plans or specs into tracer-bullet tickets with explicit dependency blocking edges for step-by-step progress. | [`to-tickets/SKILL.md`](./to-tickets/SKILL.md) |
| 117 | **`triage`** | Move issues and external PRs through a state machine of triage roles, categorise, verify, grill if needed, and write agent-ready briefs. | [`triage/SKILL.md`](./triage/SKILL.md) |
| 118 | **`typescript-expert`** | TypeScript and JavaScript expert: type-level programming, performance optimization, monorepo architecture, and debugging. | [`typescript-expert/SKILL.md`](./typescript-expert/SKILL.md) |
| 119 | **`ui-ux-pro-max`** | UI/UX design intelligence: 50+ styles, 21 palettes, typography, responsive layouts, components (React, Tailwind, shadcn). | [`ui-ux-pro-max/SKILL.md`](./ui-ux-pro-max/SKILL.md) |
| 120 | **`video-downloader`** | Downloads videos from YouTube and other platforms for offline viewing, editing, or archival. Handles various formats and quality options. | [`video-downloader/SKILL.md`](./video-downloader/SKILL.md) |
| 121 | **`wait-what`** | Stop. That last message did not land: re-pitch it. | [`wait-what/SKILL.md`](./wait-what/SKILL.md) |
| 122 | **`wayfinder`** | Decompose massive tasks into an issue-tracker dependency graph of decision tickets for step-by-step resolution. | [`wayfinder/SKILL.md`](./wayfinder/SKILL.md) |
| 123 | **`web-design-guidelines`** | Audit and enforce Vercel Web Interface Guidelines: hit targets >=48px, keyboard focus, mobile inputs >=16px, and loading states. | [`web-design-guidelines/SKILL.md`](./web-design-guidelines/SKILL.md) |
| 124 | **`web-quality-audit`** | Comprehensive web quality audit covering performance, accessibility, SEO, Core Web Vitals, and best practices. | [`web-quality-audit/SKILL.md`](./web-quality-audit/SKILL.md) |
| 125 | **`web-to-markdown`** | Fetch and convert web pages into clean Markdown using headless browser rendering (web2md CLI). | [`web-to-markdown/SKILL.md`](./web-to-markdown/SKILL.md) |
| 126 | **`windows-desktop-e2e`** | End-to-end UI automation testing for Windows native desktop apps (WPF, WinForms, Win32, Qt) via pywinauto. | [`windows-desktop-e2e/SKILL.md`](./windows-desktop-e2e/SKILL.md) |
| 127 | **`wizard`** | Generate an interactive bash wizard walking a human through manual tasks like secret provisioning, credentials, or cutovers. | [`wizard/SKILL.md`](./wizard/SKILL.md) |
| 128 | **`writing-beats`** | Writing, exploit; assemble raw material into a journey of beats, grounding each term before a beat leans on it. | [`writing-beats/SKILL.md`](./writing-beats/SKILL.md) |
| 129 | **`writing-for-agents`** | Writing documents for agents. Use when creating or editing skills, or modifying AGENTS.md or CLAUDE.md. | [`writing-for-agents/SKILL.md`](./writing-for-agents/SKILL.md) |
| 130 | **`writing-fragments`** | Writing, explore: mine raw fragments, no structure yet. | [`writing-fragments/SKILL.md`](./writing-fragments/SKILL.md) |
| 131 | **`writing-shape`** | Writing, exploit: shape raw material into an article, paragraph by paragraph. | [`writing-shape/SKILL.md`](./writing-shape/SKILL.md) |
| 132 | **`xlsx`** | Create, inspect, edit, format and convert spreadsheets (.xlsx, .csv, .tsv) with zero formula errors and professional tables. | [`xlsx/SKILL.md`](./xlsx/SKILL.md) |
