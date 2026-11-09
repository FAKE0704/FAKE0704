<h1 align="center">你好，我是FAKE0704 👋</h1>
<h3 align="center">Agent Harness 工程师 · 把 DeepSeek Harness 当内核嵌入 8 条产品线的生产系统 · <a href="README.md">English ↑</a></h3>

我主要围绕 [DeepSeek Harness (dsh)](https://github.com/deepseek-ai/deepseek-harness)——一个"万物皆插件"的 Agent 框架——做**插件与工具链开发**，也折腾 Agent 生态里的小实验。在此之前，我从 Claude Code SDK 起步做出产品雏形，随后**从零自研了一套 Agent Harness**，包含内核、插件系统与 Web 界面，代码目前未公开；我的 Agent 架构经验大多来源于此。

2026 年 10 月，这套自研引擎整体迁移到 DeepSeek Harness 内核之上，8 条产品线跑在生产环境；生产撞出的缺口反哺成 9 环自维护补丁链。热衷于将自动化的能力嵌入生活与工作之中，很幸运能碰到 Agent 时代，期待能贡献自己的智慧与能力。

### 🧩 Genshu 设计日志与内核补丁链

**[genshu-design-log](https://github.com/FAKE0704/genshu-design-log)** —— **Genshu** 的公开设计日志。Genshu 是一个以 DeepSeek Harness 为内核的独立 Agent 平台：255 篇编号决策记录、如实的状态台账、内核迁移史、生产事故复盘，以及 919 个真实会话的生产度量画像。

**5 分钟读法**：在 [design-index.md](https://github.com/FAKE0704/genshu-design-log/blob/main/design-index.md) 随便抽一行 → 看 [事故诊断精选](https://github.com/FAKE0704/genshu-design-log/blob/main/03-incident-reviews.md) 里一次真实故障复盘 → 到 fork 仓的 [`patch-chain` 分支](https://github.com/FAKE0704/deepseek-harness/tree/patch-chain) 逐环 diff 九环补丁。

**数字口径**：9 环补丁链 · 8 条产品线 · 255 篇设计决策 · 迁移 2026-10-08（P0 通过）→ 10-11（生产上产）→ 10-14（旧引擎拆除）· n=919 会话（指标只作门禁信号——Goodhart 条款）。

> 补丁链状态：**全部 upstream-pending**。私有仓 = 产品与客户业务；公开仓 = 可核对的方法与决策。

### 📈 QuantOL — 在线量化平台

<p>
  <a href="http://quantol.auto-world-lab.cn/"><b>quantol.auto-world-lab.cn</b></a> — 在线量化回测与交易系统。产品网页已上线，2026 年内开放公测 🚀
</p>

- 开源仓库 [FAKE0704/QuantOL](https://github.com/FAKE0704/QuantOL) 已获 ⭐ 87
- 浏览器里完成回测、策略开发与实盘接入流程
- 公测时间待定 —— Stay tuned!

### 💼 工作经历

- **AI 工程师**（2026.05–至今）——业务线 AI 系统从 0 到 1：菜品运维 Agent 全链路、实时数据管道 + 秒级出价的投流引擎、带语义层与审计的问数 Agent；三方平台 100+ 接口集成供 Agent 调度（其中数十个封装为 MCP 工具）。
- **AI 解决方案架构师**（2026.01–2026.05，Agent 产品 FDE）——企业级 Agent 项目从 POC 到上线端到端交付（工作流编排、工具链、LLM 可观测性），支撑月均上百亿 Token 业务体量。
- **普华永道 · 高级顾问**（2021.07–2025.09）——4 年 IT 咨询，主导 20+ 系统审计，数据中台 0→1 落地，Python/SQL 分析自动化与聚类风控指标。
- **南方科技大学 · 统计学本科**（2017–2021）

### 📝 博客 — Σσ AI Lab

在 [**Σσ AI Lab**](https://blog.auto-world-lab.cn/) 写作，聚焦量化与 AI 工程：量化系统、Agent 工具链，以及踩坑实录。

### 🔌 dsh 插件生态

| 插件 | 介绍 |
| --- | --- |
| [dsh-local-llm](https://github.com/FAKE0704/dsh-local-llm) | 在 dsh 里使用本机大模型：登记、部署/停止推理服务、直接提问、从 Hugging Face / 魔搭下载新模型，并带完整设置页 |
| [dsh-fabric-memory](https://github.com/FAKE0704/dsh-fabric-memory) | dsh 自包含的记忆与知识库插件（记忆原子 + 知识库镜像 + 修订收件箱） |

### 🛠 技术栈

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

### 📊 GitHub 统计

[![关注者](https://img.shields.io/github/followers/FAKE0704?label=%E5%85%B3%E6%B3%A8%E8%80%85&style=flat-square)](https://github.com/FAKE0704?tab=followers)
[![获星总数](https://img.shields.io/github/stars/FAKE0704?label=%E8%8E%B7%E6%98%9F%E6%80%BB%E6%95%B0&style=flat-square)](https://github.com/FAKE0704?tab=repositories&sort=stargazers)
[![QuantOL 获星](https://img.shields.io/github/stars/FAKE0704/QuantOL?label=QuantOL%20%E8%8E%B7%E6%98%9F&style=flat-square)](https://github.com/FAKE0704/QuantOL)

![贡献动画蛇](https://cdn.jsdelivr.net/gh/FAKE0704/FAKE0704@main/snake.svg?v=3)

---

<p align="center"><i>欢迎一起做 dsh 插件与 Agent 项目相关的合作 · 欢迎联系</i></p>
