<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/agent-builder; edits here are overwritten by the next export. -->

# AI Agent Builder with a Visual Workflow Canvas

> Build AI agents as one prompt or as a workflow: 16 node types for retrieval, tools, evaluation loops, human review and branching. Test runs with per-step logs, canvas versions, and deployment to your inbox, a schedule or an MCP client.

[2pm.space/agent-builder](https://2pm.space/agent-builder) · **English** · [Tiếng Việt](vi/agent-builder.md) · [中文](zh/agent-builder.md) · [日本語](ja/agent-builder.md) · [한국어](ko/agent-builder.md) · [ไทย](th/agent-builder.md) · [Français](fr/agent-builder.md) · [ລາວ](lo/agent-builder.md)

*Agent Builder · Workflow canvas · Test runs*

## Agents that do the work, not just answer a prompt

Start with one prompt, or draw the job as a workflow: find the right documents, reason and call tools, check the answer, ask a person when it matters, and reply. Every run shows what each step did, what it spent and why.

[Get started free](https://2pm.space/signup)

## From idea to working agent in three steps

Draw it, equip it, put it where the work is.

1. **Draw the job** — Pick Simple for a single prompt, or Agentic to lay the job out as nodes on a canvas — retrieval, reasoning, checks, branches — wired left to right.
2. **Give it what it needs** — Attach tools, skills, knowledge and memory to the agent or to a single node, and set the guardrails every message passes through.
3. **Put it to work** — Test it on the canvas, then connect it to an inbox channel, a schedule, another agent as a tool, or an MCP client.

## More than a prompt with tools

A canvas for the jobs one prompt cannot do on its own.

### Simple or agentic

A simple agent is one model call with your system prompt — right for questions, translation and summaries. An agentic agent is a graph of nodes, for jobs that take several steps and a decision between them.

### Sixteen kinds of step

Agent, Crew, Run Agent, Code, Knowledge and Skill Retrieval, Drive Action, Condition, Parallel, Loop, Evaluation, Human Review, Message, Send — each a card you drag onto the canvas and wire to the next.

### It checks its own work

An Evaluation node scores the answer with rules or an LLM judge and routes it: Pass moves on, Retry sends it back to the agent for another attempt, up to the retries you allow.

### A person where it matters

A Human Review node pauses the run until someone approves or rejects it, and a Message node can ask the customer for details through a form or buttons before the flow goes on.

### Tools, skills and knowledge

Sixty built-in tools, your own HTTP APIs and Python, MCP servers, and other agents as tools. A skill loads into every prompt, or only when a question matches it — so a large library does not cost tokens on every call.

### Test it, trace it, roll it back

Run the flow from the canvas and read each node's output, tokens and cost. Save canvas versions, and restore one when a change does not hold up.

## What's on the canvas

Every node, the model catalogue, and every place an agent can run.

### Reasoning & actions

- Agent — its own model, prompt and tools, in a reason-and-act loop
- Crew — a CrewAI crew of agents and tasks
- Run Agent — call an agent you already built
- Code — Python or Bash in a sandbox, no LLM cost

### Flow control

- Start — where a message enters
- Condition — branch on a rule, no LLM cost
- Parallel — every outgoing branch at once
- Loop and Exit Loop — over a list or N times

### Checks & people

- Evaluation — rules or an LLM judge, then Pass or Retry
- Human Review — pause for approve or reject
- Message — a chat message, a form or buttons
- Send — message the customer and carry on

### Knowledge & data

- Knowledge Retrieval — semantic, keyword or hybrid search
- Skill Retrieval — match skills without an LLM step
- Drive Action — create, read or update docs, tables, mind maps and storyboards
- Memory that lasts between conversations, and a workspace memory every agent shares

### Models

- Anthropic, OpenAI, Google and DeepSeek
- Alibaba Qwen, Z.AI GLM, xAI and MiniMax
- A model per Agent node, not one per workflow
- Billed from workspace credits — no provider keys to manage

### Where it runs

- Inbox channels: Messenger, Telegram, personal Zalo, website chat
- The Scheduler, on a recurring timetable
- Another agent, exposed as a tool
- MCP clients such as Claude Code and Cursor
- The Playground, before any customer sees it

## A prompt box vs. an agent builder

The same job, built two ways.

| Without 2pm.space | With 2pm.space |
| --- | --- |
| One prompt tries to retrieve, reason, check and reply at once — and you can't see which part failed. | Each job is its own node, and the run log shows what every node received, returned and spent. |
| A wrong answer goes straight to the customer. | An Evaluation node catches it and sends it back for another try before anyone sees it. |
| A risky action needs a developer to build an approval step. | Put a Human Review node in front of it, and the run waits for a yes. |
| A change that breaks the agent means rebuilding it from memory. | Restore the canvas version from before the change. |

## Agent Builder questions

What people ask before they build their first workflow.

### Do I need to code to build an agent?

No. A simple agent is a form: model, prompt, tools. An agentic agent is drawn on the canvas by dragging nodes and wiring them. Code is optional — a Code node runs Python or Bash when you want a step done without a model.

### What is the difference between a simple and an agentic agent?

A simple agent makes one model call with your system prompt and whatever tools and knowledge you attach. An agentic agent runs a graph: each node does one job — retrieve, reason, check, branch, loop, ask a person — and the edges decide what happens next.

### Which models can an agent use?

The catalogue spans Anthropic, OpenAI, Google, DeepSeek, Alibaba (Qwen), Z.AI (GLM), xAI and MiniMax, and on an agentic canvas each Agent node picks its own model. Usage is paid from your workspace credits, so there are no provider keys to manage.

### How do I test an agent before customers see it?

Run it from the canvas or the Playground. Every run is logged with each step's input, output, tokens, cost and tool calls, so you can see where an answer went wrong and fix that node rather than the whole prompt.

### Can several people edit the same agent?

Yes. The canvas syncs in real time and shows who else is on it, and canvas versions let you save a known-good state and restore it later.

### Where can an agent run once it's built?

On an inbox channel — Messenger, Telegram, personal Zalo or your website chat — on a schedule, as a tool another agent can call, or from an MCP client such as Claude Code or Cursor.

## Build the agent your work actually needs

Start with a prompt. Grow it into a workflow when the job asks for one.

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
