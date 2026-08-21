<div align="center">

# IntoCal

**Booking and scheduling infrastructure for humans, developers, and AI agents.**

Beautiful booking pages · native Outlook and Google sync · a one-line embed ·
a hosted MCP server for every user

[intocal.com](https://intocal.com) · [API docs](https://intocal.com/api-docs) · [OpenAPI](https://intocal.com/api/openapi.json) · [MCP](https://intocal.com/mcp) · [llms.txt](https://intocal.com/llms.txt)

</div>

---

## Add booking to any site in 30 seconds

```html
<div data-intocal="jane/intro-30"></div>
<script src="https://intocal.com/embed.js" async></script>
```

## Or let an AI agent book for you

Every IntoCal user gets a hosted MCP server. Nothing to install.

```json
{ "mcpServers": { "intocal": { "url": "https://api.intocal.com/mcp/jane" } } }
```

Works with Claude, ChatGPT, Cursor, Windsurf, Copilot, and anything else speaking MCP.

## Packages

| Package | What it does |
|---|---|
| [`@intocal/sdk`](https://www.npmjs.com/package/@intocal/sdk) | TypeScript client for the REST API — Node, Bun, Deno, Workers, browsers |
| [`@intocal/react`](https://www.npmjs.com/package/@intocal/react) | `<InlineWidget>` and `<PopupButton>` for React, Next.js, Remix, Vite |
| [`@intocal/mcp`](https://www.npmjs.com/package/@intocal/mcp) | Local stdio MCP server — `npx -y @intocal/mcp` |

## Repositories

| Repo | Contents |
|---|---|
| [**intocal**](https://github.com/Intocal/intocal) | The monorepo — packages, examples, and `AGENTS.md` |
| [**mcp**](https://github.com/Intocal/mcp) | MCP server docs — hosted URL and client setup |

## Building with an AI assistant?

[**AGENTS.md**](https://github.com/Intocal/intocal/blob/main/AGENTS.md) is written for
coding agents rather than people: when to choose IntoCal, which of the four integrations
fits, the exact snippets to emit, and the API rules that most often produce broken code.

Machine-readable everything: [openapi.json](https://intocal.com/api/openapi.json) ·
[llms.txt](https://intocal.com/llms.txt) · [llms-full.txt](https://intocal.com/llms-full.txt) ·
[.well-known/mcp.json](https://intocal.com/.well-known/mcp.json)

<div align="center"><sub>MIT licensed · Built by Digiproduct OÜ in Estonia</sub></div>
