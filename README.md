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

- **[Axiom](https://github.com/axiomhq/mcp-server-axiom)** - Query and analyze your Axiom logs, traces, and all other event data in natural language
- **[Browserbase](https://github.com/browserbase/mcp-server-browserbase)** - Automate browser interactions in the cloud (e.g. web navigation, data extraction, form filling, and more)
- **[Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)** - Deploy, configure & interrogate your resources on the Cloudflare developer platform (e.g. Workers/KV/R2/D1)
- **[Raygun](https://github.com/MindscapeHQ/mcp-server-raygun)** - Interact with your crash reporting and real using monitoring data on your Raygun account
- **[Obsidian Markdown Notes](https://github.com/calclavia/mcp-obsidian)** - Read and search through your Obsidian vault or any directory containing Markdown notes
- **[E2B](https://github.com/e2b-dev/mcp-server)** - Run code in secure sandboxes hosted by [E2B](https://e2b.dev)
- **[Exa](https://github.com/exa-labs/exa-mcp-server)** - Search Engine made for AIs
- **[JetBrains](https://github.com/JetBrains/mcp-jetbrains)** - Work on your code with JetBrains IDEs
- **[Neon](https://github.com/neondatabase/mcp-server-neon)** - Interact with the Neon serverless Postgres platform
- **[Neo4j](https://github.com/neo4j-contrib/mcp-neo4j/)** - Neo4j graph database server and separate graph database backed memory
- **[Tinybird](https://github.com/tinybirdco/mcp-tinybird)** - Interact with Tinybird serverless ClickHouse platform
- **[Search1API](https://github.com/fatwang2/search1api-mcp)** - One API for Search, Crawling, and Sitemaps
- **[Qdrant](https://github.com/qdrant/mcp-server-qdrant/)** - Implement semantic memory layer on top of the Qdrant vector search engine
- **[Metoro](https://github.com/metoro-io/metoro-mcp-server)** - Query and interact with kubernetes environments monitored by Metoro

🌎 Community Servers
------------------

> **Note:** Community servers are **untested** and should be used at **your own risk**. They are not affiliated with or endorsed by Anthropic.

- **[MCP Installer](https://github.com/anaisbetts/mcp-installer)** - Server that installs other MCP servers for you
- **[NS Travel Information](https://github.com/r-huijts/ns-mcp-server)** - Access Dutch Railways real-time train travel information
- **[Spotify](https://github.com/varunneal/spotify-mcp)** - Play and control Spotify through LLM chat
- **[Inoyu](https://github.com/sergehuber/inoyu-mcp-unomi-server)** - Interact with Apache Unomi CDP platform
- **[Vega-Lite](https://github.com/isaacwasserman/mcp-vegalite-server)** - Generate visualizations using VegaLite
[...continued with all community servers in similar format...]

📚 Resources
----------

Additional resources on MCP.

- **[Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers)** - Curated list by Frank Fiegel
- **[Discord Server](https://glama.ai/mcp/discord)** - Community discord for MCP
- **[Smithery](https://smithery.ai/)** - Registry of MCP servers for LLM agents
- **[mcp-get](https://mcp-get.com)** - CLI tool for managing MCP servers
- **[MCPHub](https://github.com/Jeamee/MCPHub-Desktop)** - GUI app for managing MCP servers

[Continue with Getting Started and remaining sections...]