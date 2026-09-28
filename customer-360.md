<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/customer-360; edits here are overwritten by the next export. -->

# Customer 360 — One Record Across Every Channel

> Customer 360 in the Inbox: open a conversation and the same person's messages from your other channels are already there — matched on phone or email — beside detected numbers, the linked customer and live data from your own systems.

[2pm.space/customer-360](https://2pm.space/customer-360) · **English** · [Tiếng Việt](vi/customer-360.md) · [中文](zh/customer-360.md) · [日本語](ja/customer-360.md) · [한국어](ko/customer-360.md) · [ไทย](th/customer-360.md) · [Français](fr/customer-360.md) · [ລາວ](lo/customer-360.md)

*Every channel, one record*

## Customer 360, assembled from what already happened

Conversations from every channel, phone numbers caught mid-thread, and live data from your own systems come together as one customer view — the one your team reads and your agents answer from.

[Get started free](https://2pm.space/signup)

## How the record builds itself

No data-entry project. The profile is derived from conversations you are already having.

1. **Connect your channels** — Every conversation the inbox handles builds the record: who wrote, from where, about what. Nothing extra to fill in — the profile exists because the conversations do.
2. **Add your own data** — Attach an enrichment endpoint, import a spreadsheet, or sync from an internal API. Then pick once, for the whole workspace, whether the history shows inline in the thread, in a Customer 360 tab, or not at all.
3. **Work from the whole picture** — Your team answers with the history in front of them, and your agents answer with the same context — including the parts that live in your systems rather than ours.

## A profile that is current because it is derived

Not a form someone has to remember to update.

### One person, every channel

Open a Messenger thread and the same person's website chat and Zalo messages are already in it, joined on the phone number or email they share. Nothing is joined on a similar-looking name — with no shared identifier, two threads stay apart rather than being guessed together.

### Contact details you did not type

Phone numbers customers write mid-conversation are detected, deduplicated against what you already hold, and attached to the conversation — with the staff numbers and forwarded quotes curated out instead of counted.

### Your systems, in the panel

Point it at an endpoint you control. We send the identifiers we hold; your system answers with timeline items — orders, calls, web visits — shown in the thread or in the Customer 360 tab, and not copied into our database unless you turn caching on.

### Context your agent can use

Cache a source and switch its external context on, and the agent replying reads it from that cache — so it can answer about the order without your internal API being on the critical path of every message.

### Bring the customers you have

Import from a spreadsheet with a column mapping it remembers, or sync from an HTTP source on a cursor so each run resumes where the last one stopped. Rows are keyed on your own customer ID, so the next import updates them instead of adding duplicates.

### Gated at the database, not just the API

Customer records are governed by the workspace permission system and enforced at the database level, so a member without the permission cannot reach the rows by any route — including a direct query.

## What Customer 360 holds

What arrives on its own, what you bring, and who is allowed to see it.

### Beside every conversation

- Messages from the same person's other channels
- Detected phone numbers, curated
- The linked customer, with their recent orders
- Labels, internal notes and custom attributes
- A structured conversation summary

### Enrichment from your systems

- An HTTP endpoint you control, GET or POST
- Identifiers sent: conversation, channel, external id, phones, email, name, attributes
- One display choice for the workspace: inline, panel or hidden
- Restrict a source to direct or group conversations
- Auth header encrypted at rest, never returned to the browser

### Getting customers in

- Spreadsheet import with a remembered column mapping
- HTTP sources in connect or sync mode
- Cursor-based sync that resumes where it stopped
- Sync history with counts and errors
- Upsert on your external id, so re-imports update

### For agents

- External context opt-in per source
- Served from cache, off the reply critical path
- Memory the agent keeps about the customer
- Tools that can act on the record

### For your team

- Customer list with search and filters
- A detail page per customer
- Link a conversation to a customer, or create one, from the contact panel
- The same person's other channels, right in the thread you open

### Control

- Permission-gated, enforced at the database
- Channel access applies: history from a channel a teammate cannot open never reaches their thread
- External data fetched, not silently copied
- Enrichment sources disabled without being deleted

## What your team stops piecing together

The manual reconstruction that disappears when the record assembles itself.

| Without 2pm.space | With 2pm.space |
| --- | --- |
| A customer who wrote on three channels is three strangers to your team | Their other channels' messages already in the thread you open |
| Phone numbers copied out of chat threads into a spreadsheet by hand | Numbers detected, deduplicated and attached automatically |
| Order history in the ERP, conversation in the inbox, and an agent that knows neither | Your own systems' rows in the thread, and readable by the agent once cached |
| A CRM import that creates a parallel list nobody reconciles | Imports keyed on your own customer ID, so importing again updates instead of duplicating |
| Everyone with an account can read every customer | Permission-gated records, enforced at the database as well as the API |

## Questions about Customer 360

What teams ask before they connect an internal system to it.

### What makes it a 360 view rather than a contact list?

It is assembled rather than typed in, and it sits where you work: open a conversation and the same person's messages from your other channels — matched on a shared phone number or email — are already in the thread, next to the numbers detected in it, the customer it is linked to with their recent orders, and what your own systems report. It is current because it is derived, not because someone remembered to update it.

### Can it show data from our own CRM or order system?

Yes. You point it at an HTTP endpoint you control. We send the identifiers we hold — conversation, channel, external id, phone numbers, email, name, custom attributes — and your endpoint answers with the timeline items it recognises: orders, calls, web visits. Nothing is copied into our database by default; it is fetched and displayed. A connect-mode customer source can also show the person's name, phone and email, read live when the conversation opens.

### Can the AI agent use that external data when it replies?

Only if you switch it on for that source and keep a cached copy of it. The agent reads external context from that cache rather than making your endpoint answer on every message — so a slow or rate-limited internal API never becomes the thing that delays a customer reply.

### Can I import customers we already have?

Yes — from a spreadsheet with a column mapping you set once and it remembers, or from an HTTP source that syncs on a cursor so each run picks up where the last one stopped. Rows are keyed on your own customer ID, so importing again updates the same customers instead of adding a second copy.

### Who can see customer records?

Customer data is gated by the workspace permission system, and the gate is enforced at the database as well as the API — a member without the permission cannot read the rows by any route. Channel access applies on top: history from a channel a teammate cannot open never shows up in their thread.

### What happens when the same person writes from two channels?

The other channel's messages appear in the thread you have open, matched on a shared phone number or email, while the two conversations stay separate. Nothing is guessed from a similar name — with no shared identifier, they stay apart. Once you link a conversation to a customer, the match follows that link instead of the numbers. Where two channels turn out to describe the same account entirely, the whole channel can be merged into the other.

## See your customers as one person

Connect a channel and the records start building on their own. Free to start, no credit card.

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
