# Claude Code Plugin Marketplace

Plugin registry for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Each plugin bundles MCP servers, skills, slash commands, and autonomous subagents into a single installable package.

## Plugins

| Plugin | Description | Repo |
|--------|-------------|------|
| **rag** | RAG system with semantic search, PDF/web indexing pipelines, and subagent evaluation | [RAG](https://github.com/brunowinter8192/RAG) |
| **github-research** | GitHub API tools - search repos, code, issues, PRs, discussions | [github-MCP](https://github.com/brunowinter8192/github-MCP) |
| **iterative-dev** | Development workflow engine — 5-phase cycle, plugin dev tooling, git automation, worker spawning | [Meta](https://github.com/brunowinter8192/Meta) |
| **reddit** | Reddit search and analysis (read-only) | [Reddit-MCP](https://github.com/brunowinter8192/Reddit-MCP) |
| **searxng** | Web search and URL scraping via local SearXNG instance | [searxng-mcp](https://github.com/brunowinter8192/searxng-mcp) |
| **gmail** | Gmail search and read emails (read-only) | [GmailMCP](https://github.com/brunowinter8192/GmailMCP) |
| **arxiv** | ArXiv paper search, metadata, and PDF download (read-only) | [Arxiv](https://github.com/brunowinter8192/Arxiv) |

## Installation

```
/plugin marketplace add brunowinter8192/claude-plugins
/plugin install <plugin-name>
```
