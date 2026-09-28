<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/zh/integrations; edits here are overwritten by the next export. -->

# 集成——渠道、API、数据库与 MCP

> 把消息渠道、HTTP API、6 种数据库、MCP 服务器和沙箱代码连接到你的 AI 智能体——靠描述而不是写代码，平台还自带 API 和 MCP 端点。

[2pm.space/zh/integrations](https://2pm.space/zh/integrations) · [English](../integrations.md) · [Tiếng Việt](../vi/integrations.md) · **中文** · [日本語](../ja/integrations.md) · [한국어](../ko/integrations.md) · [ไทย](../th/integrations.md) · [Français](../fr/integrations.md) · [ລາວ](../lo/integrations.md)

*渠道 · 工具 · MCP · API*

## 连接你 已在使用的一切

消息渠道、HTTP API、数据库、MCP 服务器和沙箱代码——靠描述而不是写代码，让智能体能直接找到掌握答案的系统，而不是道歉说不知道。

[免费开始](https://2pm.space/signup)

## 连通其余技术栈的六种方式

无论是什么系统，总有一种已经能覆盖。

### 任意 API，描述即可，无需编码

为工具设置 URL、方法、认证头和参数的 JSON Schema，然后授予需要调用它的智能体。除了你已有的端点，无需部署任何东西。

### 描述起来更麻烦时，就写代码

沙箱中的 Python，可作为工具调用：参数通过 ARGS 传入，print 的内容就是结果。适合那些写出来比向模型解释更快的整形、解析和计算。

### MCP，双向打通

把工具指向任意 MCP 服务器，一键发现它的工具，并逐个开启、关闭或设为需审批——还能从外部 MCP 客户端操作这个工作区，包括替你搭建智能体的编程智能体。

### 智能体即工具

把一个智能体开放给另一个智能体调用。主管智能体把任务委派给专家智能体，拿回结构化的答案，而不必在自己的提示词里再塞一份专家的副本。

### 渠道即集成

Messenger、个人 Zalo、Telegram、Pancake 和网站小部件作为一等渠道接入。其他一切通过自定义 API 渠道进来——Webhook 进，Webhook 出。

### 事件主动推送给你

收件箱事件会发送到你自己的端点，所以一条新消息就能触发你系统中的操作。投递都有日志，接收端宕机时一目了然，而不会悄悄丢失。

## 集成目录

目前可以连接的内容，按类别列出。

### 消息渠道

- Facebook Messenger，以及支持私信回复的评论
- 个人 Zalo，Zalo Official Account 即将推出
- Telegram 机器人
- Pancake 账号
- 网站聊天挂件
- 自定义 API——Webhook 接入，Webhook 推出

### 工具类型

- 内置工具，包括 Viettel Post、KiotViet 和 WordPress
- Webhook 工具——任意 HTTP API，支持 Bearer 或密钥认证
- 沙箱中的 Python 函数，除非你允许，否则不联网
- 按工具设置的人工审批和结果缓存
- MCP 服务器——发现其工具，逐个开启或关闭
- 智能体即工具的委派

### 数据连接

- PostgreSQL 和 MySQL
- Redshift 和 ClickHouse
- Snowflake 和 BigQuery
- 连接时选定数据表——模型只读取这些表

### 发布与服务

- 发布到 Facebook 主页和 WordPress
- 自定义 Webhook 发布目标
- 为第三方服务关联的应用账号
- Viettel Post 配送，支持货到付款

### 编程访问

- 工作区 API 密钥，权限与创建者一致
- 使用同一密钥认证的 MCP 端点
- 收件箱事件触发的出站 Webhook
- 每次调用都有日志，含成本

### 即装即用

- 智能体模板应用市场
- 模板克隆到你的工作区后再编辑
- 技能和工具在所有智能体之间共享
- 基于平台构建、可安装到工作区的应用

## 不再是一个工程项目

那些原本需要你自己编写和维护的集成。

| 没有 2pm.space 时 | 有了 2pm.space |
| --- | --- |
| 连接器需求躺在某人的待办列表里，等着供应商去开发 | 自己描述端点，当天下午智能体就能调用 |
| 智能体接触的每个内部服务，都要部署和维护一套胶水代码 | Webhook 工具，加上在需要时使用的沙箱 Python |
| 智能体只会聊天，因为它需要的东西一样都够不着 | 渠道、API、数据库和 MCP 服务器都能在同一个循环中调用 |
| 把专家智能体的提示词复制到每一个需要它的智能体里 | 把一个智能体开放为工具，其他智能体向它委派任务 |
| 把令牌粘贴到共享配置里，好让脚本能访问平台 | 工作区 API 密钥，权限与创建者一致，可逐个吊销 |

## 集成相关问题

工程师在把它接入内部系统之前常问的问题。

### 怎么连接不在列表中的服务？

用 Webhook 工具。填写 URL、方法、认证头和参数的 JSON Schema，然后授予需要使用它的智能体——或设为全局，让所有智能体都能用。我们这边不需要部署代码，你那边除了已有的端点也什么都不用加。

### 智能体能运行代码吗？

可以——在沙箱中运行的 Python，作为智能体可以调用的工具。它最适合那些写出来比描述更容易的转换：重组数据载荷、做不该交给模型的计算、解析棘手的内容。除非你开启，否则无法访问互联网。

### 支持 MCP 吗？

双向都支持。MCP 工具可以指向任意服务器：一键发现它的工具，然后选择哪些可供智能体使用、哪些需要审批。平台还公开了自己的 MCP 服务器，外部客户端——包括编程智能体——可以操作你的工作区：创建智能体、编辑文档、查询看板、管理技能和工具。

### 一个智能体能调用另一个智能体吗？

能。智能体可以开放为工具，主管智能体因此可以把任务委派给专家智能体并拿回结构化的答案，而不必重新实现专家已经会做的事。

### 反方向的 Webhook 怎么运作？

收件箱事件可以推送到你自己的端点，所以一条新消息或一段已解决的对话，就能触发你自己系统中的操作。投递都有日志，接收端宕机时一目了然，而不会变成一条你从不知道的消息。

### 有 API 吗？

有。API 密钥按工作区签发，拥有创建它的成员的权限，所以密钥能做的事不会超过它背后的那个人。同一个密钥也用于 MCP 端点的认证。

## 接入那个 掌握答案的系统

描述一个端点、连接一个数据库，或指向一个 MCP 服务器。免费开始，无需信用卡。

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
