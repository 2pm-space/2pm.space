<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/fine-tuning; edits here are overwritten by the next export. -->

# Fine-Tune an AI Model on Your Own Conversations

> Rate your AI agent's replies in the inbox, correct the ones that missed, tune an open-weight model on those pairs with LoRA, and point an agent at the result — billed from the same credit balance as everything else.

[2pm.space/fine-tuning](https://2pm.space/fine-tuning) · **English** · [Tiếng Việt](vi/fine-tuning.md) · [中文](zh/fine-tuning.md) · [日本語](ja/fine-tuning.md) · [한국어](ko/fine-tuning.md) · [ไทย](th/fine-tuning.md) · [Français](fr/fine-tuning.md) · [ລາວ](lo/fine-tuning.md)

*LoRA on open-weight models*

## Fine-tune a model on your own conversations

Rate your agent's replies in the inbox and correct the ones that missed, tune an open-weight model on those pairs, and point an agent at the result — so the tone you keep re-explaining in a prompt lives in the weights instead.

[Get started free](https://2pm.space/signup)

## Dataset, run, agent

Three steps, all inside the workspace the model will work in.

1. **Build a dataset** — Pick a training dataset in an inbox thread, then 👍 the AI replies worth keeping and improve the ones that missed. Every pair waits for your Include or Exclude before anything is sent for training.
2. **Pick a base and train** — Choose an open-weight base model, see the estimated cost once the dataset is exported, keep the default hyperparameters or change them, and start the run.
3. **Point an agent at it** — The finished adapter appears in an agent's Model picker under My Adapters. Point one agent at it, replay real customer messages with that agent from the inbox's Run with…, and keep whichever answers better.

## Fine-tuning without a separate stack

No provider console, no reserved capacity, no contract — the same credit balance as everything else.

### Train on replies you already reviewed

The training pairs come from your inbox: AI replies you rated 👍, the corrections you wrote when a reply missed, high-scoring episodes from the agent's memory, and any Q&A pairs you add — instead of examples invented for a model to imitate.

### A smaller model that behaves

Once the tone and the vocabulary are in the weights, they stop costing you prompt tokens on every call — which usually means a smaller, faster model doing work that needed a large one.

### Estimated before you start

Once the dataset is exported, the train dialog shows the estimated cost and the number of training tokens before the run starts. The run is charged when it finishes, from the same credit balance as everything else — no separate contract, no reserved capacity.

### A dropdown, not a migration

A finished adapter appears as a model your agents can select, next to the hosted providers. Point one agent at it, compare, and keep whichever answers better.

### Jobs you can watch

Datasets, training runs and finished adapters each have their own list, with the state, the base model and the cost of every run visible rather than buried in a provider console.

### Gated on its own

Training data is made of real customer conversations, so the whole surface carries its own permission — including the candidate list — separate from the rest of the workspace.

## What the pipeline supports

From the conversations that go in to the adapter your agents call.

### Datasets

- Built from AI replies rated and corrected in your inbox
- Every candidate pair listed for Include or Exclude before export
- A dataset detail view of what will be trained on
- Reusable across several training runs

### Base models

- Open-weight families: Llama, Qwen, Mistral and Mixtral
- DeepSeek R1 distills and gpt-oss
- Parameter count shown per model
- Estimated cost shown once the dataset is exported
- A curated list of bases the training provider can fine-tune

### Training runs

- LoRA adapters, with sensible defaults for every hyperparameter
- Job state and history per run
- Cost recorded against the run
- Failures surfaced, not silently retried forever

### Serving

- Adapters appear as a model provider in the agent picker
- Billed at the base model's inference rate, times the adapter's premium multiplier
- Usable by any agent in the workspace
- Switchable per agent, per node

### Control

- Its own permission key, with training a separate action
- Candidate conversations gated behind the same key
- Phone numbers and emails scrubbed before the JSONL is uploaded to the training provider, Together AI
- Not pooled with, or used to train, anything else

### Cost

- Same credit balance as the rest of the platform
- No subscription, no per-seat charge
- Estimate shown before the run, the actual cost charged after

## What a tuned model changes

Where the cost and the inconsistency actually go.

| Without 2pm.space | With 2pm.space |
| --- | --- |
| A 2,000-token system prompt re-explaining your tone on every single call | Tone and vocabulary in the weights, paid for once |
| Reaching for the biggest model because the small one will not stay on brand | A tuned small model that behaves, at a fraction of the per-call cost |
| Writing synthetic training examples for a domain you already have transcripts of | A dataset built from the AI replies you already rated and corrected |
| Training in a provider console, disconnected from where the model is used | Dataset, run and served adapter in the same workspace as the agents |

## Questions about fine-tuning

What teams check before they train on customer conversations.

### What does fine-tuning give me that a good prompt does not?

A prompt tells a model what to do; a fine-tune teaches it how you do it. Once the tone, the product vocabulary and the shape of a good reply are in the weights, you stop paying for them in every prompt — which usually means a smaller, cheaper, faster model doing work that previously needed a large one.

### Where does the training data come from?

From your inbox. Pick a training dataset in a thread's settings, then rate the agent's replies — a 👍 makes a reply a candidate — and use Improve to write how a reply should have gone; that correction becomes a training pair too. Episodes the agent's memory scores 8 or more out of 10 can be routed in automatically, and you can add Q&A pairs by hand. Replies your team wrote are not collected. Every pair waits for your Include before it is exported, and because the pairs are real customer messages, the whole surface is permission-gated separately from the rest of the workspace.

### Which base models can I train?

Open-weight models only, since a hosted model like Claude or GPT cannot be LoRA-tuned. The list is a curated set the training provider can fine-tune — Llama, Qwen, Mistral, Mixtral, DeepSeek R1 distills and gpt-oss, from 1B to 120B parameters — each shown with its parameter count.

### What does it cost?

Training is metered per million tokens at the base model's rate, with the provider's per-run minimum, and the train dialog shows the estimate once the dataset is exported. The run is charged when it finishes, from the same credit balance as everything else. Once trained, an adapter is billed at its base model's inference rate times the adapter's premium multiplier. There is no subscription and no per-seat charge — see the pricing page for how usage billing works.

### How do I use a trained model?

It appears in your agents' Model dropdown under My Adapters, alongside the hosted providers. Point one agent at it, replay real customer messages with it from the inbox's Run with…, and keep whichever answers better — the switch is a dropdown, not a migration.

### Is my training data used to train anything else?

No. A dataset built in your workspace trains an adapter that belongs to your workspace, and the platform does not pool it or share it with other tenants. To train, the exported JSONL — with phone numbers and email addresses scrubbed — is uploaded to the training provider, Together AI, which runs the fine-tune and serves the adapter your agents call.

## Train a model that already sounds like you

Build a dataset from replies your agent has already given. Free to start — the training run is charged from your credit balance when it finishes.

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
