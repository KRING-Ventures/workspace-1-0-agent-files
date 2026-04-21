# KRING

Universal. Org context so the agent can speak KRING to its user — who KRING is, the Speedbooting framework, current ventures, people, how KRING operates. Ships with every agent.

---

## What KRING is

**KRING Ventures** — a Danish venture studio and fund. KRING builds AI-native businesses: product flows, venture-building capability, and operational infrastructure. Not a consultancy. Not a pure fund. We build, incubate, and run.

## What KRING does

- **Spins up ventures** inside the KRING ecosystem — each with one product, one customer, one problem.
- **Runs a shared operating model** (Speedbooting OS) across every venture so the framework — not the founder's memory — carries continuity.
- **Ships shared infrastructure**: personal AI agents (OpenClaw-powered), Notion, Slack, Google Workspace, GitHub, Obsidian, the Cosmica platform.
- **Invests in learning year** — August is explicit that 2026 is a year of skill-building, framework-building, and cashflow. Treat this seriously in any work.

Current direction: AI-native business solutions; 2-year vision is "AI-driven businesses for a better world." Immediate priority: Learning & Cashflow.

## Speedbooting OS

KRING's delivery system. Everything non-trivial moves through a **Speedblock** — a scoped, versioned unit of work with a proper Build → Test → Publish lifecycle and five canonical deliverables.

### Core mantra

> *Think big, start small, scale fast.*

Every Speedblock starts with the full vision, then scopes ruthlessly to the smallest deliverable unit, then builds momentum through rapid iteration — at every level (Speedblock, stage, task).

### Two layers, kept separate

1. **Framework layer** — what a Speedblock *is* and how the system works. Lives in the Master Brief and the `speedblock-master-brief` skill references.
2. **Speedblock layer** — the packaged deliverables of a finished Speedblock.

Construction does *not* live in a separate document layer. It lives inside the Notion task hierarchy for that specific Speedblock. Don't blur these.

### Lifecycle

Three phases: **Build → Test → Publish.**

Build is where most agent work lives. Inside Build, stages run through Scope → Research → Solution → Prototype → Learning → Blueprint. Prototype is a fixed Build stage, not an optional shortcut — the solution must be proven in reality before formal packaging. Learning defines how the proven solution will be measured and kept healthy. Blueprint converts validated solution + learning logic into the full Speedblock package.

### Five core deliverables (the packaged output of a finished Speedblock)

1. **Value Brief** — why it exists, who it's for, what it's worth.
2. **Playbook** — how to run it.
3. **Toolkit** — what you need to run it.
4. **Onboarding** — deployment and adoption guide (formerly "Rollout Plan").
5. **Cosmo KF** — the Cosmo Knowledge File that lets the org agent run it forward.

### Task hierarchy in Notion PM

- Create the Speedblock as a **project in Project Overview** first. Fill project metadata (Status, Owner, Start Date, Finish Date, Blocked By, Category = Speedblock, Goal, About) *before* creating tasks.
- Task hierarchy: **head task → subphase → individual task.** The three head tasks are Build, Test, Publish.
- Under each subphase, keep **one subphase task** first. Standard stage elements live on that task's page as the initial content structure.
- **For Scope:** the main Scope task defines the overall problem space, affected users, boundaries, why-now, what's needed to move forward, and what counts as done. Create concrete Scope subtasks for real scoping jobs — not template headings. Name them after the real work. Don't add another task layer below this.
- **Every task page, at every level, gets operational text from the start:** clear goal, clear description, clear rule for what's needed to move to the next status, clear definition of done. A title alone is never enough.

### Versioning

- Speedblocks ship as v1.0, v1.1, etc. **Never rename a page** — scope splits or shifts become the next sequential version.
- Current state is read from **live project mapping statuses**, not canonical order alone. A later phase becomes next only when the current is Done.

### Standing rules (hard)

- **August writes every Building Brief himself.** Agents don't draft or edit brief content.
- **Scope-stage Pain / Outcome / Impact must not name specific tools or delivery formats** — those belong in Research / Solution.
- **When Solution is locked, Solution is the source of truth** — not Research.
- **Already-embedded ≠ kept.** A tool/decision is only "kept" with an explicit decision. Otherwise it's open.
- **Success measures describe user value**, not agent activity.
- **Examples in briefs are illustrative, not prescriptive.**
- **Keep Status live** in the PM Tasks DB as work moves — not batched at the end.
- **Work inside the original stage task.** Spin-offs only when something fundamentally new surfaces, not for admin sub-steps.
- **Deadlines move honestly.** When a date slips, log the reason explicitly instead of drifting silently.
- **Never touch August's Notion pages** (edits, inserts, reverts, cleanup) without explicit per-action permission.

## Current ventures (2026-04-21 snapshot)

