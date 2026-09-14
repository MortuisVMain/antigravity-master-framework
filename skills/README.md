# 🧰 Antigravity Skills Catalog (95+ Production Skills)

Welcome to the **Antigravity Skills Catalog** — the world's most comprehensive collection of specialized engineering, architecture, design, and automation skills for AI coding agents.

Each skill is a self-contained instruction bundle (`SKILL.md`) that an agent autonomously absorbs to enforce domain-level best practices.

---

## 🚀 How to Install a Skill

### For Antigravity Agent / Google AGY:
```bash
# Clone the repository
git clone https://github.com/MortuisVMain/antigravity-master-framework.git

# Copy any individual skill into your local skills directory:
mkdir -p ~/.gemini/config/skills/<skill-name>
cp -r antigravity-master-framework/skills/<skill-name>/* ~/.gemini/config/skills/<skill-name>/

# Or install ALL skills at once:
cp -r antigravity-master-framework/skills/* ~/.gemini/config/skills/
```

### For Claude Code / Cursor:
```bash
# Symlink or copy matching skill into Claude Code skills:
mkdir -p ~/.claude/skills/<skill-name>
cp -r antigravity-master-framework/skills/<skill-name>/* ~/.claude/skills/<skill-name>/
```

---

## 📚 Complete Skills Directory (95 Skills)

