## Frederick Hörner

**Full-Stack Developer at [TMT](https://www.tmt.de) · Germany**

I modernise grown PHP/WordPress systems without stopping production – hardened, tested, with AI tooling.
In my free time I'm building a native terminal in Rust.

[freddo.dev](https://freddo.dev)

---

### 🚧 Building now: hefyn

<a href="https://github.com/fHpro0/hefyn">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fHpro0/hefyn/main/docs/screenshots/overview-dark.png">
    <img src="https://raw.githubusercontent.com/fHpro0/hefyn/main/docs/screenshots/overview.png" alt="hefyn: session tree, command blocks and a split screen" width="440" align="right">
  </picture>
</a>

[**hefyn**](https://github.com/fHpro0/hefyn) is a native macOS terminal written in pure Rust on GPUI and
`alacritty_terminal`. It has a session tree, command blocks and a built-in MCP gateway. AI agents
like Claude Code can run commands in the sessions you allow, and everything they read is redacted
first by regex rules, an entropy detector and a local GLiNER model. A Keychain vault lets agents use
secrets without seeing them. *Work in progress.*

`Rust · GPUI · alacritty_terminal · MCP (rmcp) · ONNX/GLiNER`

<br clear="right">

---

### Why this profile looks quiet

A handful of public repositories is not the whole picture. Nearly everything I
build is client work on a company GitLab that you cannot see from here,
so the honest version is the numbers rather than a contribution graph:

| | since 09/2019 |
|---|---|
| Projects I contributed to | **68** |
| As lead or sole developer | **19** |

4 years in the job after an IHK apprenticeship as an IT specialist for
application development, all of it at the same agency — which means I have
had to live with my own decisions for years instead of handing them over at
go-live.

### What that work actually is

Client names omitted on purpose. Happy to walk through any of it.

| Project | My role | Stack |
|---|---|---|
| Menu platform with CO₂ footprint | Lead developer | Astro · Vue 3 · TypeScript · Tailwind CSS · Bun |
| Room booking & device system (e-ink displays) | Sole developer | TypeScript · Astro · Vue 3 · Drizzle ORM · better-auth |
| Digital signage for public spaces | Sole developer, two repositories | Astro · Vue 3 · TypeScript · PHP · WordPress |
| Product finder for a brewery | Lead developer | PHP · WordPress · Vue 3 · SCSS · Custom Post Types |
| Skills matrix for an intranet | Sole developer | PHP · WordPress · Vue 3 · SCSS · REST-API |
| Management platform for a cultural institution | Lead developer since 09/2023 | PHP · WordPress · Vue 3 · TypeScript · Vite |
| Signage CMS & approval workflow | Sole developer | PHP · WordPress · ACF PRO · REST-API · Imagick/GD |
| Regional database of educational offerings | Sole developer | PHP · WordPress · Vue 3 · Custom Post Types · REST-API |
| Corporate website with 3D sections | Relaunch as part of the core team | Astro · Vue 3 · TypeScript · Three.js · Tailwind CSS |
| Calendar and utility services in Go | Sole developer, two services | Go · REST-API · iCal · Docker |
| Content platform for the energy sector | Contributor since 09/2023, two repositories | Nuxt 3/4 · Vue 3 · TypeScript · Pinia · Tailwind CSS |
| GDPR-compliant session handler | Sole developer | PHP · MySQL · REST-API |

### How I work

- Replacing grown PHP/WordPress systems incrementally, in production, without a freeze
- REST APIs and webhooks that hold up: rate limiting, CSP, token hashing, path-traversal protection
- Tests wired into CI, not bolted on afterwards — Vitest, Playwright, PHPUnit
- Docker on my own Debian boxes: deployment, TLS, incident analysis, rollbacks
- LLM tooling that does real work (OpenAI API, LangChain/LangGraph, MCP), not demos

### Stack

**Languages** TypeScript · JavaScript · PHP · Python · Rust · SQL · HTML5 · CSS3 / Sass · Go

**Front end** Vue 3 · Nuxt · Astro · Tailwind CSS · Vite · Pinia · Three.js · React Native

**Back end** Node.js · Bun / Hono · REST APIs · Webhooks · Drizzle ORM · Zod · better-auth · Django / FastAPI

**Data** PostgreSQL · MySQL · SQLite · Supabase · Data modelling and migrations

**Ops** Docker · Linux / Debian · self-managed VPS and root servers · Nginx / Traefik · GitLab CI/CD · GitHub Actions · Git

**Testing** Vitest · Playwright · PHPUnit · Code Reviews · Refactoring of legacy code

**AI / LLM** OpenAI API · Claude Code · AI-assisted software development · Review of agent-generated code · OpenAI API integration in applications

### Public repositories

[**hefyn**](https://github.com/fHpro0/hefyn) — native macOS terminal with a secret-redacting MCP
gateway for AI agents. Rust, GPUI. Work in progress.

[**rmm**](https://github.com/fHpro0/rmm) — WordPress plugin that strips or
rewrites remote metadata so pages stop blocking on third-party requests. PHP.

[**freddo.dev**](https://github.com/fHpro0/freddo.dev) — source of my site.
Astro, TypeScript, SCSS, no JavaScript shipped by default.

[**MANQR**](https://manqr.me) **– cross-platform mobile app** *(private repo, [manqr.me](https://manqr.me))* — Mobile app with a real-time 3D editor and its own API backend: auth via better-auth, data model in PostgreSQL with Drizzle ORM, validation with Zod. Developed for iOS and Android; the Android version has not been published yet. In development.

`Vue 3 · Capacitor · Three.js · Elysia · Drizzle ORM · better-auth · PostgreSQL · Zod`

---

[freddo.dev](https://freddo.dev)