- **Cosmica** — KRING's internal Speedbooting Platform. Canonical home for Speedblocks, Services, Idea Canvas. Notion → Cosmica sync feeds the Activity model (Strategic Initiatives + Management Priorities). Hosted on Render; code at `KRING-Ventures/Cosmica` on GitHub.
- **Carelog ApS** — AI clinical note-taking for Danish healthcare practitioners (psychologists, physicians, physios, psychiatrists, business psychologists). Record → transcribe → generate structured clinical note. CVR 45350916, founded 2026-01-20. Pricing: 349 DKK/mo Standard (solo), 299 DKK/mo per user Clinic (5+). D-Mærket certified. 14-day self-serve trial.

Active Speedblocks right now: **Workspace v1.0** (personal agents for the first 3 pilots, shipping 2026-04-22) and **Workspace v1.1** (MS → Google cutover, split from v1.0 on 2026-04-20).

## People

KRING's principals — the people a personal agent should recognise when its user mentions them.

| Name | Role | Notes |
|---|---|---|
| **August Kring** | Co-founder / partner | Drives the Speedblock / Master Brief framework. Primary day-to-day interlocutor for Cosmo. Copenhagen-based. Danish (works in English). |
| **Martin Kring** | CEO, co-founder, partner | August's uncle. Family-and-business overlap — decisions can carry dual context. |
| **Jesper Kring** | Co-founder, partner | August's father. Same family-and-business overlap. Pilot for Workspace 1.0. |
| **Thomas Hjort** | Partner, co-founder | |
| **Corey Henderson** | CTO-at-large, partner | Builds agent infra (OpenClaw), Cosmica platform, tooling. `corey@kringventures.com`. Lives in Claude Code / Cursor / GitHub PRs. |
| **Johan Rishede Duus** | Senior growth hacker | Pilot for Workspace 1.0. |

External collaborators appear in Slack/PRs (e.g. Philip on Carelog context). They're not principals — don't treat them as decision-makers.

## How KRING communicates

- **Slack** — primary ops comms. Threaded. Decisions log to Notion one-at-a-time as they land, not batched.
- **Notion** — source of truth for Speedblock state and Project Management. Canonical pages are never renamed.
- **Telegram** — personal OpenClaw agent surface (each pilot's agent lives here).
- **Gmail / Google Workspace** — inbound notifications; important items surface into Slack or Notion. Basis stack for mail / calendar / files after v1.1.
- **Obsidian vault** (`/root/obsidian-august/`) — shared + personal knowledge. Project hierarchy: `projects/KRING/Speedbooting/Cosmica/{Speedblocks/Workspace/v1.x, Platform}`. Folder notes use same-name `.md` (never `README.md`). Breadcrumb parents, no orphans, strict tag taxonomy. Read vault governance (SHARED.md, HOME, AGENTS) before writing.
- **GitHub** — Cosmica + agent code. CodeRabbit reviews, Vercel preview deploys, Render production.

Language: Danish default, works in English. Tone: direct, specific, no filler. Direct communication is Danish norm, not rudeness.

## How KRING decides

- **August locks Scope and Solution** for Speedblocks. Building Briefs are his alone to author.
- **Corey locks platform architecture** — migrations, infra cutovers, runtime changes.
- **Decisions log to the Notion PM Tasks DB as they land.** The PM task is the decision record.
- **"Locked"** = committed. **"Draft"** = proposal / WIP. Avoid retired framing (e.g. "Wave 1 / Wave 2").

## The Basis stack (Workspace 1.0 Solution)

Locked for the agent layer across the 3 pilots: Google Workspace (incl. Gemini) · Slack · Notion · OpenClaw (Cosmo + personal OP agent) · Claude · GitHub · Obsidian (+ Syncthing). MS drops off the active stack; the MS → Google cutover runs in v1.1.

## What the agent should never assume about KRING

- Don't assume the stack matches any other startup. Default tools: Notion, Slack, Google Workspace, GitHub, Obsidian, Telegram. Per-pilot OAuth scopes live in TOOLS.md.
- Don't infer Speedblock status from Slack chatter — read the Notion PM Tasks DB.
- Don't write to Obsidian without reading vault governance first. Cosmo's only auto-allowed vault write path is `_guests/cosmo/**`.
- Don't conflate the org with any single person. KRING.md is org layer. The user's own relationship to KRING — their role, their people, their pain — lives in USER.md.

---

## For the agent reading this

- If a user asks a KRING question and the answer isn't in here, say so. Don't extrapolate.
- Canonical framework detail lives in the Notion Master Brief and the `speedblock-master-brief` skill references (`lifecycle.md`, `deliverables.md`, `operating-manual.md`, `construction-brief.md`, `quality-gates.md`, `prototype-rules.md`, `release-metadata.md`, `delivery-format.md`). Go there when this file isn't enough.
- This file is universal and grows. If you learn something stable about KRING, propose an update — don't edit silently.
