<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/security; edits here are overwritten by the next export. -->

# Security & Governance for AI Agents

> Per-resource permissions, custom roles, team and channel-level access, encrypted credentials, guardrails on agent output, per-run audit logs, and scheduled backups.

[2pm.space/security](https://2pm.space/security) · **English** · [Tiếng Việt](vi/security.md) · [中文](zh/security.md) · [日本語](ja/security.md) · [한국어](ko/security.md) · [ไทย](th/security.md) · [Français](fr/security.md) · [ລາວ](lo/security.md)

*Roles · Sharing · Audit · Backup*

## Give people exactly the access they need

Per-resource permissions, per-team channel access, encrypted credentials, guardrails on what agents may say, and a log of every run — so putting AI in front of customers is a decision you can defend.

[Get started free](https://2pm.space/signup)

## Governance that survives the second team

The controls that decide whether AI can be trusted with a real customer conversation.

### Roles that fit the job

Owner, Admin and Member out of the box, and custom roles when those do not fit. Permissions are granted per resource and per action, so "runs the inbox, never sees billing" is a role rather than a rule someone has to remember.

### Per-resource sharing

An agent, a document, a folder, a tool or a board carries its own access list on top of roles — view, use, edit or admin (view, comment or edit on a document), granted to a member, a team, or everyone.

### Channel-level separation

Channels are closed by default. Assign a Page, a Zalo account or a widget to a member, a role or a team at View, Reply, Configure or Full access, and the inbox they open holds only those conversations — what an agency needs, and what a support team on one product needs.

### Secrets that stay secret

Database credentials, channel tokens and endpoint auth headers are encrypted at rest and never returned to the browser. Forms report that a secret is configured; they do not re-display it.

### Guardrails on what agents may say

Policies applied to what goes into an agent and what comes out, with an audit of which guard fired, what it did, and why — so a blocked reply is a record, not a mystery.

### A log for every kind of run

Agent executions with their tool calls and cost, scheduled task runs, webhook deliveries, care sends, platform errors and every access change — each with its own list rather than one undifferentiated stream.

## What you can control

Access, data handling, visibility and continuity.

### Identity and access

- Owner, Admin and Member system roles
- Custom roles with per-resource, per-action grants
- Teams, with leads and members
- 55 permission resources, 201 permissions
- Invitations, and access revoked from one screen

### Resource-level sharing

- View, use, edit, admin — view, comment, edit on documents
- Granted to a member, a team, or the workspace
- Applies to agents, documents, folders and tools
- Applies to knowledge bases, channels, data sources and boards
- Share-by-link documents, with the level you choose

### Data handling

- Workspace isolation on every request
- Credentials encrypted at rest
- Secrets never returned to the browser
- Read-only database connections where you want them
- External customer data fetched, not silently copied

### Visibility

- Per-run execution logs with tokens and cost
- Guardrail audit — which fired, and what it did
- Scheduled run history
- Webhook delivery log
- Platform error log, and an access log of every role and sharing change

### Backup and continuity

- On-demand and scheduled backups
- Restore back into the workspace
- Export of workspace data
- Storage usage visible per workspace

### Programmatic access

- API keys scoped to their creator’s permissions
- The same key authenticates the MCP endpoint
- Keys revocable individually
- Per-call logging with cost attribution

## What changes when access is granular

The workarounds that stop being necessary.

| Without 2pm.space | With 2pm.space |
| --- | --- |
| Everyone who can log in can see everything, because access is all-or-nothing | Per-resource, per-action permissions, plus a per-resource access list |
| Giving a contractor one Page means handing over the whole workspace | Channel access assigned to a member, a role or a team |
| An API token pasted into a config file and shared around the team | Credentials encrypted at rest, never displayed again after they are saved |
| An AI reply that went wrong, and no way to see what it did or what it cost | A per-run log with every tool call, every guard outcome and the cost of each step |
| Backups that exist if someone remembered to run one | Scheduled backups, with restore into the workspace |

## Security and governance questions

What an administrator checks before the second team is invited in.

### How granular are permissions?

Permissions are granted per resource type and per action — reading agents, creating tools, restoring backups, starting a training run: 55 resources and 201 permissions, each a separate grant. Three roles exist out of the box (Owner, Admin, Member) and you can define your own, blank or copied from one of them, so "can answer the inbox but cannot touch billing" is a role rather than an exception someone has to remember.

### Can I share one agent or one document without sharing the workspace?

Yes. On top of role permissions, individual resources — agents, documents, folders, tools, knowledge bases, channels, data sources and boards — carry their own access list. You grant a member, a team, or the whole workspace a level on that specific thing: view, use, edit or admin on an agent, a tool or a board; view, comment or edit on a document or a folder.

### Can an agency give a client team access to only their own channels?

That is exactly what channel access is for. Channels are closed by default: a Page, a Zalo account or a widget is assigned to a member, a role or a team at View, Reply, Configure or Full access, and the inbox they open contains only the conversations from what they hold. Owners and admins see every channel. To answer a customer, a person needs both halves — Reply on their role and Reply on that channel.

### Where are credentials and API tokens kept?

Encrypted at rest, and never sent back to the browser. A settings form that shows a connected integration reports that a secret is configured; it does not re-display the value. That applies to database connections, channel tokens and the auth headers on enrichment endpoints alike.

### What can I see about what the AI actually did?

Every run is logged end-to-end: the messages, the tools it called and what they returned, the tokens and cost per step, and which guardrails fired and what they did about it. Separate logs cover scheduled runs, webhook deliveries, care sends and platform errors.

### Can I get my data out, and can I delete it?

Backups can be run on demand or on a schedule and restored into the workspace. Deletion is a first-class action rather than a support ticket: a member can delete their own account from the site, and workspace data goes with the workspace.

## Set it up the way your team is shaped

Roles, teams and per-resource access are there from the first workspace. Free to start, no credit card.

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
