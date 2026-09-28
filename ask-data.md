<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/ask-data; edits here are overwritten by the next export. -->

# Chat With Your Database — AI Analytics & BI Boards

> Connect PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake or BigQuery, define your measures once, and let your team ask questions in plain language — with the SQL and a chart attached to every answer.

[2pm.space/ask-data](https://2pm.space/ask-data) · **English** · [Tiếng Việt](vi/ask-data.md) · [中文](zh/ask-data.md) · [日本語](ja/ask-data.md) · [한국어](ko/ask-data.md) · [ไทย](th/ask-data.md) · [Français](fr/ask-data.md) · [ລາວ](lo/ask-data.md)

*6 databases and warehouses*

## Ask your database a question, get an answer you can check

Connect Postgres, BigQuery, Snowflake or ClickHouse, define your measures once, and let anyone on the team ask in plain language. Every answer arrives with a chart, a table, and the SQL it ran.

[Get started free](https://2pm.space/signup)

## Connects to the database you already run

Six engines, from a Postgres on your own server to a BigQuery project. Pick one, paste the credentials, choose the tables — the connection is tested before it is saved.

- **PostgreSQL** — Host, port 5432, SSL mode
- **MySQL** — Host, port 3306, SSL mode
- **ClickHouse** — Host, HTTP port 8123
- **Snowflake** — Account, warehouse and schema
- **BigQuery** — Service account key and location
- **Redshift** — Cluster endpoint, port 5439

- Credentials encrypted at rest, never sent back to the browser
- Read-only mode: nothing but SELECT reaches it
- Only the tables you pick are modelled

## From a connection string to a board

The modelling is a first pass you edit, not a project you schedule.

1. **Connect a database** — Point it at PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake or BigQuery. Credentials are encrypted at rest, and a connection can be marked read-only so nothing but SELECT ever reaches it.
2. **Curate the model** — The schema is introspected and a first pass of cubes, joins and measures is generated. Hide what nobody should query, rename what only its author understood, and add the measures your business actually reports on.
3. **Ask, then pin** — Ask questions in plain language, check the SQL behind the answer, and pin the ones worth keeping to a board your team opens every morning.

## Self-serve analytics that does not invent numbers

A semantic layer under the questions, so the answers agree with each other.

### Ask in plain language

Type the question the way you would ask a colleague. The answer comes back as a table and the chart that fits the shape of the result — plus the query it ran, so anyone can check the working.

### A semantic model, not a guess

Measures, dimensions and joins are defined once and compiled into every query. Revenue means the same thing in every answer, and a question the model cannot express does not quietly become a hallucinated join.

### Verified questions stay verified

Save an answer you have checked as a verified example. Its question and SQL join the examples the model reads before it writes a query, so the next similar question follows the pattern you approved.

### Boards, built from answers

Pin any answer to a board. Boards carry multiple tabs, shared filters and a date window that stays relative — a board saved as "last 7 days" still means last 7 days next month.

### SQL Lab for the rest

Some questions are faster to type than to explain. Write the SQL yourself against the same semantic model, save the queries you reuse, chart a result and pin it to a board.

### Share numbers, not credentials

A shared board shows the figures without handing over the database behind them. Access is granted per data source, and a viewer gets a board rather than a query console.

## What it connects to, and what you get

Everything the modelling layer, the boards and the SQL console actually support.

### Databases and warehouses

- PostgreSQL and MySQL
- Redshift and ClickHouse
- Snowflake and BigQuery
- Tables picked on connect — the model reads only those

### The semantic layer

- Cubes generated from your schema, then curated
- Measures and computed dimensions you define
- Joins suggested from keys, confirmed by you
- Derived cubes for the shapes SQL alone gets ugly at
- Business context and vocabulary the model reads

### Boards and charts

- Multiple tabs inside one board
- Relative date windows that stay relative
- Board-level filters that lift out of every tile
- Charts picked from the shape of the result
- Share by link, with the data source withheld

### For people who write SQL

- SQL Lab against the same connection
- Verified question and SQL pairs
- Table scope — what the model may and may not see
- Row limits enforced on every query
- Schema refresh when the warehouse changes

### Available to your agents

- Agents can query the same semantic model
- Answers land in chat, the inbox, or a scheduled report
- MCP endpoint for external clients
- Per-run logging of question, query and cost

### Control

- Access granted per data source
- Read-only connections
- Credentials encrypted at rest, never returned to the browser
- Board sharing that does not carry the connection

## Why teams stop screenshotting dashboards

What changes when the numbers answer for themselves.

| Without 2pm.space | With 2pm.space |
| --- | --- |
| Every question about the numbers goes into the analyst queue and comes back next week | Anyone asks in plain language and gets the answer, with the SQL attached |
| An LLM pointed at raw tables, confidently joining the wrong two columns | Queries compiled from a semantic model you defined and can audit |
| "Revenue" means one thing in the finance sheet and another in the ops dashboard | One definition of each measure, used by every answer and every board |
| A dashboard saved as "last 7 days" that quietly means one week in March forever | Relative date windows that stay relative |
| Sharing a number means sharing a database credential | Boards shared without the connection behind them |

## Questions about asking your data

What data teams check before pointing this at production.

### Which databases and warehouses can I connect?

PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake and BigQuery. A connection can be marked read-only so nothing but SELECT ever reaches it, and credentials are encrypted at rest and never sent back to the browser.

### How is this different from letting an LLM write raw SQL?

A model guessing at raw table names will happily join the wrong two columns and hand you a confident, wrong number. Here the questions run against a semantic model: you define the measures, the dimensions and the joins once, and every answer is compiled from those definitions. "Revenue" means the same thing in every chart, and a question the model cannot express against the model does not silently become a made-up query.

### Do I have to model everything before I get an answer?

No. The schema is introspected on connect and a first pass of cubes, joins and measures is generated for you. You then curate — hide the tables nobody should query, rename the columns whose names only make sense to the person who created them, and add the measures your business actually reports on.

### Can I still write SQL when I need to?

Yes. SQL Lab runs hand-written SQL against the same connection and semantic model — save the queries you reuse, chart a result and pin it to a board, or turn a query into a derived cube. Verified examples come from ChatQL itself: save an answer you trust, and its question and SQL guide the queries written for similar questions later.

### Can I turn answers into a dashboard?

Every answer comes back with a table and a chart the platform picked for the shape of the result, and any of them can be pinned to a board. Boards hold multiple tabs, carry their own filters and date windows, and can be shared with people who should see the numbers without being given access to the database behind them.

### Who can see which data?

Access is granted per data source, and a shared board does not carry the connection with it — a viewer sees the board, not a query console. Read-only connections, row limits on every query, and per-run logging of what was asked and what it cost apply throughout.

## Connect a database and ask it something

Free to start, no credit card, and read-only connections so the first question cannot break anything.

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
