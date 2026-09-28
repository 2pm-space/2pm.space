<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/scheduler; edits here are overwritten by the next export. -->

# AI Agent Scheduler — Run Agents on a Schedule

> Schedule an AI agent to run on its own: one-time, daily, weekly, monthly or cron, in your timezone. Batch API runs at about half the cost, limits on runs and expiry, and a history of every answer with its tokens and cost.

[2pm.space/scheduler](https://2pm.space/scheduler) · **English** · [Tiếng Việt](vi/scheduler.md) · [中文](zh/scheduler.md) · [日本語](ja/scheduler.md) · [한국어](ko/scheduler.md) · [ไทย](th/scheduler.md) · [Français](fr/scheduler.md) · [ລາວ](lo/scheduler.md)

*Scheduler · Recurring agent runs*

## Agents that show up on time, every time

Tell an agent what to do and when — a sales summary at 8:00, a content digest every Monday, a follow-up sweep each night. It runs on its own, in your timezone, and files every answer where you can read it.

[Get started free](https://2pm.space/signup)

## Put an agent on the clock

Pick the agent, set the time, read the results.

1. **Pick an agent and a job** — Choose the agent and write what it should be asked, one message per line — each line is sent and answered as its own item.
2. **Set when it runs** — One-time, daily, weekly on the days you tick, monthly on a date, or a cron expression — in the timezone you choose.
3. **Read what it did** — Every run lands in the task's history with each answer, its tokens and its cost. Run it now, pause it or cancel it from the list.

## A schedule that knows it's running an agent

Not a cron job firing a webhook — a run with a conversation, tools and a log.

### Five kinds of schedule

One-time on a date, daily at a time, weekly on chosen days, monthly on a day of the month, or any cron expression. Every schedule keeps to the timezone you set, not the server's.

### Results go where they're needed

The agent runs with its tools, so the report can go out as it is written: a Telegram message to your sales group, an email, a push to your operators, a row in a Drive table.

### Half the cost, when it can wait

Switch a simple agent to Batch API and its runs go through the provider's batch queue — about 50% cheaper, finished within 24 hours. For Anthropic and OpenAI models.

### Memory across runs, if you want it

Start a new conversation each run, keep adding to the latest one so the agent remembers last time, or post into a specific conversation.

### It stops when you say

Set an expiry date or a maximum number of runs, and choose how many messages run side by side — from one to ten.

### Every run on the record

Each run keeps its status, its start and finish, and every message's answer or error with tokens and cost — also collected under Settings › Logs.

## Every scheduling option

What the Create Task dialog offers, field by field.

### Schedule

- One-time, at a date and time
- Daily at a time
- Weekly, on any days you tick
- Monthly, on a day of the month
- A custom cron expression
- Any timezone

### Execution

- Immediately, 1–10 messages at a time
- Batch API, about 50% cheaper, within 24 h
- Batch for simple agents on Anthropic or OpenAI models
- Agents with a Human Review step can't be scheduled

### Input & conversation

- One message per line, each its own item
- A new conversation every run
- Or continue the latest conversation
- Or a specific conversation by ID

### Limits

- An expiry date and time
- A maximum number of runs
- Runs counted in the list, e.g. 6/12

### Control

- Run now
- Pause and resume
- Cancel
- Edit or delete
- Search, and filter by status or mode

### History & logs

- The status of every run and every message
- Each answer or error, in full
- Tokens and cost per message and per run
- A Scheduler Runs tab in the workspace logs

## Cron and scripts vs. the Scheduler

The same morning report, two ways.

| Without 2pm.space | With 2pm.space |
| --- | --- |
| A cron job, a script and a server to keep alive — to ask one question. | Pick the agent, write the question, set the time. |
| A run fails at 3 a.m. and you find out a week later. | Each run's status and error sit in the task's history. |
| Every report starts from scratch. | Continue the latest conversation, and the agent remembers the last one. |
| Paying full price for work nobody needs until tomorrow. | Batch API runs cost about half. |

## Scheduler questions

What people ask before they automate their first report.

### What can I schedule?

Any active agent in your workspace. You write the messages it should receive, one per line, and each run sends them and records the answers.

### How do the results reach me?

Through the agent's own tools. Give it Telegram Send Message, Gmail or Notify Operators and say in the message where the result should go. Every answer is also kept in the task's run history.

### What is Batch API mode?

It sends a run's messages through the model provider's batch queue instead of answering them straight away. It costs about half as much and finishes within 24 hours. It works for simple agents on Anthropic or OpenAI models; agentic workflows need multi-turn execution, so they always run immediately.

### Which timezone does it use?

The one you choose on the task — by default, your browser's. Daily, weekly and monthly times are read in that timezone.

### Can I schedule an agent with a Human Review step?

No. A scheduled run has nobody to approve it, so the dialog will not schedule an agent whose workflow contains a Human Review node.

### Can a task stop after a number of runs?

Yes. Set a maximum number of runs, an expiry date, or both. You can also pause, resume or cancel a task at any time.

## Let the agent keep the schedule

Build it once, put it on the clock, and read the results over coffee.

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
