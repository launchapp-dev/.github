# LaunchApp

**We build autonomous production systems.**

AO is a daemon that runs your engineering org while you sleep. Define agents, workflows, and quality gates in YAML. AO dispatches AI models to plan, code, review, test, and merge — 24/7, without human intervention.

Software was the first use case. It's not the last.

---

### What AO Does

```
Task in  →  Daemon picks it up  →  Worktree created  →  Agent writes code
         →  PM reviews quality  →  EM reviews security  →  Tests pass
         →  PR merged  →  You wake up to shipped features
```

- **YAML-defined teams** — Your engineering org is a config file, not a headcount
- **Local-first, BYOK** — Your machine, your API keys, your code never leaves your network
- **Multi-model routing** — Claude, GPT, Gemini, and more with automatic fallback chains
- **Git worktree isolation** — Every task gets a real branch, not a cloud sandbox
- **PM/EM review loops** — Agents don't just code. They review, reject, and approve.
- **Self-healing** — Rate limited? Switches providers. Agent crashed? Daemon restarts it.
- **Domain-agnostic** — The same architecture orchestrates software, media production, data pipelines, and 300+ workflow types across 30 verticals

### What We've Shipped With AO

- **180+ PRs merged autonomously** in AO's first week of operation across 4 SaaS frameworks
- **StoryForge** — A media production pipeline (world-building, scripting, image generation, voice synthesis, music, video assembly) orchestrated by the same daemon
- **Design system** — Bootstrapped by AO, now used across all our products
- **6 daemons running 24/7** managing our entire portfolio

### The Ecosystem

| Project | What It Is |
|---------|-----------|
| **AO** | Autonomous orchestration engine (Rust, 16 crates) |
| **LaunchApp Templates** | SaaS starters for Next.js, Nuxt, SvelteKit, React Router — built and maintained by AO |
| **Launchpad BaaS** | Modular backend SDK (auth, db, storage, payments, realtime, and more) |
| **Design System** | Radix + Tailwind component library |
| **StoryForge** | AI media production pipeline |
| **AO Dashboard** | Fleet monitoring (Tauri + React) |
| **AO Skills** | Workflow packs for testing, security, devops, and framework-specific optimization |

### The Stack

**Rust** for the orchestration engine. **TypeScript** for the product ecosystem. **PostgreSQL + Drizzle** for data. **React Router 7, Next.js, Nuxt, SvelteKit** for templates. **Hono** for APIs. **Tailwind CSS 4** for styling. **Tauri 2** for desktop apps.

### Why AO Is Different

Every AI coding tool on the market builds a better individual coder. AO builds the organization around the coders.

Cursor is an IDE. Devin is a cloud agent. AO is a **local-first, self-healing, domain-agnostic production system** that runs entire workflows autonomously — from requirements through merge, across any domain, 24/7.

No other tool orchestrates PM/EM review loops, routes across 6+ LLM providers with automatic fallback, manages fleet-wide operations across 50+ repos, and handles non-code production work. AO does all of this from a single YAML config.

---

<p align="center">
  <b>Define your team in YAML. Ship while you sleep.</b>
</p>
