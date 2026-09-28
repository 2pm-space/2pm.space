<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/zh/mcp-server; edits here are overwritten by the next export. -->

# MCP 服务器——把 Claude Code 和 Cursor 接到你的工作区

> 面向你的 2pm.space 工作区的远程 MCP 服务器。用一个 API 密钥连接 Claude Code、Cursor 或任意 MCP 客户端，在你的编辑器里搭建智能体、编辑 Drive 文档和思维导图、查询数据库、管理看板——超过 300 个工具，范围由密钥的权限决定。

[2pm.space/zh/mcp-server](https://2pm.space/zh/mcp-server) · [English](../mcp-server.md) · [Tiếng Việt](../vi/mcp-server.md) · **中文** · [日本語](../ja/mcp-server.md) · [한국어](../ko/mcp-server.md) · [ไทย](../th/mcp-server.md) · [Français](../fr/mcp-server.md) · [ລາວ](../lo/mcp-server.md)

*MCP 服务器 · Claude Code · Cursor*

## 你的工作区， 就在你的 AI 客户端里

用一个 API 密钥，把 Claude Code、Cursor 或任意 MCP 客户端连接到 2pm.space。让它搭一个智能体、修一条工作流、填一张 Drive 表格，或把一张图表放上看板——它执行的操作和应用本身一模一样，且只限于你这把密钥允许的范围。

[免费开始](https://2pm.space/signup)

## 三步，完成连接

一把密钥，一段代码，一句请求。

1. **创建一个 API 密钥** — 在“设置 › API 密钥与 MCP”里创建一把密钥，选择它能做什么。一把密钥的权限永远不会超过创建它的人。
2. **粘贴代码片段** — 把 Claude Code 或 Cursor 的服务器配置块——端点，以及放进 X-API-Key 请求头的密钥——复制进客户端的配置文件。
3. **直接提需求** — 告诉客户端你想要什么。它会列出工作区的工具，读取这项任务对应的指南，然后一步步调用它们。

## 整个工作区，都变成了工具

不是一个只读的窗口——而是应用本身在执行的那些操作。

### 任意 MCP 客户端

一个通过 Streamable HTTP 提供的远程服务器，因此可以搭配 Claude Code、Cursor 以及任何支持 MCP 的客户端。应用内的设置页面会给出各自的接入代码片段。

### 超过 300 个工具

智能体及其画布、工具、技能、知识、护栏和记忆、Drive 文档、表格、思维导图和分镜脚本、数据源和看板、品牌、内容日历和渠道。

### 限定于密钥的权限

服务器只会列出这把密钥权限允许的工具，且这把密钥以创建它的成员的身份行事。只给一把密钥读取权限，它就什么都改不了。

### 面向长任务的指南

19 份内置指南——搭建一个智能体、配置 RAG、整理一个数据源、规划内容日历——客户端会在开始之前先读取它们。

### 你的 Drive，就在编辑器里

创建和编辑文档，填写 Drive 表格，给思维导图加节点，或给分镜脚本加镜头——这些改动会同步出现在应用里，供团队查看。

### 数据与看板

通过语义模型查询一个已连接的数据库，搭建一个看板并添加图表，或调整模型的指标和关联关系。

## 服务器暴露了什么

连接方式、密钥，以及客户端能操作的工作区各个部分。

### 连接

- 通过 Streamable HTTP 提供的远程 MCP 服务器
- 一个端点，在设置页面上给出
- Claude Code 和 Cursor 的代码片段
- 可在 /.well-known/ai-catalog.json 被发现

### 密钥与权限

- 放在 X-API-Key 请求头中的工作区 API 密钥
- 密钥以创建它的成员的身份行事
- 权限不会超过创建者本人
- 可选的有效期
- 只列出被允许的工具

### 智能体

- 创建、配置和删除智能体
- 逐个节点编辑工作流画布
- 分配工具、技能和知识
- 保存和恢复画布版本
- 运行一次测试并读取执行轨迹

### Drive 与内容

- 文档、文件夹和 Drive 表格
- 思维导图——节点、形状和表格
- 分镜脚本——场景、镜头和画面
- 品牌及其商品和图片
- 内容日历的排期

### 数据

- 数据源、数据表和作用范围
- 语义模型：cube、指标、关联
- 用 CubeQL 或 SQL 查询
- BI 看板、标签页、图表和筛选

### 渠道与收件箱

- 渠道及其设置
- 会话及其消息
- 关怀智能体和触发条件
- 护栏和记忆

## 在标签页之间复制粘贴 vs. MCP

同一次改动，两种做法。

| 没有 2pm.space 时 | 有了 2pm.space |
| --- | --- |
| 把应用讲给你的 AI 听，再把它的答案手动搬回应用里。 | 客户端通过工作区自己的操作，直接完成这次改动。 |
| 一个全权限令牌，粘贴到了聊天窗口里。 | 一把权限不超过创建者的密钥——工具列表也就止步于此。 |
| 客户端要自己猜一套多步骤配置该怎么做。 | 它会先读这项任务对应的指南。 |
| 在每个工作区里，都手动重新搭一遍同一个智能体。 | 只需提一次要求，客户端会逐个节点把它搭出来。 |

## 关于 MCP 的问题

人们在接入一个客户端之前常问的问题。

### 哪些客户端可以用？

任何支持通过 Streamable HTTP 连接远程 MCP 服务器的客户端。设置页面提供了 Claude Code 和 Cursor 的现成代码片段。

### 客户端在我的工作区里能做什么？

取决于密钥允许的范围：搭建和测试智能体；编辑 Drive 文档、表格、思维导图和分镜脚本；查询已连接的数据库；管理看板、品牌、内容日历和渠道设置。客户端看到的工具列表，已经按这些权限过滤过了。

### 把一把密钥交给 AI 客户端安全吗？

一把密钥以创建它的成员的身份行事，不能拥有那个人本身没有的权限。MCP 上没有审批弹窗，所以密钥的权限就是那道闸门：只给应该只读的客户端只读权限，给该停止工作的密钥设一个有效期。

### 它会消耗我的额度吗？

大多数工具只是普通的读取和写入。会生成内容的工具——比如一份日历大纲、一张图片，或一次智能体的测试运行——会像在应用里一样消耗工作区额度。

## 在你的工作区里干活， 不用离开你的编辑器

创建一把密钥，粘贴代码片段，直接提需求。

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
