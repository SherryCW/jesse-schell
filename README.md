<div align="center">

# Jesse Schell Game Design Master

### 把“这个游戏好像不够好玩”，变成下一场能推翻假设的实验。
### Turn “this game doesn't feel fun” into the next experiment that can prove you wrong.

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=for-the-badge)](https://github.com/SherryCW/jesse-schell)
![Bilingual](https://img.shields.io/badge/中文_%7C_English-Bilingual-7C3AED?style=for-the-badge)
![35 Chapters](https://img.shields.io/badge/Knowledge_Base-35_Chapters-0F766E?style=for-the-badge)
![112 Lenses](https://img.shields.io/badge/Design_System-112_Lenses-EA580C?style=for-the-badge)

**体验 × 系统 × 证据 × 风险 × 商业 × 责任**<br>
**Experience × Systems × Evidence × Risk × Business × Responsibility**

[中文](#中文) · [English](#english) · [Quick Start](#quick-start) · [Repository Map](#repository-map)

</div>

---

## 中文

这不是一份“把 112 个透镜全部问一遍”的清单，也不是对 Jesse Schell 本人的模仿。

它是一套可执行的**游戏设计诊断与决策系统**：将《游戏设计艺术》第 3 版的 35 章知识与 112 个编号透镜，和风险优先原型、行为试玩证据、生产约束、商业闭环、社群健康及设计责任融合起来。面对一个模糊问题，它会先锁定**当前必须做出的决定**和**可能让项目失败的最大未知**，再只选择 3–5 个真正可能改变决定的透镜。

最终交付的不是一堆听起来正确的建议，而是：

> **一个强诊断、一个最大风险、一个最小实验、四条行为阈值，以及实验结束后的明确决策。**

### 为什么它不一样

| 常见设计分析 | Game Design Master |
|---|---|
| 罗列几十条建议 | 锁定一个当前决策和一个最大风险 |
| 机械扫描全部透镜 | 按问题与项目阶段选择 3–5 个高杠杆透镜 |
| 把“玩家说喜欢”当结论 | 用 E0–E4 证据等级区分直觉、陈述与行为 |
| 先把原型做漂亮 | 先制造最便宜、最可能失败的验证物 |
| 只看首次体验 | 分开检查第一次、第三次与第三十次会话 |
| 只优化乐趣或转化 | 同时追踪系统、商业、社群与可预见伤害 |
| 给出方向后结束 | 明确 Pass / Mixed / Fail 三条下一决策 |

### 核心决策链

```text
深度聆听
   ↓
玩家微场景 → 本质体验 → 真实使用情境
   ↓
系统因果 → 玩家行为 → 单一最大风险
   ↓
一次性原型 → 行为证据 → 继续 / 修改 / 替换 / 停止
   ↓
生产、商业、社群与责任闭环
```

### 它能处理什么

- **概念与核心循环**：这个创意真正承诺了什么体验？没有奖励，玩家还愿意重复吗？
- **机制与平衡**：是否存在低风险支配策略、失控反馈环、虚假选择或经济通胀？
- **关卡、谜题与界面**：玩家能否看见状态、理解行动、读懂结果，并知道为什么？
- **叙事、角色与世界**：玩家的选择是否真的改变状态、知识、关系或代价？
- **节奏与留存**：第一次的惊喜，能否变成第三次的学习和第三十次的长期价值？
- **多人、社群与治理**：系统奖励了合作、表达与归属，还是骚扰、剥削与冷漠？
- **VR / AR 与新技术**：技术是否创造了不可替代的体验，舒适与安全阈值在哪里？
- **商业化与长线运营**：价值流、资金流和行为影响是否一致，哪里会透支信任？
- **制作、提案与客户沟通**：什么证据能降低最大生产风险，并让提案围绕玩家时刻成立？

### 四种工作模式

1. **快速诊断**：3 个透镜、1 个最大风险、1 个下一实验。
2. **深度设计评审**：基于构建版本、设计文档、录像、遥测或试玩记录完成系统追踪与决策日志。
3. **概念创造**：从本质体验、场景、主题和四元素出发，生成可丢弃的最小原型。
4. **参考查询**：直接解释某个透镜、章节或概念，不强制运行完整协议。

### 证据不是装饰

| 等级 | 证据 | 能支持什么 |
|---|---|---|
| **E4** | 可复现的构建行为、规则或遥测 | 可支持决策 |
| **E3** | 多次记录的目标玩家行为 | 强证据，但受场景限制 |
| **E2** | 与行为对应的访谈或问卷 | 用于解释，不能单独定案 |
| **E1** | 利益相关者判断、市场轶事、社群意见 | 生成假设 |
| **E0** | 设计师直觉或模型推断 | 只用于指引方向 |

每次结论还会标注高 / 中 / 低置信度，并说明**什么新证据会改变判断**。

### 你会得到什么

默认输出是一份紧凑、可进入会议和迭代周期的决策简报：

```markdown
强诊断：PVP 的问题不是平均胜率，而是低风险策略压缩了可表达的策略空间。
置信度：中｜证据等级：E3

玩家微场景：高水平玩家识别到安全策略后，不再尝试高方差路线。
当前决策：调整数值，还是重做选择的机会成本？
最大风险：优势策略不是“过强”，而是“最少后悔”，小幅削弱无法恢复生态。

透镜组合：
- 有意义选择：可能推翻“更多选项等于更多策略”的假设。
- 技能与机会：可能推翻“输赢主要由操作水平决定”的假设。
- 风险消除：可能推翻“改数值就是最低成本答案”的假设。

最小实验：纸面/脚本模拟三种机会成本结构，不制作新内容。
成功行为：目标玩家主动切换策略，并能解释不同局面的代价。
失败行为：玩家继续无条件回到同一安全策略。
护栏：不提高新手理解成本。
停止线：两轮测试后策略集中度和选择理由均无变化。

Pass → 进入小范围数值验证
Mixed → 重做反馈与信息可见性
Fail → 替换机会成本结构
```

### 调用示例

```text
Use $jesse-schell-game-design-master to diagnose the largest experience risk in my
core loop, select only the lenses that could change our decision, and design the
cheapest falsifiable prototype.
```

```text
用 $jesse-schell-game-design-master 分析这个 PVP 机制。不要只看胜率；找出支配
策略为什么降低表达空间，给出证据等级、3–5 个透镜、最小实验和停止线。
```

```text
用 $jesse-schell-game-design-master 评审这份试玩记录。严格分开观察、解释、
反证和决策，并告诉我什么证据仍然不足。
```

---

## English

This is not a checklist that blindly runs all 112 lenses, and it does not impersonate Jesse Schell.

It is an executable **game-design diagnosis and decision system**. It combines a source-located knowledge base covering 35 chapters and 112 numbered lenses from the third edition of *The Art of Game Design* with risk-first prototyping, behavioral playtest evidence, production constraints, business viability, community health, and design responsibility.

Given an ambiguous design problem, it first identifies the **decision that must be made now** and the **single unknown most capable of killing the project**. It then selects only 3–5 lenses with enough leverage to change that decision.

The result is not a cloud of plausible advice. It is:

> **One strong diagnosis, one largest risk, one minimal experiment, four behavioral thresholds, and a decision when the experiment ends.**

### Why it is different

| Typical design analysis | Game Design Master |
|---|---|
| Produces a long recommendation list | Names one current decision and one largest risk |
| Scans every available framework | Routes 3–5 high-leverage lenses by problem and project stage |
| Treats “players said they liked it” as proof | Separates intuition, statements, and behavior with E0–E4 evidence grades |
| Polishes the prototype first | Builds the cheapest artifact most capable of failing |
| Optimizes the first session | Separates first-, third-, and thirtieth-session value |
| Optimizes fun or conversion in isolation | Traces system, business, community, and foreseeable impact together |
| Ends with a direction | Defines Pass / Mixed / Fail decision branches |

### The operating chain

```text
Deep listening
   ↓
Player micro-scene → Essential experience → Real play context
   ↓
System causality → Player behavior → Single largest risk
   ↓
Disposable prototype → Behavioral evidence → Continue / Modify / Replace / Stop
   ↓
Production, business, community, and responsibility closure
```

### What it can work on

- **Concepts and core loops** — What experience does the idea actually promise? Would players repeat without extrinsic rewards?
- **Mechanics and balance** — Dominant strategies, runaway feedback, fake choices, probability, fairness, and economy inflation.
- **Levels, puzzles, and interfaces** — Can players read state, discover actions, understand feedback, and recover from failure?
- **Narrative, characters, and worlds** — Do choices change state, knowledge, relationships, identity, or cost?
- **Pacing and retention** — Can first-session magic become third-session learning and thirtieth-session value?
- **Multiplayer and communities** — Which behaviors do identity, ranking, rewards, and governance actually reinforce?
- **VR / AR and emerging technology** — Is the technology essential, and where are the comfort, access, and safety thresholds?
- **Monetization and live operations** — Do value flow, money flow, and behavioral impact remain aligned over time?
- **Production, pitching, and clients** — Which evidence retires the largest production risk and makes the player moment legible?

### Four operating modes

1. **Quick diagnosis** — 3 lenses, 1 largest risk, 1 next experiment.
2. **Deep design review** — Use a build, design document, video, telemetry, or playtest notes for system tracing and a decision log.
3. **Concept creation** — Define the essential experience, context, theme, four elements, largest risk, and disposable prototype.
4. **Reference lookup** — Explain a lens, chapter, or concept without forcing the full protocol.

### Evidence is part of the design

| Grade | Evidence | Proper use |
|---|---|---|
| **E4** | Reproducible build behavior, rules, or telemetry | Can support a decision |
| **E3** | Recorded target-player behavior across sessions | Strong but context-bound |
| **E2** | Interviews or surveys tied to observed behavior | Explanatory, not decisive alone |
| **E1** | Stakeholder claims, market anecdotes, community opinion | Generates hypotheses |
| **E0** | Designer intuition or model inference | Direction only |

Every conclusion also declares high / medium / low confidence and names **what evidence would change it**.

### Output contract

Unless reference-only mode is requested, the skill returns:

1. Strong diagnosis, evidence grade, and confidence.
2. One observable player micro-scene.
3. Current decision and single largest risk.
4. Three to five selected lenses, each stating what it could disprove.
5. A causal system finding.
6. The cheapest falsifiable artifact.
7. Success, failure, guardrail, and stop-line behaviors.
8. Pass, mixed, and fail decision branches.
9. Unknowns, counterevidence, and foreseeable responsibility.

### Example prompts

```text
Use $jesse-schell-game-design-master to review this playtest transcript. Separate
observation, interpretation, counterevidence, and decision. Name the evidence we
still lack and design the next falsifiable test.
```

```text
Use $jesse-schell-game-design-master to diagnose our soft launch. D1 retention is
healthy, but third-session churn, payment complaints, and guild harassment are all
rising. Find the single largest risk without ignoring economy or community safety.
```

---

## Quick Start

### Install from GitHub

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/SherryCW/jesse-schell.git \
  ~/.codex/skills/jesse-schell-game-design-master
```

Already cloned? Update it with:

```bash
git -C ~/.codex/skills/jesse-schell-game-design-master pull
```

Start a new Codex session, then invoke:

```text
$jesse-schell-game-design-master
```

### Install from a local copy

```bash
mkdir -p ~/.codex/skills/jesse-schell-game-design-master
cp -R . ~/.codex/skills/jesse-schell-game-design-master
```

### Verify the skill

```bash
python3 ~/.codex/skills/.system/skill-creator/scripts/quick_validate.py \
  ~/.codex/skills/jesse-schell-game-design-master
```

---

## Repository Map

```text
jesse-schell/
├── SKILL.md                  # Core diagnosis and decision protocol
├── agents/
│   └── openai.yaml          # Codex UI metadata
├── references/
│   ├── routing.md           # Route by problem signal and project stage
│   ├── lenses.md            # Complete numbered lens index
│   ├── deliverables.md      # Prototype, playtest, economy, and decision artifacts
│   ├── cheatsheet.md        # Fast decision rules
│   ├── glossary.md          # Concise terminology
│   ├── patterns.md          # Reusable design patterns
│   └── chapters/            # 35 chapter files, loaded only when relevant
├── test-prompts.json        # Trigger and behavior smoke tests
├── ABOUT.md                 # Synthesis and validation record
└── README.md                # You are here
```

The repository uses progressive disclosure:

1. **Skill metadata** determines when it should trigger.
2. **`SKILL.md`** loads the compact operating protocol.
3. **References** load only the relevant lens, artifact, or chapter.

This keeps the working context focused while preserving depth when a decision requires it.

---

## Design Principles / 设计原则

1. **Design the player's experience, not a feature inventory.** 设计玩家体验，而不是功能库存。
2. **Use lenses to expose blind spots; use risk to set priority.** 用透镜发现盲点，用风险决定优先级。
3. **Treat intuition and player models as hypotheses.** 把直觉和玩家模型当作假设。
4. **Require behavioral evidence before raising confidence.** 提升置信度之前，先要求行为证据。
5. **Track consequences beyond author intent.** 追踪超出设计者意图的可预见后果。
6. **Let stronger evidence defeat a more elegant story.** 让更强证据推翻更漂亮的解释。

---

## Boundaries / 使用边界

- This project is an independent practical synthesis and is not affiliated with, endorsed by, or representative of Jesse Schell.<br>
  本项目是独立的实践性综合，不隶属于 Jesse Schell，也不代表或冒充其本人观点。
- It does not replace direct reading of the original book or qualified legal, safety, accessibility, child-protection, privacy, health, or ethics review.<br>
  它不能替代原书阅读，也不能替代法律、安全、无障碍、未成年人保护、隐私、健康或伦理方面的专业审查。
- Current laws, platform policies, markets, and safety standards must be checked against contemporary primary sources.<br>
  涉及现行法律、平台政策、市场与安全标准时，应核实当代一手资料。
- Engagement, conversion, feature count, visual polish, and novelty are not treated as proof of player value.<br>
  参与度、转化率、功能数量、视觉精度和新奇感均不被自动视为玩家价值的证明。

---

<div align="center">

### 好游戏不是被“想对”的，而是被一次次诚实地证伪出来的。
### Great games are not reasoned into existence. They survive honest attempts to prove them wrong.

If this system improves one hard design decision, consider starring the repository.<br>
如果它帮你做对了一次艰难的设计决策，欢迎点亮 ⭐。

</div>
