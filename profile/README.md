<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/LaunchApp-Build_→_Launch_→_Grow-white?style=for-the-badge&labelColor=000000&color=ffffff">
    <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/LaunchApp-Build_→_Launch_→_Grow-black?style=for-the-badge&labelColor=ffffff&color=000000">
    <img alt="LaunchApp" src="https://img.shields.io/badge/LaunchApp-Build_→_Launch_→_Grow-black?style=for-the-badge">
  </picture>
</p>

<h3 align="center">Streamline the process for founders to launch businesses<br/>and for businesses to grow and manage themselves.</h3>

<p align="center">
  <a href="https://github.com/launchapp-dev/ao">AO Engine</a> · <a href="https://github.com/launchapp-dev/ao-dashboard">Dashboard</a> · <a href="https://github.com/launchapp-dev/ao-docs">Docs</a> · <a href="https://github.com/launchapp-dev/ao-skills">Skills</a> · <a href="https://github.com/launchapp-dev/design-system">Design System</a>
</p>

---

### The Mission

LaunchApp eliminates the gap between **"I have an idea"** and **"I have a running business."** We build the tools, templates, and infrastructure that let founders launch fast — and the autonomous systems that keep those businesses shipping, improving, and scaling without burning out.

---

### What We Build

<table>
<tr>
<td width="50%" valign="top">

**AO — Autonomous Orchestrator**

A Rust-based daemon that runs your engineering org while you sleep. Define agents, workflows, and quality gates in YAML. AO dispatches AI models to plan, code, review, test, and merge — 24/7.

- Multi-phase pipelines with PM/EM review loops
- Multi-model routing with automatic fallback
- Git worktree isolation for parallel work
- Self-healing daemon that never stops
- Domain-agnostic — orchestrates code, media, data, and more

</td>
<td width="50%" valign="top">

**LaunchApp Templates**

Production SaaS starters across 4 frameworks — built and maintained by AO.

- **Next.js** — App Router + React 19
- **Nuxt** — Vue 3 + Nitro
- **SvelteKit** — Svelte 5 + SSR
- **React Router 7** — Flagship full-stack template
- Web + Mobile monorepo support
- Auth, billing, email, storage, i18n — all included

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Launchpad BaaS**

Modular backend SDK with 13+ composable packages:

`@launchpad/auth` · `@launchpad/db` · `@launchpad/storage` · `@launchpad/payments` · `@launchpad/realtime` · `@launchpad/push` · `@launchpad/cms` · `@launchpad/workflows` · `@launchpad/ai` · `@launchpad/analytics` · `@launchpad/identity` · `@launchpad/offline` · `@launchpad/testing`

Pick what you need. Own your backend. No vendor lock-in.

</td>
<td width="50%" valign="top">

**StoryForge**

AI media production pipeline orchestrated by AO:

- World-building with persistent character memory
- Script writing with plot continuity enforcement
- Image generation (Nano Banana, FLUX)
- Voice synthesis (ElevenLabs, Fish Audio)
- Music and SFX composition
- Episode assembly and human review gates

Same daemon. Same YAML. Same MCP architecture. Different vertical.

</td>
</tr>
</table>

---

### The Ecosystem

| Project | Description | Stack |
|:--------|:-----------|:------|
| **AO** | Autonomous orchestration engine | Rust, 16 crates |
| **AO Dashboard** | Fleet monitoring desktop app | Tauri 2 + React 19 |
| **AO Skills** | Workflow packs (testing, security, devops) | YAML + Claude |
| **AO Starter** | Project scaffolding CLI | Node.js |
| **LaunchApp Templates** | SaaS starters across 4 frameworks | TypeScript, React Router 7, Next.js, Nuxt, SvelteKit |
| **Launchpad BaaS** | Modular backend SDK (13+ packages) | TypeScript, Hono, Drizzle, PostgreSQL |
| **Design System** | Component library | Radix UI + Tailwind CSS 4 |
| **StoryForge** | Media production pipeline | PostgreSQL, MCP servers, multi-model AI |

---

### By the Numbers

<table>
<tr>
<td align="center"><strong>180+</strong><br/><sub>PRs merged autonomously<br/>in AO's first week</sub></td>
<td align="center"><strong>4</strong><br/><sub>SaaS frameworks<br/>built by AO</sub></td>
<td align="center"><strong>13+</strong><br/><sub>Launchpad SDK<br/>packages</sub></td>
<td align="center"><strong>6+</strong><br/><sub>daemons running<br/>24/7</sub></td>
<td align="center"><strong>300+</strong><br/><sub>pipeline use cases<br/>across 30 verticals</sub></td>
</tr>
</table>

---

### The Stack

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxt.js&logoColor=white" alt="Nuxt" />
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Tauri-FFC131?style=flat-square&logo=tauri&logoColor=black" alt="Tauri" />
  <img src="https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white" alt="Hono" />
  <img src="https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black" alt="Drizzle" />
</p>

---

### The Vision

**Phase 1** — Prove AO can autonomously build and maintain production codebases *(done)*
<br/>**Phase 2** — Sell templates and launch AO Pro *(active)*
<br/>**Phase 3** — AO Enterprise: on-prem, SSO, fleet management, SLA support
<br/>**Phase 4** — LaunchApp Cloud: hosted AO + Launchpad BaaS, one-click deploy
<br/>**Phase 5** — Ecosystem: third-party workflows, skill packs, template marketplace

---

<p align="center">
  <strong>Launch fast. Grow autonomously. Scale with AI.</strong>
</p>
