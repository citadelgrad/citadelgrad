<div align="center">

# Scott Nixon

<img src="https://avatars.githubusercontent.com/u/168768?v=4" alt="Scott Nixon" width="160" />

**Senior Platform Engineer at Citi**

![Rust](https://img.shields.io/badge/-Rust-2b2b2b?style=flat-square&logo=rust&logoColor=dea584)
![Python](https://img.shields.io/badge/-Python-2b2b2b?style=flat-square&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/-TypeScript-2b2b2b?style=flat-square&logo=typescript&logoColor=3178C6)
![Go](https://img.shields.io/badge/-Go-2b2b2b?style=flat-square&logo=go&logoColor=00ADD8)
![Docker](https://img.shields.io/badge/-Docker-2b2b2b?style=flat-square&logo=docker&logoColor=2496ED)
![Terraform](https://img.shields.io/badge/-Terraform-2b2b2b?style=flat-square&logo=terraform&logoColor=844FBA)
![AWS](https://img.shields.io/badge/-AWS-2b2b2b?style=flat-square&logo=amazonwebservices&logoColor=FF9900)
![GCP](https://img.shields.io/badge/-GCP-2b2b2b?style=flat-square&logo=googlecloud&logoColor=4285F4)
![Claude](https://img.shields.io/badge/-Claude-2b2b2b?style=flat-square&logo=anthropic&logoColor=d4a27f)
![SQLite](https://img.shields.io/badge/-SQLite-2b2b2b?style=flat-square&logo=sqlite&logoColor=63b4f4)

*I build the infrastructure that lets AI agents plan, code, test, review, and ship without turning production into a casino.*

![Experience: 20+ years](https://img.shields.io/static/v1?label=Experience&message=20%2B%20years&color=2b2b2b&style=flat-square&logo=terminal&logoColor=white)
![Focus: Billions of tokens](https://img.shields.io/static/v1?label=AI%20Scale&message=Billions%20of%20tokens&color=2b2b2b&style=flat-square&logo=openai&logoColor=white)
![Followers](https://img.shields.io/github/followers/citadelgrad?style=flat-square&label=GitHub%20Followers&color=2b2b2b&logo=github&logoColor=white)
![Profile Repo Stars](https://img.shields.io/github/stars/citadelgrad/citadelgrad?style=flat-square&label=Profile%20Stars&color=2b2b2b&logo=github&logoColor=white)

[![Website](https://img.shields.io/badge/citadelgrad.co-2b2b2b?style=flat-square&logo=google-chrome&logoColor=white)](https://citadelgrad.co)
[![PAS CLI](https://img.shields.io/badge/PAS%20CLI-pascals--discrete--attractor-2b2b2b?style=flat-square&logo=rust&logoColor=white)](https://github.com/citadelgrad/pascals-discrete-attractor)
[![Reckoner](https://img.shields.io/badge/Reckoner-software%20factory-2b2b2b?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/citadelgrad/reckoner)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Scott%20Nixon-2b2b2b?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/citadelgrad/)
[![X](https://img.shields.io/badge/X-@scottnixonish-2b2b2b?style=flat-square&logo=x&logoColor=white)](https://x.com/scottnixonish)

`Agentic AI Development` · `AI Platform Engineering` · `Software Factories` · `RAG` · `LLM Governance` · `Infrastructure Automation`

</div>

<p align="center">
<a href="#the-agentic-software-factory">Factory</a> · <a href="#core-toolchain">Toolchain</a> · <a href="#building-now">Building Now</a> · <a href="#merged-external-contributions">Merged OSS</a> · <a href="#operating-model">Operating Model</a> · <a href="#writing--proof">Writing</a> · <a href="#connect">Connect</a>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=citadelgrad&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" width="49%" alt="Scott Nixon GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=citadelgrad&layout=compact&theme=transparent&hide_border=true&hide=html,css" width="49%" alt="Scott Nixon top languages" />
</p>

> [!NOTE]
> My current work sits at the intersection of enterprise AI platforms and local-first autonomous development: agent pipelines, repo-level quality gates, governance gateways, and production deployment loops that make AI-generated code reviewable instead of magical.

---

## The Agentic Software Factory

Most AI coding demos stop at “the agent wrote code.” That is the easy part.

The hard part is everything around it: initialization, context, issue tracking, isolated execution, repeated verification, policy checks, fresh-eyes review, pull requests, deploys, and rollback paths. I build that control plane.

```text
idea / issue
   ↓
repo instructions + local skills + agent context
   ↓
PAS CLI pipeline execution
   ↓
Reckoner repo orchestration
   ↓
tests / lint / type checks / security gates
   ↓
reviewable pull request
   ↓
production deployment with evidence
```

This is not “let the bot cook.” It is layered control for high-throughput software work.

---

## Core Toolchain

| Project | Stars | Lang | Role in the factory |
|:--|:--:|:--:|:--|
| [**PAS CLI**](https://github.com/citadelgrad/pascals-discrete-attractor) | ![Stars](https://img.shields.io/github/stars/citadelgrad/pascals-discrete-attractor?style=flat-square&logo=github&logoColor=white) | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) | Graph-driven pipeline runner for AI workflows with backpressure, checkpoints, and verification gates |
| [**Reckoner**](https://github.com/citadelgrad/reckoner) | ![Stars](https://img.shields.io/github/stars/citadelgrad/reckoner?style=flat-square&logo=github&logoColor=white) | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) | Software factory wrapper around PAS: registers repos, runs pipelines, enforces quality loops, opens PRs |
| [**llm-governance-gateway**](https://github.com/citadelgrad/llm-governance-gateway) | ![Stars](https://img.shields.io/github/stars/citadelgrad/llm-governance-gateway?style=flat-square&logo=github&logoColor=white) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | OpenAI-compatible gateway for policy enforcement, PII redaction, tenant routing, rate limiting, and audit logging |
| [**scott-cc**](https://github.com/citadelgrad/scott-cc) | ![Stars](https://img.shields.io/github/stars/citadelgrad/scott-cc?style=flat-square&logo=github&logoColor=white) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | Personal Claude Code plugin: slash commands, specialized agents, and reusable development skills |
| [**vibe-ship-small**](https://github.com/citadelgrad/vibe-ship-small) | ![Stars](https://img.shields.io/github/stars/citadelgrad/vibe-ship-small?style=flat-square&logo=github&logoColor=white) | ![Docs](https://img.shields.io/badge/-Docs-555555?style=flat-square&logo=readthedocs&logoColor=white) | Planning method for AI-assisted development that keeps work small enough to review |
| [**NixonNote**](https://github.com/citadelgrad/nixon-note) | ![Stars](https://img.shields.io/github/stars/citadelgrad/nixon-note?style=flat-square&logo=github&logoColor=white) | ![Local-first](https://img.shields.io/badge/-Local--first-2b2b2b?style=flat-square&logo=sqlite&logoColor=white) | Personal, local-first knowledge system for notes and research |

---

## Building Now

| System | What it is | Why it matters |
|:--|:--|:--|
| **Happy Herbivore Inc** | Plant-based meal planning business and the production systems behind it | Real users, real revenue, real operational constraints |
| **Meal Mentor / GMP** | Subscription backend, mobile API, recipe delivery, and deploy automation | Legacy-to-modern platform work under production pressure |
| **PAS CLI (pascals-discrete-attractor)** | Agent pipeline runner | Makes autonomous workflows repeatable and inspectable |
| **Reckoner** | Software factory over real repos | Turns agent runs into quality-gated PRs |
| **NixonNote** | Local-first personal knowledge system | Keeps private research and notes local, searchable, and useful |
| **Rosco** | GEO/local visibility scorecards for SMBs | Practical AI visibility reporting for local businesses |

---

## Merged External Contributions

Verified merged PRs from public GitHub data. Short list, because contribution sections should not become a landfill.

| Project | Merged work |
|:--|:--|
| [**Biome**](https://github.com/biomejs/biome/pull/10498) | Implemented `useFunctionComponentDefinition`, a React lint rule for consistent function component style |
| [**Colima**](https://github.com/abiosoft/colima/pull/1523) | Added user-provided containerd/buildkit config support |
| [**Colima**](https://github.com/abiosoft/colima/pull/1522) | Added VM customization docs and FAQ updates |
| [**Beads**](https://github.com/gastownhall/beads/pull/1450) | Fixed duplicate children in `bd list --tree` |
| [**Beads**](https://github.com/gastownhall/beads/pull/1286) | Fixed export hash bookkeeping after successful export |
| [**Gastown**](https://github.com/gastownhall/gastown/pull/1137) | Added rig-name mismatch doctor checks |
| [**Gastown**](https://github.com/gastownhall/gastown/pull/1138) | Hardened rig Git URL validation |

---

## Operating Model

I care less about prompts and more about systems that can survive contact with a repo.

| Layer | Practice |
|:--|:--|
| **Context** | `AGENTS.md` / `CLAUDE.md`, project skills, local memory, issue context |
| **Planning** | Small PRs, explicit acceptance criteria, frozen benchmarks, keep-or-revert loops |
| **Execution** | Local agents, PAS CLI pipelines, isolated worktrees, deterministic Makefile targets |
| **Verification** | Tests, lint, type checks, security scans, browser smokes, fresh-eyes review |
| **Governance** | LLM gateway controls, PII redaction, policy checks, audit logs |
| **Operations** | Docker, Kamal, Terraform, Ansible, GitHub Actions, low-cost infra, boring rollbacks |

The point is to make autonomous development boring enough to trust.

---

## Writing & Proof

- [**Portfolio & home**](https://citadelgrad.co) — professional landing page, open-source projects, applications, writing, and contact links
- [**AI Engineering Experience**](https://citadelgrad.co/blog/ai-engineering-experience.html) — practical AI platform, RAG, orchestration, and production agent work
- [**Hermes + Paperclip vs OpenClaw**](https://citadelgrad.co/blog/hermes-vs-openclaw.html) — autonomous business infrastructure, memory systems, and local-first agent operations
- [**The Vibe Coding Manifesto**](https://citadelgrad.co/blog/vibe-coding-manifesto.html) — intuition, feedback loops, and AI-assisted development discipline
- [**So You Wanna Vibe Code**](https://citadelgrad.co/blog/so-you-wanna-vibe-code.html) — levels, tools, mindset, and the plan-delegate-test loop

---

## Connect

- Website: [citadelgrad.co](https://citadelgrad.co)
- GitHub: [@citadelgrad](https://github.com/citadelgrad)
- X: [@scottnixonish](https://x.com/scottnixonish)
- LinkedIn: [Scott Nixon](https://www.linkedin.com/in/citadelgrad/)

---

<div align="center">

**Current thesis:** AI coding gets useful when it becomes an operating system for software delivery, not a chatbot in an editor.

</div>
