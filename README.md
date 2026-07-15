# Jesse Schell Game Design Master

一个把 Jesse Schell《游戏设计艺术》第 3 版的 **35 章、112 个编号透镜**，与风险优先原型、行为试玩证据、生产约束、商业闭环、社群治理和设计责任结合起来的 Codex skill。

它不是透镜清单，也不模仿 Jesse Schell 本人。它把游戏设计问题压缩成一个当前决策和一个最大风险，选择 3–5 个可能推翻判断的透镜，并交付可失败实验、行为阈值和下一决策。

## 核心增强

- 按问题和项目阶段路由透镜，而非全量扫描。
- 使用 E0–E4 证据等级和高/中/低置信度。
- 区分首次、第三次和第三十次体验。
- 明确透镜冲突裁决：安全 → 体验 → 证据 → 系统 → 商业 → 偏好。
- 提供体验简报、风险表、原型卡、试玩证据表、价值—资金—影响图和决策日志。
- 将 35 章和 112 个透镜放入按需加载的 references，保持主工作流精简。

## 使用示例

```text
Use $jesse-schell-game-design-master to diagnose my game's largest experience risk,
select the highest-value lenses, and design the next falsifiable prototype.
```

## 安装

```bash
mkdir -p ~/.codex/skills
cp -R . ~/.codex/skills/jesse-schell-game-design-master
```

重启 Codex 会话后使用 `$jesse-schell-game-design-master`。

## 结构

- `SKILL.md`：大师级诊断与决策协议
- `agents/openai.yaml`：Codex UI 元数据
- `references/routing.md`：问题与项目阶段路由
- `references/deliverables.md`：可复用设计交付物
- `references/lenses.md`：完整透镜索引
- `references/chapters/`：35 章按需知识库
- `test-prompts.json`：冒烟测试场景

## 边界

这是公开框架的实践性综合，不代表 Jesse Schell 本人意见。涉及当前法律、平台规则、市场、安全、健康、未成年人、隐私或 AI 权利时，应核实当代一手资料并引入合格审查者。
