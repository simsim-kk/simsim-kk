# Hi, I'm Simsim 👋

**用 AI 工具独立构建并上线产品的创作者 / Builder who ships AI-powered products solo**

我使用 AI 编程工具（Cursor、Windsurf）从零独立开发、部署并上线了多个 Web 产品，覆盖 AI 内容生成、模拟交易、粉丝互动等方向。对 AI 产品设计、提示词工程和用户体验有实际动手经验。

I build and ship web products independently using AI coding tools (Cursor, Windsurf), covering AI content generation, simulated trading, and fan interaction. I have hands-on experience in AI product design, prompt engineering, and UX.

### 🛠️ Tools & Workflow
[![My Skills](https://skillicons.dev/icons?i=vscode,figma,git,github)](https://skillicons.dev)

![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![Windsurf](https://img.shields.io/badge/Windsurf-58E5C0?style=for-the-badge)

### 💻 Languages & Tech
[![My Skills](https://skillicons.dev/icons?i=js,react,python,nodejs,cloudflare,html,css)](https://skillicons.dev)
---

## 🚀 Projects · 项目

### 灵感铺 · 小红书创作三件套 | Inspiration Stall · XHS Creator Toolkit

**[在线访问 / Live Demo →](https://simsim-kk.github.io/xhs-toolkit/)**

一站式小红书创作辅助工具，整合选题、排版、效果检测三个环节。
A one-stop toolkit for Xiaohongshu (RedNote) creators — trend discovery, smart formatting, and virality scoring in a single page.

- 🔥 **热点追踪** — 按 10 个内容方向生成当下适合切入的选题角度与话题标签，Cloudflare Worker 定时任务 + KV 缓存，毫秒级响应
- 🎨 **排版生成** — 任意文字一键转换为小红书风格笔记（标题 / 分段 / emoji / 话题标签）
- 📊 **爆款检测** — 从标题吸引力、内容结构、话题契合、互动引导四个维度评分

**技术栈 / Stack：** GitHub Pages（前端） + Cloudflare Workers（边缘函数） + Workers KV（缓存） + Groq API（llama-3.3-70b）+ Cron Triggers（定时任务）

**亮点 / Highlights：**
前后端分离架构，密钥与业务逻辑全部隔离在 Worker 层；用定时批量生成替代实时请求，
显著降低响应延迟与 API 成本；针对公开数据源拦截问题（403/530）调整方案为 AI 知识生成，
保证服务零依赖、零中断风险。

---

### [BTS ARMY World](https://simsim-kk.github.io/bts-army-world)
全栈粉丝互动网站 · Full-stack fan interaction platform

- 12 个功能模块，含 AI 故事生成、今日陪伴、心情歌单、梦境档案等
- 技术栈：GitHub Pages + Cloudflare Workers + KV + Groq API
- 用户共创内容生态，含独立审核后台，约 5000 行代码，零成本部署
- 12 feature modules including AI story generation, mood playlists, and dream archives
- Stack: GitHub Pages + Cloudflare Workers + KV + Groq API · ~5,000 lines · zero-cost deployment

### [Collend](https://collend.netlify.app)
本地优先的 AI 书签管理器 · Local-first AI bookmark manager

- 粘贴文字或链接，自动生成摘要与标签，全数据存于本机
- Paste text or URLs to get AI-generated summaries and tags, all data stored locally

### [StockPlay US](https://simsim-kk.github.io/StockPlay)
模拟美股交易平台 · Simulated US stock trading platform

- 接入 Finnhub 实时行情，支持限价单、持仓管理、成就徽章
- Real-time quotes via Finnhub API, with limit orders, portfolio tracking, and achievement badges

---

## 🛠️ Skills · 技能

`AI API 集成` `Prompt Engineering` `Cloudflare Workers` `JavaScript` `HTML/CSS`  
`产品设计` `用户体验` `内容运营` `中文写作`

---

## 🌐 Languages · 语言

🇨🇳 中文（母语）· 🇺🇸 英文（读写可用 / Reading & Writing）

---

## 📬 Contact · 联系

有合作或工作机会欢迎联系 · Open to collaboration and job opportunities  
GitHub Issues 或邮件均可
