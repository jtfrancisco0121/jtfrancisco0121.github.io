# Jan Terence Francisco — Portfolio

**Senior Full-Stack Developer** · Go · TypeScript/React · Python/FastAPI · Rust · Java/Spring Boot

📧 jtfrancisco21@gmail.com · 🐙 [github.com/jtfrancisco0121](https://github.com/jtfrancisco0121) · 🌐 [Portfolio site](https://jtfrancisco0121.github.io/portfolio/)

I own systems end to end: I write the spec, build it across the backend, web and desktop, and put tests and release gates around it. Lately I ship production apps for small businesses and local government in the Philippines, and I build my own tooling for AI-assisted development.

---

## Active projects

### 🖥️ DCTerminalv2 — desktop workspace for Claude Code agents · [repo](https://github.com/jtfrancisco0121/DCTerminalv2)
`Rust` `Tauri 2` `React` `xterm.js` `TypeScript` `Shell`

A macOS and Windows terminal app for Claude Code. Its **Eagle-Eye** pipeline plans a change, waits for your approval, builds it in parallel git worktrees, reviews it, and opens PRs only after you approve.
- Tabs and split panes, a command palette, and per-tab "needs you" status with desktop and phone push notifications (ntfy, Pushover, webhook)
- Run panel showing stages, per-PR progress, CI checks, review gates, cost and timeline
- ClickUp integration: paste a ticket or epic link to start a run, then post results back to it
- A bundled Claude Code plugin with role skills (planner, developer, PR reviewer, codebase audit)
- Safety: a guard keeps agents inside their worktree, nothing is pushed without approval, and secrets stay in the OS keychain

*Second version of [DCTerminal](https://github.com/jtfrancisco0121/DCTerminal), a role-per-tab agent workspace with hand-offs and autopilot pipelines.*

### 🛒 TMEcommWeb — B2B ordering portal · *private, client work (Torrecamps Marketing)*
`Next.js 15` `TypeScript` `Tailwind v4` `shadcn/ui` `Drizzle` `PostgreSQL` `Auth.js v5` `Railway`

Customer ordering portal with an admin portal that requires Zoho sign-in.
- Registration goes through admin approval, which creates a Zoho Contact; each customer has their own price book
- Admins create **Zoho Books draft invoices** from submitted orders, so customers can't push invoices into Zoho directly
- Messaging (S3 attachments, Web Push), PWA, Zoho catalog and stock sync, and a **shared daily Zoho API budget**
- About 400 Vitest and Playwright tests; Docker on Railway with migrations at release time and a health-check endpoint

### 📊 TMZohoBooksInteg + TMOps — finance and operations system · *private, client work*
`Python` `FastAPI` `PostgreSQL` `Alembic` `WeasyPrint` `openpyxl` `Docker` `PyInstaller`

Internal operations system built on Zoho Books and Inventory.
- Invoices, bills and stock; Daily Sales; A/R aging; **PH BIR VAT/EWT** reporting; payroll posted as Zoho expenses
- Print layouts with calibration for pre-printed invoices, receipts and cheques; PDF and Excel export
- Runs on Docker/Railway and also as a Windows desktop launcher (PyInstaller)
- TMOps mirrors Zoho data into Postgres, so reports and dashboards don't use up API quota

---

## Professional work

### Koneksi Inc. — Senior Fullstack Developer *(Oct 2025 – present)*
Own **DATARK** end to end across a Go backend and TypeScript web and desktop apps.
- **File Disaster Recovery & Compliance:** scoring engine, control matrix, audit ledger, Korean PDF reports, Org Admin dashboard, on-demand recovery testing, retention, and file preview
- **Notification system** on Asynq/AsynqMon with delivery separated by role, plus role-based onboarding
- Storage reliability: S3 gateway and credentials redesign; realtime-backup recovery (CID correctness, retry/backoff, resumable downloads)
- **300+ Playwright desktop E2E tests** in CI as a release gate; promo/billing and timezone fixes; JWT/service-account APIs, OpenAPI

### Torrecamps Marketing — Software Consultant *(May 2026 – present)*
TMEcommWeb, TMZohoBooksInteg and TMOps (see above).

### Philtech Inc. — Software Engineer I *(Sept 2024 – Oct 2025)*
Resolved production incidents with ESL, scales, SignShop and POS systems; automated tag forecasting and ESL monitoring that catches stuck HOST→Aperion batches; built a Python queue/wait-time dashboard.

---

## Skills

| | |
|---|---|
| **Frontend** | TypeScript, React, Next.js, Tailwind, xterm.js |
| **Backend** | Go, Python/FastAPI, Java/Spring Boot, Rust (Tauri), JWT, OpenAPI, Asynq |
| **Data** | PostgreSQL, SQLite, SQL Server, MySQL, S3, IPFS |
| **Desktop** | Tauri 2, Electron, PyInstaller |
| **Integrations** | Zoho Books/Inventory, Auth.js, OAuth, Web Push, ClickUp |
| **Delivery** | Docker, Railway, GitHub Actions, Playwright, Vitest, pytest |
| **AI-assisted engineering** | Claude Code, Cursor, spec-to-code loops, agent handoffs, review gates |

## Education
**BS Information Technology — Mobile and Internet Technologies**, Asia Pacific College (2019–2024)

---
<sub>Private repos are client or personal work; I can walk through the code on request.</sub>
