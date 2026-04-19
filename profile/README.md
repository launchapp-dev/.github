<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/LAUNCHAPP-ffffff?style=for-the-badge&labelColor=000000">
    <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/LAUNCHAPP-000000?style=for-the-badge&labelColor=ffffff">
    <img alt="LaunchApp" src="https://img.shields.io/badge/LAUNCHAPP-000000?style=for-the-badge">
  </picture>
</p>

<h3 align="center">Autonomous production systems for founders who ship.</h3>

<p align="center">
  <a href="https://github.com/launchapp-dev/ao">Animus install only</a>
  · <a href="https://github.com/launchapp-dev/animus-cli">Animus CLI</a>
  · <a href="https://github.com/launchapp-dev/ao-dashboard">Dashboard</a>
  · <a href="https://github.com/launchapp-dev/ao-docs">Docs</a>
  · <a href="https://github.com/launchapp-dev/ao-skills">Skills</a>
  · <a href="https://github.com/launchapp-dev/design-system">Design System</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/open_source-36+_repos-blue?style=flat-square" alt="Open Source" />
  <img src="https://img.shields.io/badge/engine-Rust-orange?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/ecosystem-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="MIT" />
</p>

---

<br/>

## Animus — The Autonomous Orchestrator

Animus is an orchestation platform that runs autonomous production workflows while you sleep. Define agents, workflows, and quality gates in YAML. AO dispatches AI models to plan, code, review, test, and merge — 24/7, without human intervention.

**Software was the first use case. It's not the last.**

```
                    ┌─────────────────────────────────────────────────────┐
                    │                   Animus DAEMON (24/7)              │
                    ├─────────────────────────────────────────────────────┤
                    │                                                     │
  Task In ─────►    │  Worktree ──► Agent Writes Code ──► Tests Pass      │
                    │      │                                  │           │
                    │      ▼                                  ▼           │
                    │  PM Reviews Quality            EM Reviews Security  │
                    │      │                                  │           │
                    │      ▼                                  ▼           │
                    │  Quality Gates ──────────────► PR Merged to Main    │
                    │                                                     │
                    └─────────────────────────────────────────────────────┘
```

<br/>

### Open Source Repos

<table>
<tr>
<td width="50%" valign="top">

#### Animus Core

