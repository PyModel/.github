<div align="center">

<img src="banner.svg?v=4" alt="PyModel, AI, LLM, and machine learning solutions by Pythoughts" width="100%" />

### AI, LLM, and machine learning solutions, built review-first

**Think first, then code.** PyModel is where [Pythoughts](https://pythoughts.com) builds AI, LLM, and machine learning systems in the open, connecting complex data structures to software that runs in production.

[![Website](https://img.shields.io/badge/Website-pythoughts.com-6BA8FF?style=for-the-badge&labelColor=071019)](https://pythoughts.com)
[![Contact](https://img.shields.io/badge/Contact-hello%40pymodel.com-66E2D0?style=for-the-badge&labelColor=071019)](mailto:hello@pymodel.com)
[![Flagship](https://img.shields.io/badge/Flagship-Pythinker--Code-A891FF?style=for-the-badge&labelColor=071019)](https://github.com/PyModel/pythinker-code)

![Python](https://img.shields.io/badge/Python-14273A?style=flat-square&logo=python&logoColor=7CB7FF)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-14273A?style=flat-square&logo=modelcontextprotocol&logoColor=7CB7FF)
![ACP](https://img.shields.io/badge/Agent_Client_Protocol-14273A?style=flat-square&logo=zedindustries&logoColor=7CB7FF)
![License](https://img.shields.io/badge/License-Apache_2.0-14273A?style=flat-square&logo=apache&logoColor=7CB7FF)

</div>

---

## Who we are

**PyModel is a technology company specializing in AI, LLM, and machine learning solutions.** The work spans neural network development and the engineering that puts models into production. Every project answers to the same test: does it connect complex data structures to practical application, and does it hold up under real load.

Most AI coding assistants generate code first and check it later. We build in the opposite order. Our systems start with code review, security scanning, and root-cause diagnosis, and they edit only after the analysis points at a specific fix. The repositories in this organization are the building blocks of that work. They are open source, and they run in production.

## Who we work with

| Audience | What we deliver |
| --- | --- |
| **Business owners** | AI integration for products and operations. We scope the use case, wire LLM capability into your existing systems, and report results you can measure. |
| **Developers** | Terminal-native agents, skills, and orchestration tooling that fit into the workflows you already run. |
| **Data scientists** | Tooling and infrastructure across the ML lifecycle, from data preparation through deployed and monitored models. |

## What we stand for

| Principle              | What it means in practice                                                                |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| **Review-first**       | Review, secure, and diagnose come before code generation, never after.                   |
| **Terminal-native**    | Plan, edit, run, and verify without leaving your shell. Visible, scriptable, auditable.  |
| **Open and hackable**  | Subagents, skills, hooks, and plugins are first class. Bring your own model and tools.   |
| **Privacy-respecting** | Prompts go directly to your provider. Telemetry is anonymous and fully optional.         |

## Focus areas

### AI and ML backend SaaS

We design the backend side of AI products: training and fine-tuning pipelines, inference APIs, data management, and usage metering. Every design is judged on scale, security, latency, and cost, in that order of scrutiny, because a backend that fails any one of them fails the business it serves.

### AI engineering

A good model is a small part of a working AI system. We treat problem formulation, data preparation, evaluation, deployment, and monitoring as one lifecycle, and we automate the parts of it that machines do better than people.

### Machine learning

We build models across supervised, unsupervised, and reinforcement learning, and we measure them without flattery: real benchmarks, held-out validation, and documented failure modes.

### Software engineering

The AI work sits on ordinary engineering discipline. Tested code, small reviewable changes, and methodology chosen to fit the team. A model pipeline earns no exemption from the standards that apply to any other production system.

## Our public work

| Repository | Role | Description |
| --- | --- | --- |
| [pythinker&#8209;code](https://github.com/PyModel/pythinker-code) | Flagship | Terminal coding agent that reads code, edits files, runs tools, and integrates with editors via ACP. |
| [pythinker&#8209;cli](https://github.com/PyModel/pythinker-cli) | Agent | The review-first AI engineering agent: code reviewer, security scanner, root-cause debugger, and code generator in one shell-native loop. |
| [claude&#8209;architect](https://github.com/PyModel/claude-architect) | Orchestration | Delegates coding to isolated CLI agents, freezes what they produce, verifies it independently, and merges only what a human approves. |
| [maestro](https://github.com/PyModel/maestro) | Orchestration | Orchestrator and implementer loop for Claude Code: one model plans, debates, and reviews while another writes the code and proves it works. |
| [designer&#8209;skill](https://github.com/PyModel/designer-skill) | Agent skill | Plug-and-play MCP that gives coding agents UI superpowers. One-line install, zero config. |
| [css&#8209;pro&#8209;tips](https://github.com/PyModel/css-pro-tips) | Agent skill | Validated, Baseline-aware modern CSS skill for AI coding agents. |
| [react&#8209;frontend&#8209;skills](https://github.com/PyModel/react-frontend-skills) | Agent skill | 18 production-grade agent skills for the React ecosystem. |
| [vue3&#8209;best&#8209;practices](https://github.com/PyModel/vue3-best-practices) | Agent skill | Vue 3 best-practice skills, MCP server, and CI. |
| [cinematic&#8209;ui](https://github.com/PyModel/cinematic-ui) | Agent skill | Director-driven web design skill: research a real film, extract its cinematic grammar, build storyboard-first. |
| [watermark&#8209;remover](https://github.com/PyModel/watermark-remover) | Tooling | Find and remove AI provenance signals from files you own: hidden Unicode, token watermarks, and metadata. |
| [hermes&#8209;ui](https://github.com/PyModel/hermes-ui) | Tooling | Self-hosted control plane for Hermes Agent: chat, providers, models, skills, automation, and logs in one dashboard. |

## Get started

```bash
# macOS / Linux, Homebrew
brew install PyModel/pythinker/pythinker-code

# macOS / Linux, curl
curl -fsSL https://pythinker.com/install.sh | bash

# Windows, PowerShell
irm https://pythinker.com/install.ps1 | iex

# Python fallback
pip install pythinker-code
```

Confirm the install, then launch the interactive session:

```bash
pythinker --version
pythinker
```

## Built on open standards

Our agents speak the Agent Client Protocol (ACP) for inline use in editors such as Zed and JetBrains, and they load Model Context Protocol (MCP) servers, so the tools you already use keep working. Providers and models swap per session, hosted or fully local, and nothing in the stack ties you to a single vendor.

## Contributing

Bug reports, pull requests, plugins, skills, and docs are welcome. Each repository carries its own `CONTRIBUTING.md` and `SECURITY.md`, so start there. If our tools help you, star the repos; it helps other engineers find them.

---

<div align="center">

[hello@pymodel.com](mailto:hello@pymodel.com) · [pythoughts.com](https://pythoughts.com)

_PyModel, by Pythoughts. Built for engineers who live in the terminal._

</div>
