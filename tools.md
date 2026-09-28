<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/tools; edits here are overwritten by the next export. -->

# AI Agent Tool Catalog — 60 Built-in Tools, Your APIs and MCP

> Give your AI agents tools: 60 built-in tools for search, knowledge, data, email, calendars and Drive; your own HTTP APIs and sandboxed Python; any MCP server; and integrations with Viettel Post, KiotViet, WordPress and ERPNext.

[2pm.space/tools](https://2pm.space/tools) · **English** · [Tiếng Việt](vi/tools.md) · [中文](zh/tools.md) · [日本語](ja/tools.md) · [한국어](ko/tools.md) · [ไทย](th/tools.md) · [Français](fr/tools.md) · [ລາວ](lo/tools.md)

*Tools · Built-in · HTTP · Code · MCP*

## Every tool your agents need, in one catalog

Pick from 60 built-in tools, wrap your own API or Python function, connect any MCP server, or hand an agent another agent. Grant each tool to the agents that should have it — and make the risky ones wait for a person's approval.

[Get started free](https://2pm.space/signup)

## Give an agent a tool in three steps

Pick it, connect it, grant it.

1. **Pick a kind** — Choose from the built-in catalog, or create a webhook, a Python function, an MCP connection or an agent-as-tool.
2. **Connect it** — Paste the API key the vendor gave you, or the URL and auth of your own service. Credentials are stored encrypted.
3. **Grant it** — Switch it on for the agents that should use it, or make it global so every agent can. The agent decides when to call it from the tool's description.

## Five kinds of tool, one list

Whatever an agent needs to reach, there is a way to hand it over.

### Sixty tools, ready to go

Web search, Wikipedia and ArXiv, a headless browser, Gmail and Google Calendar, GitHub, Telegram, text-to-speech, BI boards and your own Drive — each a card in the catalog, many working the moment you add them.

### Any HTTP API

Describe the endpoint — method, URL, headers, auth and the JSON the agent should send — and it becomes a tool. GET, POST, PUT, PATCH and DELETE, with bearer-token or API-key auth.

### Your own Python

Write a function, give it an input schema, and it runs in a sandbox with a timeout — offline unless you allow internet access.

### Any MCP server

Point at a server's URL and the tools it exposes are discovered for you. Switch each one on or off, and require approval for the ones that write.

### Agents as tools

Expose one agent to another: a writer can ask a researcher, a sales agent can ask the stock checker — each keeping its own prompt, model and tools.

### You decide who holds what

Grant a tool per agent or make it global, switch it off without deleting it, cache its results, and require a person's approval before it runs.

## 60 built-in tools

The Create Tool catalog as it stands today. Pick a category to narrow the list.

### Search

- Tavily Search — Needs an API key
- DuckDuckGo Search
- Google Serper — Needs an API key
- YouTube Search
- YouTube Video Info
- Google Places — Needs an API key

### Knowledge

- Wikipedia
- ArXiv
- PubMed
- StackExchange
- Semantic Scholar
- OpenWeatherMap — Needs an API key
- Google Scholar — Needs an API key

### Compute

- Wolfram Alpha — Needs an API key
- Python REPL
- Shell Command

### Data

- SQL Database — Needs an API key
- Pandas DataFrame
- Vector Store Search
- GraphQL — Needs an API key
- BI Board

### AI & Media

- DALL-E Image Generation — Needs an API key
- ElevenLabs TTS — Needs an API key
- Google Cloud TTS — Needs an API key
- HuggingFace Hub — Needs an API key

### Finance

- Yahoo Finance News
- Google Finance — Needs an API key
- Google Trends — Needs an API key

### Utility

- Web Fetch
- Crawl URL
- Firecrawl Scrape — Needs an API key
- Jina Reader
- HTTP Request (GET)
- JSON Navigator
- HTTP Requests Toolkit
- Playwright Browser
- Markdown to HTML

### Productivity

- GitHub — Needs an API key
- GitLab — Needs an API key
- Office 365 — Needs an API key
- Gmail — Needs an API key
- Google Calendar — Needs an API key
- Telegram Send Message — Needs an API key
- Zalo
- Notify Operators (Push)

### MCP Servers

- N8N — Needs an API key
- WordPress (Royal MCP)
- GitHub — Needs an API key
- Slack — Needs an API key
- Google Drive — Needs an API key
- Notion — Needs an API key
- Custom MCP Server

### Drive

- Drive Docs
- Drive Mindmap
- Drive Script Storyboard
- Drive Tables

### Integrations

- WordPress
- Viettel Post
- KiotViet
- ERPNext / Frappe

- Plus Composio toolkits, with your own Composio key
- Any HTTP API as a webhook tool
- Any MCP server by URL

## What each kind takes

The fields, the options and the limits — before you sign up.

### Tool kinds

- Built-in — picked from the catalog
- Webhook — any HTTP endpoint
- Code — a sandboxed Python function
- MCP — any MCP server
- Agent as tool — another agent in the workspace

### Webhook tools

- GET, POST, PUT, PATCH and DELETE
- No auth, bearer token or API key
- Custom headers
- A JSON input schema the agent fills in

### Code tools

- Python, edited in the browser
- Runs in a sandbox with a timeout
- Internet access off unless you allow it
- An input schema, like any other tool

### MCP servers

- Connect by URL, over SSE or Streamable HTTP
- Bearer-token auth and custom headers
- Discovered tools listed one by one
- Each switched on or off
- Approval per tool, or for all of them

### Integrations

- Viettel Post — fees, shipments, status and labels
- KiotViet — products, stock, customers, orders and invoices
- WordPress — posts, pages, media, and WooCommerce products
- ERPNext / Frappe — the documents on your site
- Composio toolkits, with your Composio key

### Access & safety

- Granted per agent, or global to all
- Switched off without deleting it
- Human approval before chosen tools run
- Result caching, bypassed when approval is on
- Every call in the run log

## Wiring tools by hand vs. the catalog

The same integration, two ways.

| Without 2pm.space | With 2pm.space |
| --- | --- |
| Every new API means code, a deploy, and a prompt that explains it. | Describe the endpoint once; any agent you grant it to can call it. |
| A tool that can delete things runs as freely as one that reads. | Require approval on the tools that write, and the run waits for a person. |
| Each MCP server brings every tool it has, wanted or not. | Switch each discovered tool on or off, one by one. |
| Nobody is sure which agent can reach which system. | Each tool's page lists the agents it is granted to. |

## Tool questions

What people ask before they connect their first system.

### How many tools are built in?

Sixty today, grouped as search, knowledge, compute, data, AI and media, finance, utility, productivity, MCP servers, Drive and integrations — the full list is on this page. Beyond those, any HTTP API, Python function or MCP server can become a tool.

### Do I need API keys?

Some tools need the vendor's key — Tavily, Serper, Gmail, GitHub and the others marked with a key icon. Many work without one, including DuckDuckGo, Wikipedia, ArXiv, Web Fetch, the Playwright browser and the Drive tools.

### Can a tool wait for approval before it runs?

Yes. Switch on Require human approval for the tools a person should confirm — typically the ones that send, write or delete — and the agent's run pauses until someone approves the call. For an MCP server or an integration, approval is set per discovered tool.

### Can I connect my own MCP server?

Yes. Add an MCP tool with the server's URL, transport and auth; the tools it exposes are discovered and listed, and you switch each one on or off. Presets for N8N, Slack, Notion, GitHub, Google Drive and WordPress are in the catalog.

### Can one agent use another as a tool?

Yes. Create an Agent as tool and pick the agent. Any agent you grant it to can hand it a task and use the answer, while it keeps its own prompt, model and tools.

### Where do Viettel Post and KiotViet fit in?

They are built-in integrations. Connect your account once and the agent gets their operations as tools — quoting a shipping fee, creating a shipment, checking stock, looking up an order.

## Hand your agents the right tools

Start from the catalog. Add your own APIs when you need them.

[Get started free](https://2pm.space/signup) · [Talk to us](contact.md)

---

**Product**

- [AI Inbox](ai-inbox.md) — Messenger, Telegram, website chat and personal Zalo in one queue
- [Live Chat](live-chat.md) — An AI chat widget on your own website
- [Customer 360](customer-360.md) — One record across every channel
- [Ask Data](ask-data.md) — Question your database in plain language
- [BI Dashboards](bi-dashboards.md) — Boards pinned from plain-language questions
- [Content Calendar](content-calendar.md) — Plan, write, illustrate and publish
- [Brand Kit](brand-kit.md) — Voice, design and knowledge for every writer
- [Magic Studio](magic-studio.md) — On-brand AI images on a canvas of steps
- [Storyboard](storyboard.md) — From script to shots to rendered clips
- [Mind Map](mind-map.md) — Free real-time mind mapping, unlimited
- [Mobile App](mobile-app.md)

**Platform**

- [Agent Builder](agent-builder.md) — Workflow agents that retrieve, act and check
- [Tool Catalog](tools.md) — 60 built-in tools, your own APIs and MCP
- [Scheduler](scheduler.md) — Agents that run on a schedule
- [Integrations](integrations.md) — Channels, APIs, databases and MCP
- [MCP Server](mcp-server.md) — Work in your workspace from Claude Code or Cursor
- [Fine-Tuning](fine-tuning.md) — Train a model on your own conversations
- [Security](security.md) — Roles, sharing, audit and backup
- [Pricing](pricing.md)

**Company**

- [Contact](contact.md)
- [Privacy Policy](https://2pm.space/privacy-policy)
- [Delete your account](https://2pm.space/delete-account)
