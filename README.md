# 📡 AI 与金融市场每日速报
# 📡 AI & Market Daily Briefings

> 中英双语说明 · Bilingual README（中文优先，英文对照）

本仓库聚合两类**每日速报**，由 AI 智能体自动化生成并持续更新：一类聚焦 **AI 与开源生态**（AI + GitHub），一类聚焦 **金融市场每日动态**。所有产出均为可直接在浏览器打开的单文件 HTML，浅色主题、无外部依赖。

This repository aggregates two kinds of **daily briefings**, automatically generated and continuously updated by AI agents: one focused on the **AI & open-source ecosystem** (AI + GitHub), and one on **daily financial-market movements**. Every deliverable is a self-contained, light-themed, dependency-free HTML file you can open directly in any browser.

---

## 📌 项目简介 | Project Overview

**中文**
这是一个"日报化"的内容聚合项目。我们用 AI 智能体把每天全球范围内**热度最高、关注度最高**的事件，整理成结构清晰、可读性强、附原文链接的速报。目前包含两条内容线：AI/开源线 与 金融线。

**English**
This is a "daily-briefing" content hub. AI agents curate each day's **highest-traffic, most-watched** events worldwide into structured, readable reports with source links. It currently spans two tracks: an AI / open-source track and a finance track.

---

## 🗂 内容构成 | What's Inside

### 1. AI 与 GitHub 热门事件速报
### 1. AI & GitHub Hot-Events Briefing

- **路径 / Path**：`AI与GitHub热门事件速报/`
- **命名 / Naming**：`AI与GitHub热门事件速报_YYYY-MM-DD.html`
- **内容 / Coverage**：近 72 小时全球大模型发布、AI 科研突破与治理争议、AI 资本与融资并购、GitHub 开源热点四大板块，附真实可点击的原文链接。
  *Covers the last ~72h of model launches, AI research breakthroughs & governance debates, AI funding/M&A, and trending GitHub open-source projects — with real, clickable source links.*
- **主题 / Theme**：浅色亮色、单文件、无外部依赖。
  *Light theme, single file, zero external dependencies.*

### 2. 今天市场发生了什么（金融市场日报）
### 2. What Happened in the Market Today (Finance Daily)

- **路径 / Path**：`金融市场发生了什么/`
- **命名 / Naming**：`今天市场发生了什么_YYYY-MM-DD.html`
- **内容 / Coverage**：每日金融市场综述，覆盖宏观、行情、板块与关键资讯。
  *A daily market roundup spanning macro, market moves, sectors, and key headlines.*

---

## 🛠 内容来源与工具链 | Sources & Toolchain

两份日报由**不同的智能体工具 + 大模型组合**分别产出，便于横向对比不同工作流的效果：

The two briefings are produced by **different agent-tool + model combinations**, which also makes for a useful side-by-side comparison of workflows:

| 内容线 Content Track | 智能体工具 Agent Tool | 大模型 Model | 产出格式 Output |
| --- | --- | --- | --- |
| AI 与 GitHub 热门事件 | **WorkBuddy** + **Hy3（混元）** | Hy3（混元） | 单文件 HTML |
| 金融市场每日动态 | **Trae** + **GLM 5.2（智谱）** | GLM 5.2（智谱） | 单文件 HTML |

> 即：AI/GitHub 内容由 **WorkBuddy + Hy3** 产出；金融内容由 **Trae + GLM 5.2** 产出。
> *i.e. AI/GitHub content is produced by **WorkBuddy + Hy3**; finance content by **Trae + GLM 5.2**.*

---

## 📁 目录结构 | Repository Structure

```text
项目整理/
├── README.md                         ← 本文件 / this file
├── AI与GitHub热门事件速报/           ← AI & GitHub 线
│   ├── AI与GitHub热门事件速报_2026-09-18.html
│   ├── AI与GitHub热门事件速报_2026-09-17.html
│   └── …（每日一份 / one file per day）
└── 金融市场发生了什么/               ← 金融线
    ├── 今天市场发生了什么_2026-09-01.html
    ├── 今天市场发生了什么_2026-08-31.html
    └── …（每日一份 / one file per day）
```

---

## 🔍 阅读方式 | How to Read

- **直接打开**：双击任意 `.html` 文件，即可在浏览器中查看完整速报（含图表、事件卡与原文链接）。
  *Just open any `.html` file in a browser to view the full briefing (charts, event cards, and source links included).*
- **按日期浏览**：文件名含 `YYYY-MM-DD`，按日期排序即可回溯历史。
  *File names embed `YYYY-MM-DD`, so sort by date to browse history.*
- **原文链接**：每份速报文末均附按板块分组的真实原文链接，方便溯源。
  *Each briefing ends with grouped, real source links for traceability.*

---

## 🔄 更新频率 | Update Cadence

- 两类速报均按**日更**节奏自动生成（AI 线由定时自动化任务驱动；金融线由 Trae + GLM 5.2 工作流驱动）。
  *Both tracks update **daily** — the AI track via a scheduled automation; the finance track via a Trae + GLM 5.2 workflow.*
- 若某日无重大事件，可能不产出当日文件。
  *If a day is quiet, a same-day file may be skipped.*

---

## ⚠️ 免责声明 | Disclaimer

- 本仓库内容由 AI 智能体基于公开网络信息**自动聚合**生成，仅供学习与信息参考，**不构成任何投资建议**。
  *All content is **automatically aggregated** by AI agents from public web sources for learning and reference only — **not investment advice**.*
- 文中涉及的数值（如星标数、估值、行情数据）为报道时点的近似值，最终以官方披露为准。
  *Figures (stars, valuations, market data) are approximate as of report time; defer to official disclosures.*
- 速报中的观点归纳来自源报道，不代表本仓库立场。
  *Summaries reflect source reporting and are not endorsements by this repository.*

---

## 🤝 关于本仓库 | About This Repo

- 目标：把"每天世界上发生了什么值得关注的 AI 与金融大事"沉淀成可长期回溯的开放档案。
  *Goal: turn "what notable AI & finance events happened today" into an open, browsable archive.*
- 欢迎通过 Issue / PR 反馈纠错或建议新的内容维度。
  *Feedback and suggestions (Issues / PRs) on corrections or new dimensions are welcome.*

---

<p align="center">
  Generated with ❤️ by AI agents · WorkBuddy + Hy3 ＆ Trae + GLM 5.2<br>
  中文 · English 双语速报档案
</p>
