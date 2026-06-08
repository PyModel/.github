<div align="center">

<img src="https://raw.githubusercontent.com/Pythoughts-labs/.github/main/profile/banner.svg" alt="Pythoughts — AI Solutions for Developers Who Live in the Terminal" width="100%" />

### 🧠 AI Solutions for Developers Who Live in the Terminal

**Think first, then code.** We design and ship review-first AI engineering systems — agents that read, audit, and reason about your code before they ever write a line.

[![Website](https://img.shields.io/badge/🌐_Website-pythoughts.com-6366F1?style=for-the-badge&labelColor=1E1B4B)](https://pythoughts.com)
[![Email](https://img.shields.io/badge/📫_Contact-info@pythoughts.com-EC4899?style=for-the-badge&labelColor=1E1B4B)](mailto:info@pythoughts.com)
[![Flagship](https://img.shields.io/badge/⚡_Flagship-Pythinker_Code-F59E0B?style=for-the-badge&labelColor=1E1B4B)](https://github.com/Pythoughts-labs/pythinker-code)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-8B5CF6?style=flat-square&logo=openai&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-10B981?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-0EA5E9?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![ACP](https://img.shields.io/badge/ACP-EF4444?style=flat-square&logo=zedindustries&logoColor=white)
![License](https://img.shields.io/badge/License-Apache_2.0-64748B?style=flat-square&logo=apache&logoColor=white)

</div>

---

## 🏢 Who we are

**Pythoughts is an AI solutions company.** We build practical, production-grade AI engineering tools that fit the way developers actually work. Our focus is a single, opinionated idea: AI should **understand** your codebase before it changes it.

Most AI coding assistants jump straight to generating code. We think that's backwards. Our systems lead with **code review, security scanning, and root-cause diagnosis**, and only make scoped edits once the analysis points at a fix. The repositories in this organization are the building blocks of that work — open source, hackable, and shipped to production.

## 🎯 What we stand for

| | |
| --- | --- |
| 🔍 **Review-first** | Review, secure, and diagnose come *before* code generation — never after. |
| 🖥️ **Terminal-native** | Plan, edit, run, and verify without leaving your shell. Visible, scriptable, auditable. |
| 🧩 **Open & hackable** | Subagents, skills, hooks, and plugins are first-class. Bring your own model and tools. |
| 🔐 **Privacy-respecting** | Prompts go directly to your provider. Telemetry is anonymous and fully optional. |

## 📦 Our work

These repositories are part of the Pythoughts platform — our flagship agent and the tooling that ships it everywhere.

| Repository | Role | Description |
| --- | --- | --- |
| [**pythinker-code**](https://github.com/Pythoughts-labs/pythinker-code) | ⚡ Flagship | The review-first AI engineering agent for the terminal — reviewer, security scanner, debugger, and coder in one shell-native loop. |
| [**homebrew-pythinker**](https://github.com/Pythoughts-labs/homebrew-pythinker) | 🍺 Distribution | Official Homebrew tap for macOS and Linux installs. |
| [**scoop-pythinker**](https://github.com/Pythoughts-labs/scoop-pythinker) | 🪟 Distribution | Official Scoop bucket for Windows installs. |

## 🚀 Get started

```bash
# 🍺 macOS / Linux — Homebrew
brew install Pythoughts-labs/pythinker/pythinker-code

# 🐧 macOS / Linux — curl
curl -fsSL https://pythinker.com/install.sh | bash

# 🪟 Windows — PowerShell
irm https://pythinker.com/install.ps1 | iex

# 🐍 Python fallback
pip install pythinker-code
```

Then launch the interactive session:

```bash
pythinker --version   # confirm install
pythinker             # start the interactive TUI
```

## 🔌 Built on open standards

![ACP](https://img.shields.io/badge/Agent_Client_Protocol-EF4444?style=flat-square)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-0EA5E9?style=flat-square)
![BYOM](https://img.shields.io/badge/Bring_Your_Own_Model-8B5CF6?style=flat-square)

Our agents speak the **Agent Client Protocol (ACP)** for inline use in editors like Zed and JetBrains, and load **Model Context Protocol (MCP)** servers so your existing tools just work. Swap providers and models per session — hosted APIs or fully local models via LM Studio and Ollama. No vendor lock-in.

## 🤝 Contributing

Contributions are warmly welcome — bug reports, pull requests, plugins, skills, and docs all help. Start with the `CONTRIBUTING.md` and `SECURITY.md` in each repository.

> If our tools help you, a ⭐ on the repos goes a long way.

---

<div align="center">

📫 [info@pythoughts.com](mailto:info@pythoughts.com) · 🌐 [pythoughts.com](https://pythoughts.com)

*Built with care for engineers who live in the terminal.*

</div>
