# 2 分钟开始｜Start Here

你不需要安装代码，也不需要理解多智能体框架。选择一个真实问题，把对应的 Community Agent 复制到你常用的 AI 工具中，就可以完成第一次体验。

No installation or agent-framework knowledge is required. Pick a real problem, copy one Community Agent into your preferred AI tool, and run your first task.

## 先按目标选择入口

| 你现在想解决什么 | 建议先用 | 第一次应该得到什么 |
|---|---|---|
| 判断一个产品想法是否值得做 | [市场研究员](./community-agents/market-researcher.md) | 需求信号、替代方案、差异化假设和待验证问题 |
| 明确用户是谁、为什么会使用 | [用户研究员](./community-agents/user-researcher.md) | 用户分群、关键痛点、访谈问题和证据缺口 |
| 把想法收敛成 MVP | [产品策略师](./community-agents/product-strategist.md) | 定位、核心场景、MVP 范围、非目标和验证计划 |
| 建立一周内容计划 | [内容策划师](./community-agents/content-planner.md) | 内容支柱、选题、发布节奏和复盘指标 |
| 判断办公流程是否值得自动化 | [办公流程分析师](./community-agents/office-process-analyst.md) | 当前流程、瓶颈、自动化机会、风险和优先级 |
| 检查方案有没有逻辑或范围风险 | [风险审核员](./community-agents/risk-reviewer.md) / [项目范围审核员](./community-agents/project-scope-reviewer.md) | 证据缺口、关键风险、验收标准和下一步决策 |

## 第一次运行

1. 打开上表中的 Agent 文件并复制全部内容。
2. 把它粘贴到你常用的 AI 工具，接着填写下面的任务卡。
3. 先要求它完成一项决策，不要一次塞入整个项目。
4. 检查事实、假设和待验证项是否分开，再决定是否采用。

```text
项目/业务：
目标用户：
我现在需要决定：
已有证据或材料：
时间、预算、合规等约束：
明确不做什么：

请按照岗位文件中的交付格式输出。
不要把推测写成事实；请分别标注：已有证据、合理假设、待验证问题。
最后给出最小的下一步行动，以及我需要亲自确认的决定。
```

## 怎样算一次有价值的输出

- 它针对你的具体目标，而不是复述通用知识。
- 事实、假设和待验证内容可以清楚区分。
- 输出包含明确的取舍、非目标与风险，而不只是“可以做什么”。
- 下一步行动足够小，可以立即执行或验证。
- 关键决定仍由你审核，而不是由 Agent 替你拍板。

如果你想看完整结构，可阅读 [AI 食谱产品验证脱敏案例](./examples/ai-recipe-validation/README.md)。它演示了市场研究员、用户研究员、产品策略师和风险审核员如何手动接力。

## 什么时候需要付费邀请版

Community Pack 适合单次使用和手动串联。当你开始反复复制上下文、手动挑选岗位、汇总版本和安排审核时，付费邀请版才体现价值：AI CEO 负责访谈和规划，系统进行能力匹配与多模型调度，并保存项目状态、成果版本、审核和修改记录。

付费版还提供更完整且持续扩展的 Agent 队伍；本仓库不公开完整 AI CEO、自动编排、多模型路由、Skill 进化、长期记忆和商业平台源代码。

[申请邀请码](https://clawhireai.com/?utm_source=github&utm_medium=start_here&utm_campaign=invite_application) · [查看能力边界](./README.md#付费邀请版多了什么) · [提出一个场景](https://github.com/clawhire-ai/clawhire/discussions)

---

## English quick start

Choose the role closest to the decision in front of you: [Market Researcher](./community-agents/market-researcher.md), [User Researcher](./community-agents/user-researcher.md), [Product Strategist](./community-agents/product-strategist.md), [Content Planner](./community-agents/content-planner.md), [Office Process Analyst](./community-agents/office-process-analyst.md), or [Risk Reviewer](./community-agents/risk-reviewer.md).

Copy the full role file into your preferred AI tool, then add:

```text
Project/business:
Target user:
Decision I need to make now:
Evidence or source material:
Time, budget, compliance or other constraints:
Explicit non-goals:

Follow the deliverable format in the role file. Separate evidence, assumptions,
and open questions. End with the smallest useful next action and the decisions
that still require my approval.
```

The Community Pack is stateless and manually coordinated. Use hosted ClawHire when you need AI CEO discovery, persistent project context, automatic role and capability matching, multi-model orchestration, reviews and continued revisions.

If this starting path is useful, **Star the repository** so you can find it again and follow new public Agents, Lite workflows and sanitized examples.
