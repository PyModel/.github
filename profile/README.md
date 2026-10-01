<div align="center">

<img src="banner.svg?v=5" alt="PyModel — AI, LLM, and machine learning solutions" width="100%" />

### Think first, then code.

Open-source tools for coding agents, UI engineering, and verifiable AI workflows.

[Website](https://pymodel.com) · [Explore all repositories](https://github.com/orgs/PyModel/repositories) · [Contact](mailto:hello@pymodel.com)

</div>

## Featured

<a href="https://github.com/PyModel/jev-judge-mcp"><img src="jev-judge-mcp.svg" alt="jev-judge-mcp: typed judgment tools for MCP agents. Model judges, policy decides: auto, review, or escalate." width="100%" /></a>

```sh
uvx --from 'jev-judge-mcp[typesafe]' jev-judge-mcp setup     # verify and store your TypeSafe key
uvx --from 'jev-judge-mcp[typesafe]' jev-judge-mcp install   # add the server to your agents
uvx --from 'jev-judge-mcp[typesafe]' jev-judge-mcp doctor    # check the configuration, offline
```

Works with Claude Code, Claude Desktop, Codex, Cursor, OpenCode, Pi, omp, and Pythinker.

<a href="https://github.com/PyModel/niblet-skill-mcp"><img src="niblet-skill-mcp.svg" alt="niblet-skill-mcp: real screen references and a design skill for coding agents that build UI. Contract, build, check." width="100%" /></a>

```sh
npx skills add PyModel/niblet-skill-mcp --skill niblet -y   # the design skill, no token needed
claude mcp add niblet -- npx -y @pymodel/niblet             # optional: real screen references
```

The skill works alone. The server adds real screens, licensed fonts and icons, and the design system behind a picked screen.

## Projects

### Agent judgment and verification

- [**jev-judge-mcp**](https://github.com/PyModel/jev-judge-mcp): verify, screen, rank, decide, and gate with typed verdicts; policy picks auto, review, or escalate
- [**jev-skill**](https://github.com/PyModel/jev-skill): agent skill for building Jev decisions into your own app
- [**code-max**](https://github.com/PyModel/code-max): requires real test evidence before an agent claims done
- [**done-means-done**](https://github.com/PyModel/done-means-done): a task record and Stop hook that send agents back to unfinished work
- [**defensive-design**](https://github.com/PyModel/defensive-design): proportional failure handling, idempotency, and backpressure for production code

### Coding agents

- [**pythinker-code**](https://github.com/PyModel/pythinker-code): our flagship terminal agent, with editor support over ACP
- [**pythinker-cli**](https://github.com/PyModel/pythinker-cli): review-first shell agent that scans and debugs before it writes
- [**claude-architect**](https://github.com/PyModel/claude-architect): Claude Code delegates to isolated CLI agents, then verifies before you merge
- [**claude-agy-mcp**](https://github.com/PyModel/claude-agy-mcp): Claude Code to Antigravity CLI bridge with model fallback
- [**maestro**](https://github.com/PyModel/maestro): Claude plans and reviews, Codex writes the code

### UI and frontend

- [**niblet-skill-mcp**](https://github.com/PyModel/niblet-skill-mcp): design skill and MCP server that ground agent-built UI in real screens
- [**designer-skill**](https://github.com/PyModel/designer-skill): UI design tools for any coding agent, installed in one line
- [**react-frontend-skills**](https://github.com/PyModel/react-frontend-skills): React 19, Next.js 16, TypeScript, and testing skills
- [**vue3-best-practices**](https://github.com/PyModel/vue3-best-practices): Vue 3, Router, Pinia, and Vitest skills with an MCP server
- [**css-pro-tips**](https://github.com/PyModel/css-pro-tips): Baseline-aware modern CSS guidance, loaded on demand
- [**cinematic-ui**](https://github.com/PyModel/cinematic-ui): web design driven by the visual grammar of a real film

### Agent skills

- [**research-stack-skill**](https://github.com/PyModel/research-stack-skill): one routed research path across Context7, Tavily, and Firecrawl
- [**postgres-skill**](https://github.com/PyModel/postgres-skill): schema, indexing, query tuning, migrations, and RLS
- [**prompt-enhancement-skill**](https://github.com/PyModel/prompt-enhancement-skill): create, critique, and repair prompts for any AI tool
- [**reverse-engineering-skill**](https://github.com/PyModel/reverse-engineering-skill): binary analysis, runtime instrumentation, and protocol work

### Privacy

- [**watermark-remover**](https://github.com/PyModel/watermark-remover): cleaner for hidden Unicode, token watermarks, and C2PA/EXIF metadata in your files

## Work with us

Found a bug or have an idea? Open an issue in the relevant repository. For AI and machine learning work, contact [hello@pymodel.com](mailto:hello@pymodel.com) or visit [pymodel.com](https://pymodel.com).
