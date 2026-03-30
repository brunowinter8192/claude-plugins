# Claude Code Plugin Marketplace

Plugin registry for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Each plugin bundles MCP servers, skills, slash commands, and autonomous subagents into a single installable package.

## Plugins

| Plugin | Description | Repo |
|--------|-------------|------|
| **rag** | Local RAG pipeline — index PDFs and websites, search with hybrid retrieval | [RAG](https://github.com/brunowinter8192/RAG) |
| **searxng** | Web search, URL scraping, and site crawling via local SearXNG instance | [searxng-mcp](https://github.com/brunowinter8192/searxng-mcp) |
| **github-research** | GitHub API tools — search repos, code, issues, PRs, discussions, and releases | [github-MCP](https://github.com/brunowinter8192/github-MCP) |
| **reddit** | Reddit search, browsing, and commenting with autonomous research agent | [Reddit-MCP](https://github.com/brunowinter8192/Reddit-MCP) |
| **arxiv** | ArXiv paper search, metadata retrieval, and PDF download | [Arxiv](https://github.com/brunowinter8192/Arxiv) |
| **gmail** | Gmail search and email reading (read-only, OAuth 2.0) | [GmailMCP](https://github.com/brunowinter8192/GmailMCP) |
| **iterative-dev** | Development workflow engine — structured dev cycle, worker spawning, git automation | [Meta](https://github.com/brunowinter8192/Meta) |

## Installation

```
/plugin marketplace add brunowinter8192/claude-plugins
/plugin install <plugin-name>
```

## License

MIT
