<h1 align="center">Hi there, I'm FAKE0704 👋</h1>
<h3 align="center">Agent harness engineer · embedding DeepSeek Harness as the kernel of an 8-product-line production system · <a href="README.zh.md">中文介绍 ↓</a></h3>

I build **plugins and tooling for [DeepSeek Harness (dsh)](https://github.com/deepseek-ai/deepseek-harness)** — an everything-is-a-plugin agent harness — along with agent-ecosystem experiments. Before that, I started with the Claude Code SDK to get an early product running, then designed and built **my own agent harness from scratch**, including the kernel, plugin system, and web UI; the code is currently private, and most of my agent-architecture experience comes from that work.

In 2026-10 its engine was fully migrated onto DeepSeek Harness as the kernel — 8 product lines now run in production on it, and the gaps production surfaced turned into a 9-ring self-managed patch chain. Passionate about embedding automation into everyday life and work — lucky to live in the agent era, and hoping to contribute my own ideas and effort.

### 🧩 Genshu design log & kernel patch chain

**[genshu-design-log](https://github.com/FAKE0704/genshu-design-log)** — the public design log of **Genshu**, an agent platform that embeds DeepSeek Harness as its kernel: 255 numbered decision records with an honest status ledger, kernel migration history, incident post-mortems, and a production metrics profile over 919 real sessions.

**5-minute path**: pick any row in [design-index.md](https://github.com/FAKE0704/genshu-design-log/blob/main/design-index.md) → [incident reviews](https://github.com/FAKE0704/genshu-design-log/blob/main/03-incident-reviews.md) for a real failure post-mortem → the fork's [`patch-chain` branch](https://github.com/FAKE0704/deepseek-harness/tree/patch-chain) diffs the 9 rings one by one.

**Numbers**: 9-ring patch chain · 8 product lines · 255 decision docs · migration 2026-10-08 (P0) → 10-11 (production) → 10-14 (legacy engine removed) · n=919 sessions (metrics as gate signals only — Goodhart clause).

> Patch chain status: **all upstream-pending**. Private repos hold product & client business; public repos hold checkable method & decisions.

### 📈 QuantOL — online quant platform

<p>
  <a href="http://quantol.auto-world-lab.cn/"><b>quantol.auto-world-lab.cn</b></a> — an online quant system for backtesting and trading. Product site is live; public beta coming in 2026 🚀
</p>

- ⭐ 87 stars on [FAKE0704/QuantOL](https://github.com/FAKE0704/QuantOL)
- Backtest engine, strategy development and live trading workflows in the browser
- Public beta date TBD — stay tuned!

### 💼 Experience

- **AI Engineer** (2026.05–now) — built business-line AI systems from 0 to 1: dish-ops agent system covering the full product lifecycle, ad-bidding engine with real-time pipelines, and a governed data-QA agent; integrated 100+ third-party platform APIs for agent orchestration (dozens wrapped as MCP tools).
- **AI Solution Architect** (2026.01–2026.05, agent product FDE) — delivered enterprise agent projects end to end (workflow orchestration, tool chains, LLM observability), supporting ~10B+ tokens of monthly business traffic.
- **Senior Consultant @ PwC** (2021.07–2025.09) — 4 years of IT consulting; led 20+ system audits, built a 0→1 data platform, and shipped Python/SQL analytics automation with clustering-based risk metrics.
- **B.S. in Statistics @ SUSTech** (2017–2021)

### 📝 Blog — Σσ AI Lab

I write about quant and AI engineering at [**Σσ AI Lab**](https://blog.auto-world-lab.cn/) (Chinese) — covering quant systems, agent tooling, and lessons from building them.

### 🔌 dsh plugin ecosystem

| Plugin | What it does |
| --- | --- |
| [dsh-local-llm](https://github.com/FAKE0704/dsh-local-llm) | Run local LLMs in dsh: register models, deploy/stop inference, chat, and pull new models from Hugging Face / ModelScope — with a full settings page |
| [dsh-fabric-memory](https://github.com/FAKE0704/dsh-fabric-memory) | Self-contained memory & knowledge-base plugin for dsh (memory atoms + KB mirror + revision inbox) |

### 🛠 Tech stack

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

### 📊 GitHub stats

[![followers](https://img.shields.io/github/followers/FAKE0704?label=followers&style=flat-square)](https://github.com/FAKE0704?tab=followers)
[![total stars](https://img.shields.io/github/stars/FAKE0704?label=total%20stars&style=flat-square)](https://github.com/FAKE0704?tab=repositories&sort=stargazers)
[![QuantOL stars](https://img.shields.io/github/stars/FAKE0704/QuantOL?label=QuantOL%20stars&style=flat-square)](https://github.com/FAKE0704/QuantOL)

![contribution snake](https://cdn.jsdelivr.net/gh/FAKE0704/FAKE0704@main/snake.svg?v=3)

---

<p align="center"><i>Open to collaboration on dsh plugins & agent projects — feel free to reach out.</i></p>
