# Jesse Schell · 游戏设计大师 Skill

一个以 Jesse Schell 公开游戏设计框架和《游戏设计艺术》第 3 版为基础的综合型 Codex/Claude skill。

它把“体验优先、透镜式诊断、风险优先原型、试玩证据”与场景、玩家、机制、平衡、谜题、界面、节奏、叙事、社群、技术、商业和责任模块合并为一条可执行工作流。

## 核心工作方式

每次只做四件关键事：

1. 写出暂定体验问题。
2. 锁定唯一最大风险假设。
3. 选择 3–5 个能改变判断的 lenses。
4. 设计可失败的最小原型，并用可观察行为决定继续、修改、替代或停止。

它不会机械调用全部方法，也不会用功能数量、画质、技术新奇或单次“喜欢吗”投票代替体验证据。

## 覆盖范围

- 本质体验、场景适配、五种声音与客户欲望
- 玩家模型、动机、机制语法、多轴平衡与谜题可解性
- 界面反馈、兴趣曲线、互动叙事、间接控制与角色关系
- 临场感、社群治理、协作设计文档与六问试玩
- 技术成熟度、资金流商业模型与影响责任链

## 安装

将 `SKILL.md` 放入个人 skill 目录，并保留目录名 `jesse-schell-perspective`，以继续使用 `$jesse-schell-perspective`：

```bash
mkdir -p ~/.codex/skills/jesse-schell-perspective/agents
cp SKILL.md ~/.codex/skills/jesse-schell-perspective/SKILL.md
cp agents/openai.yaml ~/.codex/skills/jesse-schell-perspective/agents/openai.yaml
```

## 设计边界

本 skill 模拟公开方法，不代表 Jesse Schell 本人意见。透镜是实践启发式，不是统一科学理论。缺少 build、录像、规则、版本、目标玩家和行为数据时，结论必须标注为暂定或未知；涉及未成年人、隐私、健康、安全、付费操控和 AI 版权时，需要当代资料与专业审查。

## 文件

- `SKILL.md`：主 skill
- `agents/openai.yaml`：调用接口
- `test-prompts.json`：冒烟测试
- `ABOUT.md`：方法来源、合并决策和质量记录
