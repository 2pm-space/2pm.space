<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/integrations; edits here are overwritten by the next export. -->

# Integrations — Channels, APIs, Databases & MCP

> Connect messaging channels, HTTP APIs, 6 databases, MCP servers and sandboxed code to your AI agents — described rather than coded, with an API and an MCP endpoint of its own.

[2pm.space/integrations](https://2pm.space/integrations) · **English** · [Tiếng Việt](vi/integrations.md) · [中文](zh/integrations.md) · [日本語](ja/integrations.md) · [한국어](ko/integrations.md) · [ไทย](th/integrations.md) · [Français](fr/integrations.md) · [ລາວ](lo/integrations.md)

*Channels · Tools · MCP · API*

## Connect it to everything you already run

Messaging channels, HTTP APIs, databases, MCP servers and sandboxed code — described rather than coded, so an agent can reach the system that holds the answer instead of apologising for not knowing.

[Get started free](https://2pm.space/signup)

## Six ways to reach the rest of your stack

Whatever the system is, one of these already covers it.

### Any API, described not coded

Give a tool a URL, a method, an auth header and a JSON Schema for its parameters, then grant it to the agents that should call it. Nothing to deploy beyond the endpoint you already have.

### Code when describing is harder

Python in a sandbox, callable as a tool: the arguments arrive in ARGS and the result is whatever it prints. For the reshaping, parsing and arithmetic that is faster to write than to explain to a model.

### MCP, both directions

Point a tool at any MCP server, discover its tools with one click and switch each on, off or behind approval — and drive this workspace from an external MCP client, including a coding agent building your agents for you.

### Agents as tools

Expose one agent to another. A supervisor delegates to a specialist and gets a structured answer back, instead of a second copy of the specialist inside its own prompt.

### Channels as integrations

Messenger, Personal Zalo, Telegram, Pancake and a website widget connect as first-class channels. Anything else arrives through the Custom API channel — a webhook in, a webhook out.

### Events pushed to you

Inbox events reach endpoints you own, so a new message can trigger something in your stack. Delivery is logged, so a receiver that was down is visible rather than lost.

## The catalogue

What connects today, by kind.

### Messaging channels

- Facebook Messenger, and comments with private reply
- Personal Zalo, with Zalo Official Account coming soon
- Telegram bots
- Pancake accounts
- Website chat widget
- Custom API — webhook in, webhook out

### Tool types

- Built-in tools, including Viettel Post, KiotViet and WordPress
- Webhook tools — any HTTP API, with bearer or key auth
- Sandboxed Python functions, offline unless you allow internet
- Human approval and result caching, per tool
- MCP servers — discover their tools, switch each one on or off
- Agent-as-tool delegation

### Data connections

- PostgreSQL and MySQL
- Redshift and ClickHouse
- Snowflake and BigQuery
- Tables picked on connect — the model reads only those

### Publishing and services

- Facebook Pages and WordPress publishing
- Custom webhook destinations
- Connected app accounts for third-party services
- Viettel Post shipping, with cash on delivery

### Programmatic access

- Workspace API keys, scoped to their creator’s permissions
- An MCP endpoint authenticated by the same key
- Outbound webhooks on inbox events
- Per-call logging with cost

### Ready to install

- A marketplace of agent templates
- Templates cloned into your workspace, then edited
- Skills and tools shared across every agent
- Apps built on the platform and installed into a workspace

## What stops being an engineering project

The integrations you would otherwise have written and maintained.

| Without 2pm.space | With 2pm.space |
| --- | --- |
| A connector request in someone’s backlog, waiting on a vendor to build it | Describe the endpoint yourself and the agent can call it the same afternoon |
| Glue code deployed and maintained for every internal service an agent touches | Webhook tools, plus sandboxed Python for the parts that need it |
| An agent that can only talk, because nothing it needs is reachable from it | Channels, APIs, databases and MCP servers all callable from the same loop |
| Copying a specialist agent’s prompt into every other agent that needs it | One agent exposed as a tool the others delegate to |
| A token pasted into a shared config so a script can reach the platform | Workspace API keys scoped to their creator’s permissions, revocable one by one |

## Integration questions

What engineers ask before wiring this into an internal system.

### How do I connect a service that is not on the list?

With a webhook tool. You give it the URL, the method, the auth header and a JSON Schema for its parameters, then grant it to the agents that should use it — or make it Global for all of them. No code deployed on our side, and none on yours beyond the endpoint you already have.

### Can agents run code?

Yes — Python, in a sandbox, as a tool an agent can call. It is the right answer for the transformations that are easier to write than to describe: reshaping a payload, doing arithmetic a model should not be trusted with, parsing something awkward. Internet access stays off unless you switch it on.

### Does it support MCP?

In both directions. An MCP tool points at any server: discover its tools with one click, then choose which ones agents may use and which need approval. And the platform exposes its own MCP server so an external client — including a coding agent — can drive your workspace: create agents, edit documents, query boards, manage skills and tools.

### Can one agent call another?

Yes. An agent can be exposed as a tool, so a supervisor can delegate to a specialist and get a structured answer back rather than reimplementing what the specialist already does.

### How do webhooks work in the other direction?

Inbox events can be pushed to endpoints you own, so a new message or a resolved conversation can trigger something in your own stack. Delivery is logged, so a receiver that was down is visible rather than a message you never knew about.

### Is there an API?

Yes. API keys are issued per workspace and carry the permissions of the member who created them, so a key cannot do more than the person behind it. The same key authenticates the MCP endpoint.

## Wire it into the system that has the answer

Describe an endpoint, connect a database, or point it at an MCP server. Free to start, no credit card.

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
