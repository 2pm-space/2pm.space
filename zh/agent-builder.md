<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/zh/agent-builder; edits here are overwritten by the next export. -->

# AI 智能体构建器——可视化工作流画布

> 把 AI 智能体构建成一条提示词，或一整套工作流：16 种节点类型覆盖检索、工具调用、评估循环、人工审核与分支判断。测试运行附带逐步日志和画布版本，可部署到你的收件箱、一个调度任务或某个 MCP 客户端。

[2pm.space/zh/agent-builder](https://2pm.space/zh/agent-builder) · [English](../agent-builder.md) · [Tiếng Việt](../vi/agent-builder.md) · **中文** · [日本語](../ja/agent-builder.md) · [한국어](../ko/agent-builder.md) · [ไทย](../th/agent-builder.md) · [Français](../fr/agent-builder.md) · [ລາວ](../lo/agent-builder.md)

*智能体构建器 · 工作流画布 · 测试运行*

## 真正完成工作的智能体， 而不只是回答一条提示词

从一条提示词开始，或把整个任务画成工作流：找到正确的文档、推理并调用工具、核对答案、在关键时刻请人确认，然后回复。每次运行都会显示每一步做了什么、花费多少，以及为什么。

[免费开始](https://2pm.space/signup)

## 三步，从想法到可用的智能体

画出流程，配上装备，再放到真正干活的地方。

1. **画出任务** — 选择 Simple 模式写一条提示词，或选择 Agentic 模式把任务铺成画布上的节点——检索、推理、核对、分支——从左到右依次连接。
2. **配上所需的一切** — 把工具、技能、知识和记忆挂到智能体或某个具体节点上，并设置每条消息都要经过的护栏。
3. **让它开始干活** — 先在画布上测试，再把它接到某个收件箱渠道、一个调度任务、作为另一个智能体的工具，或某个 MCP 客户端。

## 不只是带工具的提示词

一张画布，用来处理一条提示词做不到的任务。

### Simple 或 Agentic

Simple 模式的智能体只是一次模型调用，加上你的系统提示词——适合问答、翻译和摘要。Agentic 模式把智能体变成一张节点图，用于需要多个步骤、且步骤之间要做决策的任务。

### 十六种节点

Agent、Crew、Run Agent、Code、Knowledge Retrieval、Skill Retrieval、Drive Action、Condition、Parallel、Loop、Evaluation、Human Review、Message、Send——每一种都是一张可拖到画布上、彼此相连的卡片。

### 自己核对自己的答案

Evaluation 节点用规则或 LLM 评审给答案打分并决定流向：Pass 就继续往下走，Retry 会把它送回智能体再试一次，最多可设定重试次数上限。

### 在关键处交给人

Human Review 节点会暂停运行，直到有人批准或驳回；Message 节点可以在流程继续之前，通过表单或按钮向客户询问细节。

### 工具、技能与知识

60 个内置工具、你自己的 HTTP API 和 Python 代码、MCP 服务器，以及把另一个智能体当作工具。技能可以注入每条提示词，也可以只在问题匹配时才注入——庞大的技能库不必在每次调用时都消耗 Token。

### 测试、追踪、随时回滚

在画布上运行流程，查看每个节点的输出、Token 和成本。保存画布版本，一旦某次改动不理想，随时恢复。

## 画布上有什么

每一种节点、模型目录，以及智能体可以运行的每一个地方。

### 推理与行动

- Agent——拥有自己的模型、提示词和工具，在推理-行动循环中运行
- Crew——一组 CrewAI 智能体与任务
- Run Agent——调用一个你已经构建好的智能体
- Code——沙箱中的 Python 或 Bash，不产生 LLM 成本

### 流程控制

- Start——消息进入的入口
- Condition——按规则分支，不产生 LLM 成本
- Parallel——同时执行每一条外发分支
- Loop 与 Exit Loop——遍历一个列表，或重复 N 次

### 核对与真人介入

- Evaluation——用规则或 LLM 评审打分，然后 Pass 或 Retry
- Human Review——暂停等待批准或驳回
- Message——一条消息、一个表单或几个按钮
- Send——给客户发消息后继续往下走

### 知识与数据

- Knowledge Retrieval——语义、关键词或混合检索
- Skill Retrieval——无需 LLM 步骤即可匹配技能
- Drive Action——创建、读取或更新文档、表格、思维导图和分镜脚本
- 跨对话保留的记忆，以及每个智能体共享的工作区记忆

### 模型

- Anthropic、OpenAI、Google 和 DeepSeek
- 阿里巴巴 Qwen、智谱 GLM、xAI 和 MiniMax
- 按 Agent 节点各自选择模型，而不是整个工作流只用一个
- 从工作区额度中扣费——无需自行管理各家提供商的密钥

### 运行的地方

- 收件箱渠道：Messenger、Telegram、个人 Zalo、网站聊天
- 调度器，按周期性时间表运行
- 作为工具暴露给另一个智能体
- Claude Code、Cursor 等 MCP 客户端
- 试验场，在任何客户看到之前先行测试

## 提示词输入框 vs. 智能体构建器

同一件事，两种做法。

| 没有 2pm.space 时 | 有了 2pm.space |
| --- | --- |
| 一条提示词要同时完成检索、推理、核对和回复——却看不出到底是哪一步出了问题。 | 每件事都是独立的节点，运行日志会显示每个节点收到了什么、返回了什么、花费了多少。 |
| 一个错误的答案直接发到了客户面前。 | Evaluation 节点会拦下它，退回去再试一次，客户根本看不到。 |
| 一个有风险的操作需要开发者专门搭一道审批步骤。 | 在它前面放一个 Human Review 节点，运行就会等一句“同意”。 |
| 一次改动把智能体弄坏了，只能凭记忆重新搭一遍。 | 把画布恢复到改动之前的那个版本。 |

## 关于智能体构建器的问题

人们在搭建第一个工作流之前常问的问题。

### 搭智能体需要写代码吗？

不需要。Simple 智能体就是一张表单：模型、提示词、工具。Agentic 智能体则通过拖拽节点并连线，在画布上画出来。代码是可选项——想不经过模型完成某一步时，用一个 Code 节点运行 Python 或 Bash 即可。

### Simple 智能体和 Agentic 智能体有什么区别？

Simple 智能体只用你的系统提示词加上挂载的工具和知识，进行一次模型调用。Agentic 智能体运行一张图：每个节点各司其职——检索、推理、核对、分支、循环、请人确认——由连线决定接下来发生什么。

### 智能体可以用哪些模型？

模型目录涵盖 Anthropic、OpenAI、Google、DeepSeek、阿里巴巴（Qwen）、智谱（GLM）、xAI 和 MiniMax；在 Agentic 画布上，每个 Agent 节点各自选择自己的模型。用量从你的工作区额度中扣费，无需自行管理各家提供商的密钥。

### 在客户看到之前，怎么测试一个智能体？

在画布或试验场里运行它。每次运行都会记录每一步的输入、输出、Token、成本和工具调用，你能看清答案到底是在哪里出的问题，然后修正那一个节点，而不是重写整条提示词。

### 可以多人同时编辑同一个智能体吗？

可以。画布实时同步，能看到还有谁在编辑；画布版本可以保存一个确认可用的状态，以后随时恢复。

### 智能体搭好之后可以运行在哪里？

可以运行在收件箱渠道上——Messenger、Telegram、个人 Zalo 或你的网站聊天——也可以按计划运行、被另一个智能体当作工具调用，或从 Claude Code、Cursor 等 MCP 客户端调用。

## 搭建你的工作 真正需要的那个智能体

从一条提示词开始，等任务需要时再让它长成一套工作流。

[免费开始](https://2pm.space/signup) · [联系我们](contact.md)

---

**产品**

- [AI Inbox](ai-inbox.md) — Messenger、Telegram、网站聊天和个人 Zalo，汇入同一个队列
- [Live Chat](live-chat.md) — 放在你自己网站上的 AI 聊天挂件
- [Customer 360](customer-360.md) — 跨所有渠道的同一份客户档案
- [Ask Data](ask-data.md) — 用日常语言向数据库提问
- [BI 看板](bi-dashboards.md) — 从日常语言提问中固定生成的看板
- [Content Calendar](content-calendar.md) — 策划、撰写、配图、发布
- [Brand Kit](brand-kit.md) — 每位撰稿人共用的品牌口吻、设计与知识
- [Magic Studio](magic-studio.md) — 在分步画布上生成符合品牌的 AI 图片
- [Storyboard](storyboard.md) — 从脚本到镜头，再到渲染好的片段
- [Mind Map](mind-map.md) — 免费实时思维导图，不限数量
- [移动应用](mobile-app.md)

**平台**

- [智能体构建器](agent-builder.md) — 能检索、能行动、能自查的工作流智能体
- [工具目录](tools.md) — 60 个内置工具、你自己的 API，以及 MCP
- [调度器](scheduler.md) — 按计划自动运行的智能体
- [集成](integrations.md) — 渠道、API、数据库和 MCP
- [MCP 服务器](mcp-server.md) — 在 Claude Code 或 Cursor 中直接操作你的工作区
- [Fine-Tuning](fine-tuning.md) — 用你自己的对话训练模型
- [安全](security.md) — 角色、共享、审计与备份
- [价格](pricing.md)

**公司**

- [联系](contact.md)
- [隐私政策](https://2pm.space/privacy-policy)
- [删除你的账号](https://2pm.space/delete-account)
