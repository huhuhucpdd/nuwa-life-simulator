# 赛博女娲 · 个人量子人生模拟器（nuwa-life-simulator.skill）
>**“如果当时选了另一条路，现在的你会是什么样？—— 这不是疑问，这是一个可以玩的存档。”**
[![交互式推演](https://img.shields.io/badge/🎮_交互式推演-时间线自由编辑-ff69b4?style=for-the-badge&logo=windowsterminal&logoColor=white&labelColor=0d1117)](#)
[![隐私沙盒](https://img.shields.io/badge/🔐_隐私沙盒-只提取特征,不存储原始数据-2ea043?style=for-the-badge&logo=privacy&logoColor=white&labelColor=0d1117)](#)
[![平行时间线](https://img.shields.io/badge/🌌_平行时间线-α・β・γ_动态模拟-1f6feb?style=for-the-badge&logo=git&logoColor=white&labelColor=0d1117)](#)
[![可编辑人生存档](https://img.shields.io/badge/🕹️_可编辑存档-暂停・回溯・修改-db61a2?style=for-the-badge&logo=save&logoColor=white&labelColor=0d1117)](#)
[![科学推演](https://img.shields.io/badge/🧬_推演引擎-统计基线+个人偏离+随机-7b4df2?style=for-the-badge&logo=framework&logoColor=white&labelColor=0d1117)](#)
[![Status: Early Stage](https://img.shields.io/badge/Status-Early%20Stage-orange.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/huhuhucpdd/nuwa-life-simulator?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117&color=yellow)](#)
[![Version](https://img.shields.io/badge/version-2.0-7b4df2?style=for-the-badge&logo=version&logoColor=white&labelColor=0d1117)](#)

## 这是什么？

**赛博女娲**是一套结构化 Prompt（Skill），让你能在支持长上下文的 AI 对话中，对自己的真实人生进行"版本控制"：

- 🕐 **回溯**：回到过去任意决策节点
- ✍️ **改写**：修改一个选择，看世界如何分叉（一句话、一本书、一次告白）
- 🌌 **推演**：AI 基于你的行为模式生成平行人生对比

<img width="1672" height="941" alt="时间线" src="https://github.com/user-attachments/assets/c9c5aa79-435f-478b-9412-7548b125d004" />

---
这不是职业测试，也不是情感分析。  
**这是你人生的版本控制工具。**  
导入你的数据，让 AI 蒸馏出你的“决策基因”，然后你可以在过去与未来之间自由穿梭，随便修改一个选择，看世界的走向如何天翻地覆。

---

## 5 分钟立刻上手

复制下面这句话，粘贴到支持 Skill 的 AI 对话中，立刻开始：

> `“我想知道如果去年我选择了离开现在的工作/关系，今天会是什么样。请启动时间线推演，先用快速题问我三个问题就立刻开始。”`

---

## 核心机制

### 三条时间线

| 时间线 | 说明 |
|--------|------|
| **α 线（基准）** | 按你当前惯性自然延伸 |
| **β 线（激进）** | 把抑制偏好放松 30%，探索"更敢的自己" |
| **γ 线（随机）** | 注入黑天鹅事件，展示意外剧本 |

### 三种推演引擎

- **混沌引擎**：纯随机上帝骰子，用于展示极端可能性空间  
- **统计引擎**：基于真实社会统计学模型（职业转型成功率、地域流动性等群体数据）
- **混合引擎（推荐）**：推荐）：**统计基线 + 你的个人偏离量 + 残余随机噪声** —— 既有普适规律，又保留你的独特决策指纹

### 半衰期诚实

| 时间范围 | 可信度 |
|----------|--------|
| 0–6 个月 | 70%–85% |
| 6 个月–2 年 | 50%–65% |
| 2–5 年 | 30%–45% |
| 5 年以上 | 10%–20%（仅主题风向）|

> 时间越远，我们越诚实。这不是不自信，是对蝴蝶效应的敬畏。

  **🕸️ 三层因果网络**  
  推演不是线性的：我们维护一张 `微观（你的日常决策）→ 中观（社交圈、职业环境）→ 宏观（经济周期、技术变革）` 的贝叶斯网络，每次你报告新的人生事件，整张网络都会更新一次先验概率，让推演随你一同进化。


---
## 隐私保证

所有原始个人数据**仅在你自己的对话环境中处理**，AI 只接收匿名结构化特征。处理完成后会提醒你删除原始数据。详见 `references/privacy-sandbox.md`。

---

## 当前状态

⚠️ **早期阶段**。核心推演逻辑通过 Prompt Engineering 实现，题库和事件库持续扩充中。

已知局限：
- 长对话可能出现上下文漂移
- 统计引擎的基线数据来自公开社会研究，精度有限
- 5 年以上推演为概念展示，不宜作为决策依据

欢迎 Issue、PR 与讨论。

---

## 为什么做这个

> 很多时候我们困在当下，不是因为没能力选对路，而是因为没有亲眼看过另一种可能性足够具体的展开，所以不敢动。

赛博女娲不帮你做决定。它只是让你看见——"假如你选了另一条路，五年后的你会在做什么？"

当你看过平行人生的对比卡，有些心结会松，有些动力会生。

---  
如果你用这个工具重新看见了平行世界的自己，请告诉我。我在另一边等你。

*赛博女娲由 十七i 构建 · 连接我*  

[![Email](https://img.shields.io/badge/Email-2037131983@qq.com-important)](mailto:2037131983@qq.com)
[![GitHub](https://img.shields.io/badge/GitHub-huhuhucpdd-lightgrey)](https://github.com/huhuhucpdd)

本项目说明：本项目处于项目初级阶段，做的不好的地方请各位老爷高抬贵手！希望大家共建！
