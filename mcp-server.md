<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/mcp-server; edits here are overwritten by the next export. -->

# MCP Server — Connect Claude Code and Cursor to Your Workspace

> A remote MCP server for your 2pm.space workspace. Connect Claude Code, Cursor or any MCP client with an API key, and build agents, edit Drive documents and mind maps, query databases and manage boards from your editor — over 300 tools, limited to what the key allows.

[2pm.space/mcp-server](https://2pm.space/mcp-server) · **English** · [Tiếng Việt](vi/mcp-server.md) · [中文](zh/mcp-server.md) · [日本語](ja/mcp-server.md) · [한국어](ko/mcp-server.md) · [ไทย](th/mcp-server.md) · [Français](fr/mcp-server.md) · [ລາວ](lo/mcp-server.md)

*MCP Server · Claude Code · Cursor*

## Your workspace, inside your AI client

Connect Claude Code, Cursor or any MCP client to 2pm.space with one API key. Ask it to build an agent, fix a workflow, fill a Drive table or put a chart on a board — it does the work through the same operations the app uses, and only the ones your key allows.

[Get started free](https://2pm.space/signup)

## Connected in three steps

A key, a snippet, a request.

1. **Create an API key** — Under Settings › API Keys & MCP, create a key and choose what it may do. A key can never hold more than the person who made it.
2. **Paste the snippet** — Copy the server block for Claude Code or Cursor — the endpoint, and your key in an X-API-Key header — into the client's config file.
3. **Ask for the work** — Tell the client what you want. It lists the workspace's tools, reads the playbook for the job, and calls them step by step.

## The whole workspace, as tools

Not a read-only window — the same operations the app performs.

### Any MCP client

A remote server over Streamable HTTP, so it works with Claude Code, Cursor and any other client that speaks MCP. The in-app setup page gives you the snippet for each.

### Over 300 tools

Agents and their canvases, tools, skills, knowledge, guardrails and memory, Drive documents, tables, mind maps and storyboards, data sources and boards, brands, the content calendar and channels.

### Limited to the key

The server lists only the tools the key's permissions allow, and a key acts as the member who created it. Give a key read permissions only, and it cannot change a thing.

### Playbooks for the long jobs

Nineteen built-in guides — building an agent, setting up RAG, curating a data source, planning a content calendar — that the client reads before it starts.

### Your Drive, from the editor

Create and edit documents, fill Drive tables, add nodes to a mind map or shots to a storyboard — and the changes are there in the app for your team.

### Data and boards

Query a connected database through its semantic model, build a board and add charts to it, or tune the model's measures and relationships.

## What the server exposes

The connection, the key, and the parts of the workspace a client can work in.

### Connection

- A remote MCP server over Streamable HTTP
- One endpoint, shown on the setup page
- Snippets for Claude Code and Cursor
- Discoverable at /.well-known/ai-catalog.json

### Keys & permissions

- A workspace API key in the X-API-Key header
- A key acts as the member who created it
- Permissions no wider than its creator's
- An optional expiry date
- Only permitted tools are listed

### Agents

- Create, configure and delete agents
- Edit the workflow canvas node by node
- Assign tools, skills and knowledge
- Save and restore canvas versions
- Run a test and read the trace

### Drive & content

- Documents, folders and Drive tables
- Mind maps — nodes, shapes and tables
- Storyboards — scenes, shots and frames
- Brands, their products and images
- Content calendar slots

### Data

- Data sources, tables and scopes
- The semantic model: cubes, measures, joins
- Queries in CubeQL or SQL
- BI boards, tabs, charts and filters

### Channels & inbox

- Channels and their settings
- Conversations and their messages
- Care agents and triggers
- Guardrails and memory

## Copy-paste between tabs vs. MCP

The same change, made two ways.

| Without 2pm.space | With 2pm.space |
| --- | --- |
| Describe the app to your AI, then copy its answer back into the app by hand. | The client makes the change itself, through the workspace's own operations. |
| A full-access token pasted into a chat. | A key limited to what its creator may do — and the tool list stops there. |
| The client guesses how a multi-step setup works. | It reads the playbook for the job first. |
| Rebuilding the same agent by hand in every workspace. | Ask once, and the client builds it node by node. |

## MCP questions

What people ask before they connect a client.

### Which clients work?

Any client that supports remote MCP servers over Streamable HTTP. The setup page gives ready-made snippets for Claude Code and Cursor.

### What can a client do in my workspace?

Whatever the key allows: build and test agents; edit Drive documents, tables, mind maps and storyboards; query connected databases; manage boards, brands, the content calendar and channel settings. The tool list the client sees is already filtered to those permissions.

### Is it safe to give an AI client a key?

A key acts as the member who created it and can hold no permission that person lacks. There is no approval prompt over MCP, so the key's permissions are the gate: grant read permissions only to a client that should only read, and set an expiry date on a key that should stop working.

### Does it use my credits?

Most tools are plain reads and writes. Tools that generate something — a calendar outline, an image, a test run of an agent — use workspace credits exactly as they would in the app.

## Work in your workspace without leaving your editor

Create a key, paste the snippet, ask.

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