| Skill Name | Description | Path |
| :--- | :--- | :---: |
| **`accessibility`** | Audit and improve web accessibility following WCAG 2.1 guidelines. Use when asked to "improve accessibility", "a11y audi... | [`skills/accessibility/`](./accessibility/SKILL.md) |
| **`accidental-data-loss-prevention`** | | | [`skills/accidental-data-loss-prevention/`](./accidental-data-loss-prevention/SKILL.md) |
| **`api-platform-builder`** | Master REST API design, FastAPI/Flask microservices, OpenAPI contracts, Pydantic V2 validation, JWT auth, and API stress... | [`skills/api-platform-builder/`](./api-platform-builder/SKILL.md) |
| **`architecture-decision-records`** | Capture architectural decisions made during Claude Code sessions as structured ADRs. Auto-detects decision moments, reco... | [`skills/architecture-decision-records/`](./architecture-decision-records/SKILL.md) |
| **`architecture-patterns`** | Design, implement, and refactor Ports & Adapters systems with clear domain boundaries, dependency inversion, and testabl... | [`skills/architecture-patterns/`](./architecture-patterns/SKILL.md) |
| **`bash-pro`** | Master of defensive Bash scripting for production automation, CI/CD | [`skills/bash-pro/`](./bash-pro/SKILL.md) |
| **`benchmark-optimization-loop`** | Use when the user asks to make something faster, try many variants, run recursive optimization, benchmark latency/throug... | [`skills/benchmark-optimization-loop/`](./benchmark-optimization-loop/SKILL.md) |
| **`blender-motion-state-inspection`** | Use this skill when inspecting Blender characters, rigs, poses, animation retargeting, ground contact, facing direction,... | [`skills/blender-motion-state-inspection/`](./blender-motion-state-inspection/SKILL.md) |
| **`ce-brainstorm`** | Explore vague or ambitious ideas into a right-sized requirements-only unified plan. Use when the user wants to brainstor... | [`skills/ce-brainstorm/`](./ce-brainstorm/SKILL.md) |
| **`ce-code-review`** | Structured code review for bugs, regressions, tests, and standards. Use before PRs or when asked to review code. Use whe... | [`skills/ce-code-review/`](./ce-code-review/SKILL.md) |
| **`ce-commit-push-pr`** | Commit, push, and open a PR. Use when asked to ship/open a PR, or for PR-description-only flows like writing, rewriting,... | [`skills/ce-commit-push-pr/`](./ce-commit-push-pr/SKILL.md) |
| **`ce-compound`** | Document a solved problem as a durable repo learning. Use when verified work produced non-obvious reasoning absent from ... | [`skills/ce-compound/`](./ce-compound/SKILL.md) |
| **`ce-compound-refresh`** | Refresh the repo's captured learnings against the current codebase. Use when auditing stale, overlapping, superseded, or... | [`skills/ce-compound-refresh/`](./ce-compound-refresh/SKILL.md) |
| **`ce-doc-review`** | Review requirements, plans, or specs with role-specific lenses. Use when the user wants to improve an existing planning ... | [`skills/ce-doc-review/`](./ce-doc-review/SKILL.md) |
| **`ce-explain`** | Create a durable visual teaching artifact for something worth learning. Use when the user wants to be taught, wants a de... | [`skills/ce-explain/`](./ce-explain/SKILL.md) |
| **`ce-handoff`** | Create a session handoff for another agent, or resume, find, and read any user-selected continuity source. Use when work... | [`skills/ce-handoff/`](./ce-handoff/SKILL.md) |
| **`ce-ideate`** | Generate and evaluate grounded ideas. Use when the user wants ideas, improvements, or surprising directions before choos... | [`skills/ce-ideate/`](./ce-ideate/SKILL.md) |
| **`ce-optimize`** | Optimize a named target with a measured loop: attribute a workload's cost, or score variants and keep winners. Use when ... | [`skills/ce-optimize/`](./ce-optimize/SKILL.md) |
| **`ce-polish`** | Polish a working feature through user-directed live browser feedback. Use when a functional feature needs focused UX ref... | [`skills/ce-polish/`](./ce-polish/SKILL.md) |
| **`ce-pov`** | Give a decisive, project-grounded point of view: a graded verdict on an external-adoption question, a holistic take on a... | [`skills/ce-pov/`](./ce-pov/SKILL.md) |
| **`ce-prototype`** | Build a throwaway prototype to answer how something should work, feel, or read. Use when committing the wrong answer wou... | [`skills/ce-prototype/`](./ce-prototype/SKILL.md) |
| **`ce-resolve-pr-feedback`** | Resolve PR review feedback. Use when addressing feedback already left on a PR. Not for reviewing the code before feedbac... | [`skills/ce-resolve-pr-feedback/`](./ce-resolve-pr-feedback/SKILL.md) |
| **`ce-setup`** | Check Compound Engineering health and repo-local config. | [`skills/ce-setup/`](./ce-setup/SKILL.md) |
| **`ce-strategy`** | Create or update STRATEGY.md. Use when starting a product, adding a strategy doc to an existing repo, changing direction... | [`skills/ce-strategy/`](./ce-strategy/SKILL.md) |
| **`ce-test-browser`** | Run browser tests for pages affected by the current branch or PR. Use when asked to run or check browser tests for the c... | [`skills/ce-test-browser/`](./ce-test-browser/SKILL.md) |
| **`ce-work`** | Execute a plan or concrete work prompt end-to-end. Use when implementing from a plan document, a spec path, or a clear b... | [`skills/ce-work/`](./ce-work/SKILL.md) |
| **`ce-worktree`** | Set up isolated git worktrees — create a new branch for fresh work, or attach a worktree to an existing branch, PR, or c... | [`skills/ce-worktree/`](./ce-worktree/SKILL.md) |
| **`clean-code`** | Baseline cross-project coding conventions for naming, readability, immutability, and code-quality review. Use detailed f... | [`skills/clean-code/`](./clean-code/SKILL.md) |
| **`code-reviewer-pro`** | Master code review, refactoring, and code simplification engine. Fuses Clean Code standards (SOLID, DRY, immutability), ... | [`skills/code-reviewer-pro/`](./code-reviewer-pro/SKILL.md) |
| **`core-web-vitals`** | Optimize Core Web Vitals (LCP, INP, CLS) for better page experience and search ranking. Use when asked to "improve Core ... | [`skills/core-web-vitals/`](./core-web-vitals/SKILL.md) |
| **`cpp-pro`** | C++ coding standards based on the C++ Core Guidelines (isocpp.github.io). Use when writing, reviewing, or refactoring C+... | [`skills/cpp-pro/`](./cpp-pro/SKILL.md) |
| **`cpp-testing`** | Use only when writing/updating/fixing C++ tests, configuring GoogleTest/CTest, diagnosing failing or flaky tests, or add... | [`skills/cpp-testing/`](./cpp-testing/SKILL.md) |
| **`critic-triad`** | Global 3-Critic Supreme Council & Autonomous Skill-Hunter. Dynamically summons a Triad of adversarial critics (1: Red-Te... | [`skills/critic-triad/`](./critic-triad/SKILL.md) |
| **`csharp-testing`** | C# and .NET testing patterns with xUnit, FluentAssertions, mocking, integration tests, and test organization best practi... | [`skills/csharp-testing/`](./csharp-testing/SKILL.md) |
| **`database-migrations`** | Database migration best practices for schema changes, data migrations, rollbacks, and zero-downtime deployments across P... | [`skills/database-migrations/`](./database-migrations/SKILL.md) |
| **`database-schema-designer`** | Design robust, scalable database schemas for SQL and NoSQL databases. Provides normalization guidelines, indexing strate... | [`skills/database-schema-designer/`](./database-schema-designer/SKILL.md) |
| **`design-to-code`** | Pixel-perfect Figma to React conversion using coderio. Generates production-ready code (TypeScript, Vite, TailwindCSS V4... | [`skills/design-to-code/`](./design-to-code/SKILL.md) |
| **`devops-and-cloud`** | Docker containerization, multi-stage builds, docker-compose orchestration, GitHub Actions CI/CD pipelines, and cloud dep... | [`skills/devops-and-cloud/`](./devops-and-cloud/SKILL.md) |
| **`django-pro`** | Master Django 5.x with async views, DRF, Celery, and Django Channels. Build scalable web applications with proper archit... | [`skills/django-pro/`](./django-pro/SKILL.md) |
| **`docker-expert`** | Docker containerization expert with deep knowledge of multi-stage builds, image optimization, container security, Docker... | [`skills/docker-expert/`](./docker-expert/SKILL.md) |
| **`docx`** | Use this skill whenever the user wants to create, read, edit, or manipulate Word documents (.docx files). Triggers inclu... | [`skills/docx/`](./docx/SKILL.md) |
| **`execution-planner`** | Master engineering execution planner and architectural design engine. Fuses proactive requirement grilling (/grill-me mo... | [`skills/execution-planner/`](./execution-planner/SKILL.md) |
| **`fastapi-pro`** | Build high-performance async APIs with FastAPI, SQLAlchemy 2.0, and Pydantic V2. Master microservices, WebSockets, and m... | [`skills/fastapi-pro/`](./fastapi-pro/SKILL.md) |
| **`"figma-implement-design"`** | Translate Figma nodes into production-ready code with 1:1 visual fidelity using the Figma MCP workflow (design context, ... | [`skills/figma-implement-design/`](./figma-implement-design/SKILL.md) |
| **`file-organizer`** | Intelligently organizes files and folders by understanding context, finding duplicates, and suggesting better organizati... | [`skills/file-organizer/`](./file-organizer/SKILL.md) |
| **`game-development`** | Game development orchestrator. Routes to platform-specific skills based on project needs. | [`skills/game-development/`](./game-development/SKILL.md) |
| **`image-enhancer`** | Improves the quality of images, especially screenshots, by enhancing resolution, sharpness, and clarity. Perfect for pre... | [`skills/image-enhancer/`](./image-enhancer/SKILL.md) |
| **`image-to-code`** | Elite website image-to-code skill for Codex. For visually important web tasks, it must first generate the design image(s... | [`skills/image-to-code/`](./image-to-code/SKILL.md) |
| **`javascript-mastery`** | Comprehensive JavaScript reference covering 33+ essential concepts every developer should know. From fundamentals like p... | [`skills/javascript-mastery/`](./javascript-mastery/SKILL.md) |
| **`karpathy-guidelines`** | Enforce Andrej Karpathy's 4 core coding principles: Think Before Coding, Simplicity First, Surgical Changes, and Goal-Dr... | [`skills/karpathy-guidelines/`](./karpathy-guidelines/SKILL.md) |
| **`lavish`** | Turn complex or visual agent responses into rich, reviewable HTML artifacts the user can annotate and send feedback on, ... | [`skills/lavish/`](./lavish/SKILL.md) |
| **`lfg`** | Run the full autonomous shipping pipeline end-to-end, hands-off with no check-ins. Use only when the user explicitly ask... | [`skills/lfg/`](./lfg/SKILL.md) |
| **`mermaid-diagrams`** | Comprehensive guide for creating software diagrams using Mermaid syntax. Use when users need to create, visualize, or do... | [`skills/mermaid-diagrams/`](./mermaid-diagrams/SKILL.md) |
| **`ml-best-practices`** | | | [`skills/ml-best-practices/`](./ml-best-practices/SKILL.md) |
| **`nextjs-best-practices`** | Next.js App Router principles. Server Components, data fetching, routing patterns. | [`skills/nextjs-best-practices/`](./nextjs-best-practices/SKILL.md) |
| **`open-design-pro`** | Master design engineering and anti-slop frontend engine. Fuses DESIGN.md token contracts (OKLCH, typography, elevation),... | [`skills/open-design-pro/`](./open-design-pro/SKILL.md) |
| **`PDF Processing Pro`** | Production-ready PDF processing with forms, tables, OCR, validation, and batch operations. Use when working with complex... | [`skills/pdf-processing-pro/`](./pdf-processing-pro/SKILL.md) |
| **`performance`** | Optimize web performance for faster loading and better user experience. Use when asked to "speed up my site", "optimize ... | [`skills/performance/`](./performance/SKILL.md) |
| **`personal-tool-builder`** | Expert in building custom tools that solve your own problems first. The best products often start as personal tools - sc... | [`skills/personal-tool-builder/`](./personal-tool-builder/SKILL.md) |
| **`"playwright"`** | Use when the task requires automating a real browser from the terminal (navigation, form filling, snapshots, screenshots... | [`skills/playwright/`](./playwright/SKILL.md) |
| **`powershell-windows`** | PowerShell Windows patterns. Critical pitfalls, operator syntax, error handling. | [`skills/powershell-windows/`](./powershell-windows/SKILL.md) |
| **`prd`** | Generate a Product Requirements Document (PRD) for a new feature. Use when planning a feature, starting a new project, o... | [`skills/prd/`](./prd/SKILL.md) |
| **`python-mastery`** | Master modern Python 3.12+ engineering and architecture. Fuses idiomatic Python patterns, high-performance asyncio concu... | [`skills/python-mastery/`](./python-mastery/SKILL.md) |
| **`python-patterns`** | Python development principles and decision-making. Framework selection, async patterns, type hints, project structure. T... | [`skills/python-patterns/`](./python-patterns/SKILL.md) |
| **`python-testing-patterns`** | Python testing strategies using pytest, TDD methodology, fixtures, mocking, parametrization, and coverage requirements. ... | [`skills/python-testing-patterns/`](./python-testing-patterns/SKILL.md) |
| **`ralph`** | Convert PRDs to prd.json format for the Ralph autonomous agent system. Use when you have an existing PRD and need to con... | [`skills/ralph/`](./ralph/SKILL.md) |
| **`vercel-react-best-practices`** | React and Next.js performance optimization guidelines from Vercel Engineering. This skill should be used when writing, r... | [`skills/react-best-practices/`](./react-best-practices/SKILL.md) |
| **`react-patterns`** | Modern React patterns and principles. Hooks, composition, performance, TypeScript best practices. | [`skills/react-patterns/`](./react-patterns/SKILL.md) |
| **`react-ui-patterns`** | Modern React UI patterns for loading states, error handling, and data fetching. Use when building UI components, handlin... | [`skills/react-ui-patterns/`](./react-ui-patterns/SKILL.md) |
| **`rust-patterns`** | Idiomatic Rust patterns, ownership, error handling, traits, concurrency, and best practices for building safe, performan... | [`skills/rust-patterns/`](./rust-patterns/SKILL.md) |
| **`rust-testing`** | Rust testing patterns including unit tests, integration tests, async testing, property-based testing, mocking, and cover... | [`skills/rust-testing/`](./rust-testing/SKILL.md) |
| **`screenshot-feature-extractor`** | Analyze product screenshots to extract feature lists and generate development task checklists. Use when: (1) Analyzing c... | [`skills/screenshot-feature-extractor/`](./screenshot-feature-extractor/SKILL.md) |
| **`senior-architect`** | Comprehensive software architecture skill for designing scalable, maintainable systems using ReactJS, NextJS, NodeJS, Ex... | [`skills/senior-architect/`](./senior-architect/SKILL.md) |
| **`senior-backend`** | Comprehensive backend development skill for building scalable backend systems using NodeJS, Express, Go, Python, Postgre... | [`skills/senior-backend/`](./senior-backend/SKILL.md) |
| **`senior-data-scientist`** | World-class data science skill for statistical modeling, experimentation, causal inference, and advanced analytics. Expe... | [`skills/senior-data-scientist/`](./senior-data-scientist/SKILL.md) |
| **`senior-devops`** | Comprehensive DevOps skill for CI/CD, infrastructure automation, containerization, and cloud platforms (AWS, GCP, Azure)... | [`skills/senior-devops/`](./senior-devops/SKILL.md) |
| **`senior-frontend`** | Comprehensive frontend development skill for building modern, performant web applications using ReactJS, NextJS, TypeScr... | [`skills/senior-frontend/`](./senior-frontend/SKILL.md) |
| **`senior-fullstack`** | Comprehensive fullstack development skill for building complete web applications with React, Next.js, Node.js, GraphQL, ... | [`skills/senior-fullstack/`](./senior-fullstack/SKILL.md) |
| **`senior-ml-engineer`** | World-class ML engineering skill for productionizing ML models, MLOps, and building scalable ML systems. Expertise in Py... | [`skills/senior-ml-engineer/`](./senior-ml-engineer/SKILL.md) |
| **`senior-prompt-engineer`** | World-class prompt engineering skill for LLM optimization, prompt patterns, structured outputs, and AI product developme... | [`skills/senior-prompt-engineer/`](./senior-prompt-engineer/SKILL.md) |
| **`senior-qa`** | Comprehensive QA and testing skill for quality assurance, test automation, and testing strategies for ReactJS, NextJS, N... | [`skills/senior-qa/`](./senior-qa/SKILL.md) |
| **`senior-security`** | Comprehensive security engineering skill for application security, penetration testing, security architecture, and compl... | [`skills/senior-security/`](./senior-security/SKILL.md) |
| **`seo`** | Optimize for search engine visibility and ranking. Use when asked to "improve SEO", "optimize for search", "fix meta tag... | [`skills/seo/`](./seo/SKILL.md) |
| **`skill-repair`** | | | [`skills/skill-repair/`](./skill-repair/SKILL.md) |
| **`systematic-debugger`** | Master systematic debugging and error diagnosis engine. Fuses first-principles root cause analysis, reproducible test cr... | [`skills/systematic-debugger/`](./systematic-debugger/SKILL.md) |
| **`design-taste-frontend`** | Anti-slop frontend skill for landing pages, portfolios, and redesigns. The agent reads the brief, infers the right desig... | [`skills/taste-skill/`](./taste-skill/SKILL.md) |
| **`tdd-workflow`** | Use this skill when writing new features, fixing bugs, or refactoring code. Enforces test-driven development with 80%+ c... | [`skills/tdd-workflow/`](./tdd-workflow/SKILL.md) |
| **`typescript-expert`** | >- | [`skills/typescript-expert/`](./typescript-expert/SKILL.md) |
| **`ui-ux-pro-max`** | UI/UX design intelligence. 50 styles, 21 palettes, 50 font pairings, 20 charts, 9 stacks (React, Next.js, Vue, Svelte, S... | [`skills/ui-ux-pro-max/`](./ui-ux-pro-max/SKILL.md) |
| **`video-downloader`** | Downloads videos from YouTube and other platforms for offline viewing, editing, or archival. Handles various formats and... | [`skills/video-downloader/`](./video-downloader/SKILL.md) |
| **`web-design-guidelines`** | Review and enforce Vercel Web Interface Guidelines compliance. Checks UI code for hit targets, keyboard accessibility, f... | [`skills/web-design-guidelines/`](./web-design-guidelines/SKILL.md) |
| **`web-quality-audit`** | Comprehensive web quality audit covering performance, accessibility, SEO, and best practices. Use when asked to "audit m... | [`skills/web-quality-audit/`](./web-quality-audit/SKILL.md) |
| **`web-to-markdown`** | Use ONLY when the user explicitly says: 'use the skill web-to-markdown ...' (or 'use a skill web-to-markdown ...'). Conv... | [`skills/web-to-markdown/`](./web-to-markdown/SKILL.md) |
| **`windows-desktop-e2e`** | E2E testing for Windows native desktop apps (WPF, WinForms, Win32/MFC, Qt) using pywinauto and Windows UI Automation. Us... | [`skills/windows-desktop-e2e/`](./windows-desktop-e2e/SKILL.md) |
| **`xlsx`** | Use this skill any time a spreadsheet file is the primary input or output. This means any task where the user wants to: ... | [`skills/xlsx/`](./xlsx/SKILL.md) |

---

## 🛠 Adding Custom Skills
To add a new skill to the framework:
1. Create a directory: `skills/<your-skill-name>/`
2. Create `SKILL.md` with standard YAML frontmatter (`name:`, `description:`, `user-invocable:`).
3. Specify domain rules, anti-patterns, checklists, and code examples.