| Repo | Description |
|:-----|:-----------|
| [`animus`](https://github.com/launchapp-dev/ao) | Install script and entry point |
| [`animus-cli`](https://github.com/launchapp-dev/animus-cli) | The orchestration engine (Rust) |
| [`animus-projects`](https://github.com/launchapp-dev/ao-projects) | Task and requirements management |
| [`animus-fleet`](https://github.com/launchapp-dev/ao-fleet) | Fleet control plane for multi-project orchestration |
| [`animus-dashboard`](https://github.com/launchapp-dev/ao-dashboard) | Fleet monitoring desktop app (Tauri + React) |
| [`animus-docs`](https://github.com/launchapp-dev/ao-docs) | Documentation |

</td>
<td width="50%" valign="top">

#### Animus Skills & Packs

| Repo | Description |
|:-----|:-----------|
| [`animus-skills`](https://github.com/launchapp-dev/ao-skills) | Claude integration skills |
| [`animus-core-packs`](https://github.com/launchapp-dev/ao-core-packs) | Core workflow packs |
| [`animus-starter`](https://github.com/launchapp-dev/ao-starter) | `create-ao` scaffolding CLI |
| [`animus-skill-testing`](https://github.com/launchapp-dev/ao-skill-testing) | Automated test generation |
| [`animus-skill-security`](https://github.com/launchapp-dev/ao-skill-security) | Security scanning and auditing |
| [`animus-skill-devops`](https://github.com/launchapp-dev/ao-skill-devops) | CI/CD and deployment |
| [`animus-workflow-examples`](https://github.com/launchapp-dev/ao-workflow-examples) | Real-world workflow examples |

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Animus Fleet Tools

| Repo | Description |
|:-----|:-----------|
| [`animus-fleet-pack`](https://github.com/launchapp-dev/ao-fleet-pack) | Conductor, watchdog, syncer agents |
| [`animus-fleet-tools`](https://github.com/launchapp-dev/ao-fleet-tools) | Fleet monitoring shell tools |
| [`animus-examples`](https://github.com/launchapp-dev/ao-examples) | Starter YAML configs |
| [`animus-skill-nextjs`](https://github.com/launchapp-dev/ao-skill-nextjs) | Next.js workflow optimization |
| [`animus-skill-nuxt`](https://github.com/launchapp-dev/ao-skill-nuxt) | Nuxt workflow optimization |
| [`animus-skill-sveltekit`](https://github.com/launchapp-dev/ao-skill-sveltekit) | SvelteKit workflow optimization |
| [`animus-skill-react-router`](https://github.com/launchapp-dev/ao-skill-react-router) | React Router workflow optimization |

</td>
<td width="50%" valign="top">

#### Libraries & Tools

| Repo | Description |
|:-----|:-----------|
| [`design-system`](https://github.com/launchapp-dev/design-system) | Radix UI + Tailwind CSS 4 components |
| [`worktree-manager`](https://github.com/launchapp-dev/worktree-manager) | AI-powered parallel dev with git worktrees |
| [`ai-model-registry`](https://github.com/launchapp-dev/ai-model-registry) | MCP server for AI model metadata |
| [`create-launchapp`](https://github.com/launchapp-dev/create-launchapp) | Project launcher CLI |
| [`figma-tailwind-plugin`](https://github.com/launchapp-dev/figma-tailwind-plugin) | Figma to Tailwind React components |
| [`launchpad-db-engine`](https://github.com/launchapp-dev/launchpad-db-engine) | Database engine with multi-tenancy |

</td>
</tr>
</table>

<br/>

---

<br/>

## What Makes Animus Different

<table>
<tr>
<td align="center" width="33%">
<br/>
<strong>YAML-Defined Teams</strong>
<br/><br/>
<sub>Your engineering org is a config file, not a headcount. Define agents, workflows, phases, and quality gates declaratively.</sub>
<br/><br/>
</td>
<td align="center" width="33%">
<br/>
<strong>Local-First, BYOK</strong>
<br/><br/>
<sub>Your machine. Your API keys. Your code never leaves your network. No cloud lock-in. Standard git repos.</sub>
<br/><br/>
</td>
<td align="center" width="33%">
<br/>
<strong>Multi-Model Routing</strong>
<br/><br/>
<sub>Claude, GPT, Gemini, and more with automatic fallback chains. Rate limited? animus switches providers silently.</sub>
<br/><br/>
</td>
</tr>
<tr>
<td align="center" width="33%">
<br/>
<strong>PM/EM Review Loops</strong>
<br/><br/>
<sub>Agents don't just code. A PM reviews quality. An EM reviews security. Bad PRs get rejected before merge.</sub>
<br/><br/>
</td>
<td align="center" width="33%">
<br/>
<strong>Self-Healing Daemon</strong>
<br/><br/>
<sub>Agent crashed? Daemon restarts it. Model rate-limited? Switches provider. Runs 24/7 with watchdog.</sub>
<br/><br/>
</td>
<td align="center" width="33%">
<br/>
<strong>Domain-Agnostic</strong>
<br/><br/>
<sub>Same architecture orchestrates code, media, data, legal, healthcare — 300+ pipeline types across 30 verticals.</sub>
<br/><br/>
</td>
</tr>
</table>

<br/>

---

<br/>

## Coming Soon

<table>
<tr>
<td width="50%" valign="top">

#### LaunchApp Templates `private — coming soon`

Production SaaS starters across 4 frameworks, built and maintained by animus:

- **React Router 7** — Flagship full-stack template
- **Next.js** — App Router + React 19
- **Nuxt** — Vue 3 + Nitro
- **SvelteKit** — Svelte 5 + SSR

Auth, billing, email, storage, i18n, teams — all included. Web + mobile monorepo support.

</td>
<td width="50%" valign="top">

#### Launchpad BaaS `private — coming soon`

Modular backend SDK with 13+ composable packages:

`@launchpad/auth` · `@launchpad/db` · `@launchpad/storage` · `@launchpad/payments` · `@launchpad/realtime` · `@launchpad/push` · `@launchpad/cms` · `@launchpad/workflows` · `@launchpad/ai` · `@launchpad/analytics` · `@launchpad/identity` · `@launchpad/offline` · `@launchpad/testing`

Pick what you need. Own your backend. Zero vendor lock-in.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### StoryForge `private — coming soon`

AI media production pipeline orchestrated by Animus. Proof that the architecture generalizes beyond code:

- World-building with persistent character memory
- Script writing with plot continuity enforcement
- Image, voice, music, and SFX generation
- Episode assembly with human review gates

Same daemon. Same YAML. Same MCP. Different vertical.

</td>
<td width="50%" valign="top">

#### Animus Cloud `planned`

Hosted Animus orchestration — no CLI setup required:

- Cloud-managed daemons
- Team collaboration and fleet dashboards
- Usage-based pricing
- One-click template deployment
- API access for CI/CD integration

*From "I have an idea" to "running business" in one click.*

</td>
</tr>
</table>

<br/>

---

<br/>

## By the Numbers

<table>
<tr>
<td align="center" width="20%">
<h2>180+</h2>
<sub>PRs merged autonomously<br/>in Animus's first week</sub>
</td>
<td align="center" width="20%">
<h2>16</h2>
<sub>Rust crates in<br/>the Animus engine</sub>
</td>
<td align="center" width="20%">
<h2>36+</h2>
<sub>open source<br/>repositories</sub>
</td>
<td align="center" width="20%">
<h2>4</h2>
<sub>SaaS frameworks<br/>built by Animus</sub>
</td>
<td align="center" width="20%">
<h2>300+</h2>
<sub>pipeline use cases<br/>across 30 verticals</sub>
</td>
</tr>
</table>

<br/>

---

<br/>

## The Stack

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Nuxt-00DC82?style=for-the-badge&logo=nuxt.js&logoColor=white" alt="Nuxt" />
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white" alt="Svelte" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Tauri-FFC131?style=for-the-badge&logo=tauri&logoColor=black" alt="Tauri" />
  <img src="https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white" alt="Hono" />
  <img src="https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black" alt="Drizzle" />
</p>

<br/>

---

<br/>

## Roadmap

```
  DONE          ACTIVE       NEXT                PLANNED                FUTURE
  ─────         ──────       ────                ───────                ──────
  Phase 1       Phase 2      Phase 3             Phase 4                Phase 5
  Prove Animus  Templates    Animus Enterprise   LaunchApp Cloud        Ecosystem
               + Animus Pro  on-prem, SSO        hosted Animus + BaaS   marketplace
                              fleet mgmt         one-click deploy       3rd party packs
  ✓ 180+       ◆ SaaS        ○ RBAC + audit      ○ Cloud daemons        ○ Skill store
    PRs         templates    logs
  ✓ 6+         ◆ Workflow    ○ SLA support       ○ Team dashboards      ○ Template
    daemons     packs                                                   marketplace
  ✓ Design     ◆ Animus Pro  ○ Enterprise        ○ Usage-based          ○ Plugin
    system       beta         licensing            pricing              ecosystem
```

<br/>

---

<p align="center">
  <strong>Define your team in YAML. Ship while you sleep.</strong>
  <br/><br/>
  <a href="https://github.com/launchapp-dev/ao">Get Started with Animus</a>
  · <a href="https://github.com/launchapp-dev/ao-docs">Read the Docs</a>
  · <a href="https://github.com/launchapp-dev/ao-workflow-examples">See Examples</a>
</p>
