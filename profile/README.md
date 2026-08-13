<div align="center">

<img src="banner.svg" alt="PyModel, review-first AI engineering by Pythoughts" width="100%" />

### Review-first AI engineering for developers who live in the terminal

**Think first, then code.** PyModel is the engineering home of [Pythoughts](https://pythoughts.com): we design and ship AI engineering systems that read, audit, and reason about your code before they ever write a line.

[![Website](https://img.shields.io/badge/Website-pythoughts.com-D4AF37?style=for-the-badge&labelColor=0A0A0C)](https://pythoughts.com)
[![Contact](https://img.shields.io/badge/Contact-info%40pythoughts.com-8A8A93?style=for-the-badge&labelColor=0A0A0C)](mailto:info@pythoughts.com)
[![Flagship](https://img.shields.io/badge/Flagship-Pythinker-E8C766?style=for-the-badge&labelColor=0A0A0C)](https://github.com/PyModel/pythinker-cli)

![Python](https://img.shields.io/badge/Python-26262C?style=flat-square&logo=python&logoColor=D4AF37)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-26262C?style=flat-square&logo=modelcontextprotocol&logoColor=D4AF37)
![ACP](https://img.shields.io/badge/Agent_Client_Protocol-26262C?style=flat-square&logo=zedindustries&logoColor=D4AF37)
![License](https://img.shields.io/badge/License-Apache_2.0-26262C?style=flat-square&logo=apache&logoColor=D4AF37)

</div>

---

## Who we are

**PyModel is where [Pythoughts](https://pythoughts.com), an AI solutions company, builds in the open.** We make production-grade AI engineering tools that fit the way developers actually work, guided by one opinionated idea: AI should understand your codebase before it changes it.

Most AI coding assistants jump straight to generating code. We think that is backwards. Our systems lead with code review, security scanning, and root-cause diagnosis, then make scoped edits once the analysis points at a fix. Every repository in this organization is a building block of that work: open source, hackable, and shipped to production.

## What we stand for

| Principle              | What it means in practice                                                                |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| **Review-first**       | Review, secure, and diagnose come before code generation, never after.                   |
| **Terminal-native**    | Plan, edit, run, and verify without leaving your shell. Visible, scriptable, auditable.  |
| **Open and hackable**  | Subagents, skills, hooks, and plugins are first class. Bring your own model and tools.   |
| **Privacy-respecting** | Prompts go directly to your provider. Telemetry is anonymous and fully optional.         |

## Focus areas

### AI and ML backend SaaS

We build the backend side of AI products: model training and fine-tuning pipelines, deployment and inference APIs, data management, and usage-based service layers. The architectural bar is constant across projects: horizontal scalability, security at every boundary, predictable latency, and honest cost efficiency.

### AI engineering

AI engineering is shipping AI systems with software-engineering rigor. We treat problem formulation, data preparation, model development, deployment, monitoring, and governance as one lifecycle, and we automate that lifecycle with agents and MLOps practice rather than heroics.

### Machine learning

Across supervised, unsupervised, and reinforcement learning, we care about the full path from raw data to evaluated model: preprocessing, feature engineering, model selection, training, validation, and testing, with honest benchmarks and attention to the ethics of what ships.

### Software engineering

Everything above rests on classical engineering discipline: clear lifecycles, tested code, and methodology chosen to fit the work. CLI, web, or service, the same bar applies: simple, reviewable, production-grade.

## Our public work

| Repository | Role | Description |
| --- | --- | --- |
| [pythinker&#8209;cli](https://github.com/PyModel/pythinker-cli) | Flagship | The review-first AI engineering agent: code reviewer, security scanner, root-cause debugger, and code generator in one shell-native loop. |
| [pythinker&#8209;code](https://github.com/PyModel/pythinker-code) | Agent | Terminal coding agent that reads code, edits files, runs tools, and integrates with editors via ACP. |
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

Then confirm the install and launch the interactive session:

```bash
pythinker --version
pythinker
```

## Built on open standards

Our agents speak the **Agent Client Protocol (ACP)** for inline use in editors like Zed and JetBrains, and load **Model Context Protocol (MCP)** servers so your existing tools just work. Swap providers and models per session, hosted APIs or fully local models. No vendor lock-in.

## Contributing

Bug reports, pull requests, plugins, skills, and docs are all welcome. Start with the `CONTRIBUTING.md` and `SECURITY.md` in each repository. If our tools help you, a star on the repos goes a long way.

---

<div align="center">

[info@pythoughts.com](mailto:info@pythoughts.com) · [pythoughts.com](https://pythoughts.com)

_PyModel, by Pythoughts. Built with care for engineers who live in the terminal._

</div>
