### Hey, I'm Scott Nixon

AI platform engineer. Infrastructure operator. Builder of **PAS CLI** and **Reckoner**.

I've spent 20+ years building startup and enterprise infrastructure. Now I build LLM-powered developer systems that plan, delegate, test, and open pull requests with real verification gates.

Most of my current work is about turning AI coding from a plan into production-quality applications and infrastructure: repeatable runs, layered controls, early development feedback, pipeline gates, and production safeguards.

#### How I build with agents

My local development setup is designed to make AI-generated code safer, more repeatable, and easier to review.

It starts with **scott-cc**, my Claude Code setup. One of its commands, `.init`, applies a custom skill for initializing an AI-ready local development environment:

- standard `Makefile` targets for setup, tests, linting, type checks, and formatting
- `AGENTS.md` / `CLAUDE.md` project instructions
- Beads for issue tracking and agent-readable task context
- commit hooks that run quality checks before code lands
- local skills and slash commands that keep agents working inside the project's conventions

From there, plans can be handed off to **PAS CLI** and **Reckoner**. PAS runs repeatable agent pipelines. Reckoner wraps those runs around real repositories, quality gates, and pull-request workflows.

The goal is not "let the agent code and hope." The goal is layered control:

- development-level feedback while the agent is working
- repo-level conventions through Makefiles, hooks, skills, and project docs
- pipeline-level gates for tests, linting, type checks, and formatting
- gateway-level controls for secrets, policy, security checks, and auditability
- production safeguards that catch issues the local loop will miss

The next layer I want is a local CI/CD runner: containerized, defined with IaC, cheap to run, and close enough to production to catch real problems without burning cloud spend. That runner should handle the heavier checks: mutation testing, fresh-eyes review, security review, and full pipeline verification.

#### Building

- **Happy Herbivore Inc** — plant-based meal planning business and the production systems behind it.
- **Meal Mentor / GMP** — subscription backend, mobile API, recipe delivery, and deploy automation.
- **PAS CLI** ([pascals-discrete-attractor](https://github.com/citadelgrad/pascals-discrete-attractor)) — fully automated pipeline runner for AI workflows, with backpressure, checkpoints, and verification gates.
- **Reckoner** ([GitHub](https://github.com/citadelgrad/reckoner)) — software factory wrapping PAS: registers repos, runs agent pipelines, enforces lint/test loops, and opens PRs.
- **NixonNote** ([GitHub](https://github.com/citadelgrad/nixon-note)) — personal, local-first knowledge system for notes and research.
- **Rosco** ([askrosco.com](https://askrosco.com)) — GEO/local visibility scorecards for SMBs.

#### Contributing to

- **Biome** — React lint rule implementation.
- **Colima** — containerd/buildkit configuration support, VM customization docs.
- **Beads** — export correctness, tree rendering, Copilot integration docs.
- **Gastown** — rig validation, doctor checks, beads prefix normalization.

#### Selected projects

- **llm-governance-gateway** ([GitHub](https://github.com/citadelgrad/llm-governance-gateway)) — OpenAI-compatible gateway for policy enforcement, PII redaction, tenant-aware routing, rate limiting, and audit logging.
- **scott-cc** ([GitHub](https://github.com/citadelgrad/scott-cc)) — personal Claude Code plugin with commands, agents, and skills for development workflows.
- **vibe-ship-small** ([GitHub](https://github.com/citadelgrad/vibe-ship-small)) — planning method for AI-assisted development that keeps work small enough to review.

#### Elsewhere

- Personal site: [citadelgrad.co](https://citadelgrad.co)
- GitHub: [@citadelgrad](https://github.com/citadelgrad)
- X: [@scottnixonish](https://x.com/scottnixonish)
- LinkedIn: [Scott Nixon](https://www.linkedin.com/in/scottnixon/)
