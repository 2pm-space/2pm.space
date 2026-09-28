<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/zh/tools; edits here are overwritten by the next export. -->

# AI 智能体工具目录——60 个内置工具、你的 API 与 MCP

> 给你的 AI 智能体配上工具：60 个内置工具覆盖搜索、知识、数据、邮件、日历和 Drive；你自己的 HTTP API 和沙箱 Python；任意 MCP 服务器；以及 Viettel Post、KiotViet、WordPress 和 ERPNext 的集成。

[2pm.space/zh/tools](https://2pm.space/zh/tools) · [English](../tools.md) · [Tiếng Việt](../vi/tools.md) · **中文** · [日本語](../ja/tools.md) · [한국어](../ko/tools.md) · [ไทย](../th/tools.md) · [Français](../fr/tools.md) · [ລາວ](../lo/tools.md)

*工具 · 内置 · HTTP · Code · MCP*

## 智能体需要的每一种工具， 都在一个目录里

从 60 个内置工具中挑选，把你自己的 API 或 Python 函数包装成工具，连接任意 MCP 服务器，或把一个智能体交给另一个智能体使用。把每个工具授权给该用的智能体——高风险的那些，让它们等人批准。

[免费开始](https://2pm.space/signup)

## 三步，给智能体配上一个工具

选一种，接上它，授权给它。

1. **选一种类型** — 从内置目录中选择，或创建一个 Webhook、一个 Python 函数、一个 MCP 连接，或把某个智能体当作工具。
2. **接上它** — 粘贴服务商给你的 API 密钥，或填入你自己服务的 URL 和认证方式。凭据都以加密方式存储。
3. **授权给它** — 为该用的智能体开启它，或设为全局，让每个智能体都能用。智能体会根据工具的描述，自行判断何时调用它。

## 五种工具，一份清单

智能体需要触达的任何东西，都有办法交给它。

### 六十个工具，开箱即用

网页搜索、维基百科和 ArXiv、无头浏览器、Gmail 和 Google 日历、GitHub、Telegram、文字转语音、BI 看板，还有你自己的 Drive——目录里每一项都是一张卡片，很多添加后立刻就能用。

### 任意 HTTP API

描述这个端点——方法、URL、请求头、认证方式，以及智能体应该发送的 JSON——它就变成了一个工具。支持 GET、POST、PUT、PATCH 和 DELETE，可用 Bearer 令牌或 API 密钥认证。

### 你自己的 Python

写一个函数，定义它的输入结构，它就会在带超时限制的沙箱里运行——默认不联网，除非你允许。

### 任意 MCP 服务器

指向某个服务器的 URL，它暴露的工具会被自动发现。逐个开启或关闭，对会写入数据的工具要求审批。

### 智能体即工具

把一个智能体开放给另一个：撰稿智能体可以请教调研智能体，销售智能体可以请教库存查询智能体——各自保留自己的提示词、模型和工具。

### 由你决定谁能用什么

按智能体单独授权，或设为全局；不删除也能关闭它；缓存它的结果；运行前要求有人批准。

## 60 个内置工具

创建工具目录当前的全貌。选一个分类来缩小范围。

### 搜索

- Tavily Search — 需要 API 密钥
- DuckDuckGo Search
- Google Serper — 需要 API 密钥
- YouTube Search
- YouTube Video Info
- Google Places — 需要 API 密钥

### 知识

- Wikipedia
- ArXiv
- PubMed
- StackExchange
- Semantic Scholar
- OpenWeatherMap — 需要 API 密钥
- Google Scholar — 需要 API 密钥

### 计算

- Wolfram Alpha — 需要 API 密钥
- Python REPL
- Shell Command

### 数据

- SQL Database — 需要 API 密钥
- Pandas DataFrame
- Vector Store Search
- GraphQL — 需要 API 密钥
- BI Board

### AI 与媒体

- DALL-E Image Generation — 需要 API 密钥
- ElevenLabs TTS — 需要 API 密钥
- Google Cloud TTS — 需要 API 密钥
- HuggingFace Hub — 需要 API 密钥

### 财务

- Yahoo Finance News
- Google Finance — 需要 API 密钥
- Google Trends — 需要 API 密钥

### 实用工具

- Web Fetch
- Crawl URL
- Firecrawl Scrape — 需要 API 密钥
- Jina Reader
- HTTP Request (GET)
- JSON Navigator
- HTTP Requests Toolkit
- Playwright Browser
- Markdown to HTML

### 效率

- GitHub — 需要 API 密钥
- GitLab — 需要 API 密钥
- Office 365 — 需要 API 密钥
- Gmail — 需要 API 密钥
- Google Calendar — 需要 API 密钥
- Telegram Send Message — 需要 API 密钥
- Zalo
- Notify Operators (Push)

### MCP 服务器

- N8N — 需要 API 密钥
- WordPress (Royal MCP)
- GitHub — 需要 API 密钥
- Slack — 需要 API 密钥
- Google Drive — 需要 API 密钥
- Notion — 需要 API 密钥
- Custom MCP Server

### Drive

- Drive Docs
- Drive Mindmap
- Drive Script Storyboard
- Drive Tables

### 集成

- WordPress
- Viettel Post
- KiotViet
- ERPNext / Frappe

- 另有 Composio 工具包，需要你自己的 Composio 密钥
- 任意 HTTP API 都能作为 Webhook 工具
- 任意 MCP 服务器，按 URL 接入

## 每种类型需要填什么

字段、选项和限制——注册前就能看到。

### 工具类型

- 内置——从目录中挑选
- Webhook——任意 HTTP 端点
- Code——沙箱中的 Python 函数
- MCP——任意 MCP 服务器
- 智能体即工具——工作区中的另一个智能体

### Webhook 工具

- GET、POST、PUT、PATCH 和 DELETE
- 无认证、Bearer 令牌或 API 密钥
- 自定义请求头
- 由智能体填写的 JSON 输入结构

### Code 工具

- Python，在浏览器中编辑
- 在带超时限制的沙箱中运行
- 默认不联网，除非你允许
- 和其他工具一样有输入结构

### MCP 服务器

- 按 URL 连接，通过 SSE 或 Streamable HTTP
- Bearer 令牌认证和自定义请求头
- 发现的工具逐一列出
- 每个都可单独开启或关闭
- 可按工具单独设置审批，也可全部要求审批

### 集成

- Viettel Post——运费、运单、状态和面单
- KiotViet——商品、库存、客户、订单和发票
- WordPress——文章、页面、媒体和 WooCommerce 商品
- ERPNext / Frappe——你网站上的各类文档
- Composio 工具包，需要你自己的 Composio 密钥

### 访问与安全

- 按智能体单独授权，或全局开放
- 关闭而不必删除
- 选定工具运行前需人工批准
- 结果缓存，开启审批时会绕过缓存
- 每次调用都记录在运行日志中

## 手写工具接线 vs. 使用目录

同一种集成，两种做法。

| 没有 2pm.space 时 | 有了 2pm.space |
| --- | --- |
| 每接入一个新 API，都意味着写代码、部署一次，再补一段解释它的提示词。 | 把端点描述一次；被授权的任何智能体都能调用它。 |
| 能删除数据的工具，和只能读取数据的工具一样随意运行。 | 对会写入数据的工具要求审批，运行会等一个人确认。 |
| 每接入一个 MCP 服务器，就把它拥有的所有工具都带了进来，不管是否需要。 | 逐个开启或关闭每一个发现的工具。 |
| 没人说得清哪个智能体能触达哪个系统。 | 每个工具的页面都列出了它被授权给了哪些智能体。 |

## 关于工具的问题

人们在接入第一个系统之前常问的问题。

### 内置工具有多少个？

目前 60 个，分为搜索、知识、计算、数据、AI 与媒体、财务、实用工具、效率、MCP 服务器、Drive 和集成——完整列表就在本页。除此之外，任意 HTTP API、Python 函数或 MCP 服务器都可以变成一个工具。

### 需要自己准备 API 密钥吗？

有些工具需要服务商的密钥——Tavily、Serper、Gmail、GitHub 等标有钥匙图标的工具。很多工具不需要，包括 DuckDuckGo、维基百科、ArXiv、Web Fetch、Playwright 浏览器和 Drive 工具。

### 工具可以在运行前等待审批吗？

可以。为需要人工确认的工具——通常是发送、写入或删除类的——开启“需要人工审批”，智能体的运行就会暂停，直到有人批准这次调用。对于 MCP 服务器或集成，审批是按每个发现的工具单独设置的。

### 可以接入我自己的 MCP 服务器吗？

可以。用服务器的 URL、传输方式和认证信息添加一个 MCP 工具；它暴露的工具会被发现并列出，你可以逐个开启或关闭。目录中已经内置了 N8N、Slack、Notion、GitHub、Google Drive 和 WordPress 的预设。

### 一个智能体可以把另一个智能体当作工具吗？

可以。创建一个“智能体即工具”，选定那个智能体。被授权的任何智能体都可以把任务交给它，并使用它的答案，而它仍然保留自己的提示词、模型和工具。

### Viettel Post 和 KiotViet 是怎么接入的？

它们是内置集成。连接一次你的账号，智能体就能把它们的操作当作工具使用——报运费、创建运单、查库存、查订单。

## 把合适的工具 交到智能体手上

从目录开始，需要时再加上你自己的 API。

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
