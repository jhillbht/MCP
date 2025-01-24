# Model Context Protocol servers

This repository is a collection of *reference implementations* for the [Model Context Protocol](https://modelcontextprotocol.io/) (MCP), as well as references to community built servers and additional resources.

The servers in this repository showcase the versatility and extensibility of MCP, demonstrating how it can be used to give Large Language Models (LLMs) secure, controlled access to tools and data sources. Each MCP server is implemented with either the [Typescript MCP SDK](https://github.com/modelcontextprotocol/typescript-sdk) or [Python MCP SDK](https://github.com/modelcontextprotocol/python-sdk).

⭐ Reference Servers
------------------

These servers aim to demonstrate MCP features and the Typescript and Python SDK.

- **[AWS KB Retrieval](src/aws-kb-retrieval-server)** - Retrieval from AWS Knowledge Base using Bedrock Agent Runtime
- **[Brave Search](src/brave-search)** - Web and local search using Brave's Search API
- **[EverArt](src/everart)** - AI image generation using various models
- **[Everything](src/everything)** - Reference / test server with prompts, resources, and tools
- **[Fetch](src/fetch)** - Web content fetching and conversion for efficient LLM usage
- **[Filesystem](src/filesystem)** - Secure file operations with configurable access controls
- **[Git](src/git)** - Tools to read, search, and manipulate Git repositories
- **[GitHub](src/github)** - Repository management, file operations, and GitHub API integration
- **[GitLab](src/gitlab)** - GitLab API, enabling project management
- **[Google Drive](src/gdrive)** - File access and search capabilities for Google Drive
- **[Google Maps](src/google-maps)** - Location services, directions, and place details
- **[Memory](src/memory)** - Knowledge graph-based persistent memory system
- **[PostgreSQL](src/postgres)** - Read-only database access with schema inspection
- **[Puppeteer](src/puppeteer)** - Browser automation and web scraping
- **[Sentry](src/sentry)** - Retrieving and analyzing issues from Sentry.io
- **[Sequential Thinking](src/sequentialthinking)** - Dynamic and reflective problem-solving through thought sequences
- **[Slack](src/slack)** - Channel management and messaging capabilities
- **[Sqlite](src/sqlite)** - Database interaction and business intelligence capabilities
- **[Time](src/time)** - Time and timezone conversion capabilities

💝 Third-Party Servers
-------------------

🏅 Official Integrations
--------------------

Official integrations are maintained by companies building production ready MCP servers for their platforms.

- <img height="12" width="12" src="https://axiom.co/favicon.ico" alt="Axiom Logo" /> **[Axiom](https://github.com/axiomhq/mcp-server-axiom)** - Query and analyze your Axiom logs, traces, and all other event data in natural language
- <img height="12" width="12" src="https://browserbase.com/favicon.ico" alt="Browserbase Logo" /> **[Browserbase](https://github.com/browserbase/mcp-server-browserbase)** - Automate browser interactions in the cloud (e.g. web navigation, data extraction, form filling, and more)
- <img height="12" width="12" src="https://cdn.simpleicons.org/cloudflare" /> **[Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)** - Deploy, configure & interrogate your resources on the Cloudflare developer platform (e.g. Workers/KV/R2/D1)

[Rest of the file content follows...]