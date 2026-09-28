<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/zh/bi-dashboards; edits here are overwritten by the next export. -->

# 由日常语言提问搭建的 BI 看板

> 把 Ask Data 或 SQL Lab 生成的图表固定到共享的 BI 看板上：多标签页、九种图表类型、基于你的数据模型的全局筛选、周期对比和数字格式——支持 PostgreSQL、MySQL、BigQuery、Snowflake、Redshift 或 ClickHouse。

[2pm.space/zh/bi-dashboards](https://2pm.space/zh/bi-dashboards) · [English](../bi-dashboards.md) · [Tiếng Việt](../vi/bi-dashboards.md) · **中文** · [日本語](../ja/bi-dashboards.md) · [한국어](../ko/bi-dashboards.md) · [ไทย](../th/bi-dashboards.md) · [Français](../fr/bi-dashboards.md) · [ລາວ](../lo/bi-dashboards.md)

*BI 看板 · 看板 · SQL Lab*

## 从一个问题开始的 仪表盘

用日常语言向数据库提问，固定生成的图表，它就会加入团队一直开着的看板——支持多标签页、可以触达每个卡片的筛选，以及一键即可对比上一周期。

[免费开始](https://2pm.space/signup)

## 三步，从问题到看板

提问，固定，共享。

1. **提问，或直接写 SQL** — Ask Data 用日常语言配上图表来回答问题。SQL Lab 让你自己写查询，或者让 AI 根据描述帮你起草。
2. **固定到看板** — 把图表固定到一个看板和一个标签页——新建一个，或用已有的。这张卡片保留的是它的查询，而不只是一张图片。
3. **共享它** — 把看板共享给需要它的人。筛选条件保存在链接里，所以打开一个链接就能看到你当时看到的那个视图。

## 始终诚实的看板

每张卡片都是对你数据模型的一次查询，而不是一张截图。

### 同一个营收定义

卡片查询的是 Ask Data 所用的同一个语义模型，所以一个指标只需定义一次，在每张图表、每个看板里都是同一个意思。

### 能触达每张卡片的筛选

在你的模型标记为可筛选的任意维度上添加一个看板筛选——文本、单选、多选、日期或日期范围——每张用到它的卡片都会重新运行。做不到的卡片会明确说明。

### 本期对比上期

与上一周期、去年同期或你选定的区间对比，并按天、周、月、季度或年重新分桶时间。

### 九种画法

柱状图、横向柱状图、堆叠图、100% 堆叠图、折线图、面积图、饼图、散点图，以及单数字卡片——每张卡片都可以单独设置坐标轴、图例、数据标签和系列颜色。

### 给较真的人用的 SQL Lab

对着模型写 CubeQL，查看它编译出的原生 SQL，保存你的查询，把写得好的一条转成可复用的派生 cube。

### 智能体也能搭看板

BI Board 工具让智能体创建看板、添加图表并读取某张卡片的数据——同样的操作也开放在我们的 MCP 服务器上，供 Claude Code 或 Cursor 使用。

## 一个看板支持什么

图表、格式、筛选和时间——完整清单。

### 图表类型

- 柱状图和横向柱状图
- 堆叠图和 100% 堆叠图
- 折线图和面积图
- 饼图
- 散点图
- 数字卡片

### 格式

- 数字、货币、百分比或字节
- 小数位、紧凑的 K / M / B 和分隔符
- 前缀和后缀
- 坐标轴标题、最小值、最大值和对数刻度
- 图例、数据标签和系列颜色
- 按字段覆盖模型自带的格式

### 筛选

- 作用于模型中任意可筛选的维度
- 文本、单选、多选、日期和日期范围
- 等于、不等于、包含、以…开头、以…结尾
- 保存在链接里，方便分享同一个视图
- 在某张卡片的分类中进行搜索

### 时间

- 与上一周期对比
- 或去年同期
- 或自定义区间
- 按天、周、月、季度或年分组
- 相对日期区间始终保持相对

### SQL Lab

- 对着语义模型写 CubeQL
- 它编译出的原生 SQL
- AI 根据描述起草查询
- 保存过的查询
- 把一条查询保存为派生 cube

### 看板与共享

- 一个看板下的多个标签页，可重命名和重新排序
- 可拖拽调整大小的布局
- 按需刷新某张卡片
- 与同事共享
- 智能体和 MCP 客户端也能搭看板

## 表格报表 vs. 实时看板

同一份周一数字，两种做法。

| 没有 2pm.space 时 | 有了 2pm.space |
| --- | --- |
| 每个周一，都有人要导出、粘贴、重新画一次图表。 | 这张卡片保留着它的查询——刷新一下就是最新数据。 |
| 两份报告，两个不同的营收定义。 | 每张卡片都从模型里读取同一个指标。 |
| “能不能看看上个月的？”意味着又要做一份新报告。 | 改一下看板筛选，或打开对比功能。 |
| 一个图表需求要等会写 SQL 的人有空。 | 用日常语言提问，把答案固定下来。 |

## 关于 BI 看板的问题

人们在搭建第一个看板之前常问的问题。

### 看板可以用哪些数据库？

Ask Data 支持的任意连接：PostgreSQL、MySQL、Redshift、ClickHouse、Snowflake 和 BigQuery。看板通过你的语义模型来查询它们。

### 图表是怎么放到看板上的？

从 Ask Data 或 SQL Lab：图表看起来没问题之后，选择“固定到看板”，选定看板和标签页。这张卡片保留的是查询，而不只是一张图片。

### 筛选对每张卡片都生效吗？

看板筛选会作用于每张查询用到该维度的卡片，并重新运行它。做不到筛选的卡片会在标题栏里明确说明，而不是悄悄显示未筛选的数字。

### 可以对比上个月或去年吗？

可以。打开对比功能，选择上一周期、去年同期，或自定义区间；带日期区间的卡片会同时显示两个周期。

### 智能体能用看板吗？

可以。BI Board 工具让智能体创建看板、添加图表并读取某张卡片的数据，同样的操作也通过 MCP 服务器开放给 Claude Code 或 Cursor。

## 把你的数字 放到每个人都能看到的地方

连接一个数据库，提一个问题，固定这个答案。

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
