# Claude Code Plugin Marketplace

Plugin registry for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Each plugin bundles MCP servers, skills, slash commands, and autonomous subagents into a single installable package.

## Plugins

| Plugin | Description | Repo |
|--------|-------------|------|
| **rag** | Semantic search over indexed documents via MCP (pgvector, Qwen3 embeddings) | [RAG](https://github.com/brunowinter8192/RAG) |
| **github-research** | GitHub API tools - search repos, code, issues, PRs, discussions | [github-MCP](https://github.com/brunowinter8192/github-MCP) |
| **iterative-dev** | Iterative development cycle with code investigation agent | [Meta](https://github.com/brunowinter8192/Meta) |
| **reddit** | Reddit search and analysis (read-only) | [Reddit-MCP](https://github.com/brunowinter8192/Reddit-MCP) |
| **searxng** | Web search and URL scraping via local SearXNG instance | [searxng-mcp](https://github.com/brunowinter8192/searxng-mcp) |

## Installation

```
/plugin marketplace add brunowinter8192/claude-plugins
/plugin install <plugin-name>
```
