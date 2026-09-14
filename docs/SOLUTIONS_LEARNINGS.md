# 🧠 General Engineering Solutions & Platform Gotchas (001–011)

> **Methodology:** Compound Engineering (Continuous Learning Loop)  
> **Goal:** Eliminate AI agent amnesia across sessions. Every engineering breakthrough or non-obvious platform quirk is captured here.

---

## 📌 Registry of Solved Platform Gotchas & Architecture Solutions

| ID | Solution Title | Stack / Domain | Key Engineering Insight |
| :-: | :--- | :--- | :--- |
| **001** | **Bypassing CORS for ES Modules in Playwright** | Frontend / E2E / Node.js | Chromium blocks `type="module"` on `file:///`. Fix: spin up an ephemeral local HTTP server on port 0. |
| **002** | **Ralph Autonomous Agent Harness Architecture** | AI Scaffolding / Git | Eliminate context rot via isolated clean-context runs, `prd.json`, and atomic git commits. |
| **003** | **Karpathy Agent Calibration Guidelines** | AI Alignment / Code Quality | Eliminate overengineering: Think First, Simplicity First (200->50), Surgical Changes, Goal-Driven. |
| **004** | **Universal Agent Action Algorithm (v2.6)** | AI Alignment / Master Loop | 5-phase deterministic cycle: Awakening ➔ Skill-Hunting ➔ Critic Triad ➔ Surgical Execution ➔ Compound. |
| **005** | **Test Isolation & Falsy Fallbacks in Python** | Python / Testing | Ban `arg or os.getenv()`, which breaks tests when `arg=""`. Always use `if arg is not None:`. |
| **006** | **Packaging Web Apps into .exe with Taskbar Icon** | Desktop / .NET 10 / WebView2 | Register AppUserModelID before UI starts; use multi-layer PNG-in-ICO and SingleFile without CORS. |
| **007** | **Fixing Console Encoding (CP866 vs UTF-8) in Windows CLI** | Desktop / Rust / PowerShell | Fix encoding glitches in CLI tools (DISM/SFC): `chcp 65001` + synchronize `OutputEncoding`. |
| **008** | **Cargo File Locks in Cloud Sync Folders (os error 32)** | Desktop / Rust / Cargo | Redirect `CARGO_TARGET_DIR` to `$env:TEMP` to eliminate sharing violations and speed up builds 3-4x. |
| **009** | **Fixing TaskDialogIndirect Not Found in Tauri / Windows** | Desktop / Tauri 2 / Windows | Custom app manifest MUST declare dependency on Common-Controls v6, otherwise Windows loads legacy v5. |
| **010** | **Fixing TypeError: Client.__init__() in TestClient** | Backend / Python 3.14 / HTTPX | Use `AsyncClient(transport=ASGITransport(app=app))` to resolve breaking changes in httpx 0.28+. |
| **011** | **Global Critic Triad & Autonomous Skill-Hunter (v2.6)** | AI Architecture / Multi-Agent | Eliminate blind spots & AI slop via Triad of adversarial critics (Skeptic + Pragmatist + Specialist). |
