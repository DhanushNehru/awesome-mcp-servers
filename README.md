# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Model Context Protocol (MCP) servers, tools, SDKs, and resources.

[Model Context Protocol (MCP)](https://modelcontextprotocol.io/docs/getting-started/intro) is an open standard introduced by Anthropic that enables AI assistants like Claude to securely connect with local and remote resources. It acts as the "USB-C for AI," providing a universal way to expose tools and context to Large Language Models.

---

## Contents

- [Core / Official](#core--official)
- [Development & DevOps](#development--devops)
- [Databases & Data Management](#databases--data-management)
- [Web & Search](#web--search)
- [E-commerce & Retail](#e-commerce--retail)
- [Productivity & Collaboration](#productivity--collaboration)
- [Security & OSINT](#security--osint)
- [Creative & Media](#creative--media)
- [Clients & Integration](#clients--integration)
- [Resources & Guides](#resources--guides)

---

## Core / Official

- [Model Context Protocol Specification](https://modelcontextprotocol.io/docs/) - The official specification for the protocol.
- [Anthropic MCP SDKs](https://github.com/modelcontextprotocol) - Official TypeScript and Python SDKs.
- [Anthropic Reference Servers](https://github.com/modelcontextprotocol/servers) - The official repository containing reference implementations (Brave Search, GitHub, Postgres, etc.).

## Development & DevOps

- [GitHub MCP Server](https://github.com/modelcontextprotocol/servers) - Official reference server for interacting with GitHub (Issues, PRs, Repos, Code Search).
- [MartinLoop MCP](https://github.com/Keesan12/martin-loop/tree/main/packages/mcp) - Governed MCP runtime for AI coding agents with budget caps, verifier gates, and inspectable runs.
- [Tuning Engines](https://github.com/cerebrixos-org/tuning-engines-cli) - Govern model, agent, skill, and MCP workflows with policy controls, approvals, traces, and usage analytics. Install with `npx -y --package tuningengines-cli@latest te mcp serve`.
- GitLab MCP Server - *(Coming Soon / Community Implementation)*
- Docker MCP Server - Interact with Docker daemon (containers, images, logs) via Claude.
- Kubernetes MCP - Connect your cluster to Claude for natural language debugging.
- AWS MCP - Manage AWS resources and query CloudWatch logs.

## Databases & Data Management

- [PostgreSQL MCP](https://github.com/modelcontextprotocol/servers) - Official reference server to execute read-only queries against PostgreSQL databases.
- [SQLite MCP](https://github.com/modelcontextprotocol/servers) - Connect to local SQLite databases.
- Redis MCP - Interact with Redis caches.
- DuckDB MCP - Analytical queries on massive local files.
- [Neo4j MCP](https://github.com/neo4j/mcp) - Query and visualize graph data with Cypher.

## Web & Search

- [Brave Search MCP](https://github.com/modelcontextprotocol/servers) - Official integration for web search via Brave.
- Exa Search MCP - AI-focused web search integration.
- Firecrawl MCP - Scrape and crawl websites into LLM-ready markdown.
- [Puppeteer MCP](https://github.com/modelcontextprotocol/servers) - Browser automation to interact with dynamic web pages.

## E-commerce & Retail

- [Packrift MCP](https://github.com/Packrift/packrift-mcp) - Packaging catalog search, pricing, inventory, and cart URLs.

## Productivity & Collaboration

- [Slack MCP](https://github.com/modelcontextprotocol/servers) - Read messages and interact with Slack workspaces.
- [Google Drive MCP](https://github.com/modelcontextprotocol/servers) - Access and read files securely.
- Notion MCP - Query Notion databases and pages.
- Linear MCP - Manage tasks and issues in Linear.

## Security & OSINT

> **Note:** This section is actively being populated! If you build security-focused MCP servers, please contribute!

- VirusTotal MCP - Analyze files, domains, IPs, and URLs.
- Shodan MCP - Query Shodan for connected devices.
- Dependency Scanner MCP - Scan lockfiles (package.json, etc.) for vulnerabilities.
- [EnigmAgent MCP](https://github.com/Agnuxo1/EnigmAgent) - AES-256-GCM + Argon2id encrypted local vault. Resolves `{{PLACEHOLDER}}` secrets at runtime so API keys never appear in prompts or logs.
- [Xquik MCP Server](https://github.com/Xquik-dev/x-twitter-scraper) - X/Twitter data and automation MCP server for tweet search, user lookup, follower export, media download, monitors, webhooks, and confirmation-gated write actions.

## Creative & Media

- [prompt-to-asset](https://github.com/MohamedAbdallah-14/prompt-to-asset) - MCP server for routing image generation prompts across multiple models.

## Clients & Integration

Tools and applications that support the Model Context Protocol:

- [Claude Desktop](https://claude.com/download) - The official desktop app from Anthropic with built-in MCP support.
- [Cursor](https://cursor.com/) - The AI code editor with native MCP configuration capabilities.
- [Windsurf](https://windsurf.com/editor) - AI IDE supporting MCP for context provision.

## Resources & Guides

- [Introducing the Model Context Protocol (Anthropic Blog)](https://www.anthropic.com/news/model-context-protocol)
- How to Build Your First MCP Server - Community guide.
- MCP in Action: Use Cases

---

## Contributing

Contributions of any kind welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

To the extent possible under law, DhanushNehru has waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE) for details.
