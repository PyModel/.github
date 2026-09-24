<div align="center">

<img src="banner.svg?v=5" alt="PyModel — AI, LLM, and machine learning solutions" width="100%" />

### Think first, then code.

Open-source tools for coding agents, UI engineering, and verifiable AI workflows.

[Website](https://pymodel.com) · [Explore all repositories](https://github.com/orgs/PyModel/repositories) · [Contact](mailto:hello@pymodel.com)

</div>

## New: jev-judge-mcp

[**jev-judge-mcp**](https://github.com/PyModel/jev-judge-mcp) gives your coding agent eleven typed judgment tools backed by TypeSafe's Jev model: `verify`, `screen`, `find`, `classify`, `rerank`, `decide`, `compare`, `extract`, `review`, `gate`, and `score`. The agent passes in evidence and a question with a fixed set of answers. Jev returns probabilities, usually in under a second, and policy maps them to `auto`, `review`, or `escalate`.

![GitHub stars for jev-judge-mcp](https://img.shields.io/github/stars/PyModel/jev-judge-mcp?style=flat-square&label=stars&color=2E8FE8) ![PyPI version of jev-judge-mcp](https://img.shields.io/pypi/v/jev-judge-mcp?style=flat-square&label=pypi&color=2E8FE8)

```sh
uvx --from 'jev-judge-mcp[typesafe]' jev-judge-mcp setup     # verify your TypeSafe key, then store it
uvx --from 'jev-judge-mcp[typesafe]' jev-judge-mcp install   # add the server to your agents
uvx --from 'jev-judge-mcp[typesafe]' jev-judge-mcp doctor    # check the configuration, offline
```

Works with Claude Code, Claude Desktop, Codex, Cursor, OpenCode, Pi, omp, and Pythinker.

## Most starred projects

Every PyModel project with four or more stars, most starred first.

| Project | Type | What it does | Stars |
| --- | --- | --- | --- |
| [designer-skill](https://github.com/PyModel/designer-skill) | MCP server | Gives coding agents UI design tools through an installable MCP server. | ![GitHub stars for designer-skill](https://img.shields.io/github/stars/PyModel/designer-skill?style=flat-square&label=stars&color=2E8FE8) |
| [claude-architect](https://github.com/PyModel/claude-architect) | Orchestrator | Delegates coding to isolated CLI agents, then verifies their work before a human approves the merge. | ![GitHub stars for claude-architect](https://img.shields.io/github/stars/PyModel/claude-architect?style=flat-square&label=stars&color=2E8FE8) |
| [css-pro-tips](https://github.com/PyModel/css-pro-tips) | Skill | Brings modern, Baseline-aware CSS guidance to AI coding agents. | ![GitHub stars for css-pro-tips](https://img.shields.io/github/stars/PyModel/css-pro-tips?style=flat-square&label=stars&color=2E8FE8) |
| [jev-judge-mcp](https://github.com/PyModel/jev-judge-mcp) | MCP server | Gives agents typed judgment tools that return `auto`, `review`, or `escalate`. | ![GitHub stars for jev-judge-mcp](https://img.shields.io/github/stars/PyModel/jev-judge-mcp?style=flat-square&label=stars&color=2E8FE8) |
| [niblet-skill-mcp](https://github.com/PyModel/niblet-skill-mcp) | MCP server | Grounds agent-built interfaces in real product screens with a design skill and MCP server. | ![GitHub stars for niblet-skill-mcp](https://img.shields.io/github/stars/PyModel/niblet-skill-mcp?style=flat-square&label=stars&color=2E8FE8) |
| [pythinker-code](https://github.com/PyModel/pythinker-code) | Coding agent | Runs an AI coding agent in your terminal and integrates with editors through ACP. | ![GitHub stars for pythinker-code](https://img.shields.io/github/stars/PyModel/pythinker-code?style=flat-square&label=stars&color=2E8FE8) |
| [react-frontend-skills](https://github.com/PyModel/react-frontend-skills) | Skill | Provides agent skills for React, Next.js, TypeScript, testing, and frontend architecture. | ![GitHub stars for react-frontend-skills](https://img.shields.io/github/stars/PyModel/react-frontend-skills?style=flat-square&label=stars&color=2E8FE8) |
| [pythinker-cli](https://github.com/PyModel/pythinker-cli) | Coding agent | Reviews, scans, and debugs before it writes code, all in one shell-native loop. | ![GitHub stars for pythinker-cli](https://img.shields.io/github/stars/PyModel/pythinker-cli?style=flat-square&label=stars&color=2E8FE8) |
| [watermark-remover](https://github.com/PyModel/watermark-remover) | Tool | Finds and removes AI provenance signals, such as hidden Unicode and metadata, from files you own. | ![GitHub stars for watermark-remover](https://img.shields.io/github/stars/PyModel/watermark-remover?style=flat-square&label=stars&color=2E8FE8) |
| [claude-agy-mcp](https://github.com/PyModel/claude-agy-mcp) | MCP server | Lets Claude Code delegate heavy tasks to the Antigravity CLI with model routing and session continuity. | ![GitHub stars for claude-agy-mcp](https://img.shields.io/github/stars/PyModel/claude-agy-mcp?style=flat-square&label=stars&color=2E8FE8) |
| [code-max](https://github.com/PyModel/code-max) | Skill | Makes a coding agent verify before it claims done, with evidence-backed completion reports. | ![GitHub stars for code-max](https://img.shields.io/github/stars/PyModel/code-max?style=flat-square&label=stars&color=2E8FE8) |
| [done-means-done](https://github.com/PyModel/done-means-done) | Skill | Keeps an agent working until a validator confirms every obligation in its task record is met. | ![GitHub stars for done-means-done](https://img.shields.io/github/stars/PyModel/done-means-done?style=flat-square&label=stars&color=2E8FE8) |

## Start with Pythinker Code

[Pythinker Code](https://github.com/PyModel/pythinker-code) is our flagship terminal agent. It reads a codebase, edits files, runs tools, and connects to editors through the Agent Client Protocol. Its repository has the current install instructions and examples.

## Work with us

Found a bug or have an idea? Open an issue in the relevant repository. For AI and machine learning work, contact [hello@pymodel.com](mailto:hello@pymodel.com) or visit [pymodel.com](https://pymodel.com).
