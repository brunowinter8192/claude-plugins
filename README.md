# Claude Code Plugin Marketplace

Plugin registry for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Each plugin bundles CLI tools, skills, slash commands, and autonomous subagents into a single installable package.

## Plugins

| Plugin | Description | Repo |
|--------|-------------|------|
| **rag** | Local RAG pipeline — index PDFs and websites, search with hybrid retrieval | [rag-cli](https://github.com/brunowinter8192/rag-cli) |
| **searxng** | Web search, URL scraping, and site crawling via local SearXNG instance | [searxng-cli](https://github.com/brunowinter8192/searxng-cli) |
| **github-research** | GitHub API tools — search repos, code, issues, PRs, discussions, and releases | [gh-cli](https://github.com/brunowinter8192/gh-cli) |
| **reddit** | Reddit subreddit discovery and post/comment indexing for RAG | [reddit-cli](https://github.com/brunowinter8192/reddit-cli) |
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
