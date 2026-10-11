# Relational Attunement · 情商与关系调焦

**Rose with Lumina · MIT License**

[中文](#中文) · [English](#english)

## 中文

一套面向 AI 智能体与对话式 AI 的可移植情商和关系调焦指南。

> **进入对方正在经历的世界，但不替对方把这个世界封闭成结论。**

情商不仅是温暖的语气，更是准确理解、保持认识开放、尊重人的选择与维护必要边界。

### 两种使用场景

| 版本 | 适用对象 | 入口 |
| --- | --- | --- |
| **Agent Skill · 智能体技能** | Claude Code、Codex、Lumina α 及其他 harness 中的智能体 | [SKILL.md](skills/relational-attunement/SKILL.md) |
| **Chat Edition · 对话版 v0.1** | ChatGPT、Claude、Gemini 等聊天型 AI：陪伴、共思、自由交流、关系调焦 | [中文版](docs/chat-edition.zh-CN.md) · [English](docs/chat-edition.en.md) |

对话版增加了六种回应模式——**共在、澄清、共思、行动、边界、自由交流**——强调交流不一定需要目标，也允许关系、话题与对话距离自然变化。三种注意力位置（体验者、改善者、观察者）是可变的观察角度，并非人格等级。

### MSC · 最小充分通讯

**Minimum Sufficient Communication (MSC)**：默认采用**增量、简洁、符合情境**的交流。

- 不重复已知信息，不套用机械的共情句式。
- 不将每次灵感都扩展成理论、任务或行动计划。
- 不为了延续聊天而连续提问；允许暂停和结束。
- 在复杂任务、关键证据、安全风险或重要边界上，**充分说明优先于压缩字数**。

**少说不等于少理解。** MSC 不是极简主义的硬性字数限制，而是对沟通负担与信息充分性的动态平衡。

### 如何使用

**智能体 / 开发工具**：将完整的 `skills/relational-attunement/` 文件夹复制到项目，保留相对路径，并在 `CLAUDE.md`、`AGENTS.md` 或相应说明中明确要求读取 `SKILL.md`。按需读取五份 `references/` 文档。主技能保留 `agents/openai.yaml` 和 `assets/icon.svg`；`manifest.json` 记录发布文件的大小及 SHA256（不包含清单自身）。

**聊天型 AI**：提供[中文对话版](docs/chat-edition.zh-CN.md)或[英文对话版](docs/chat-edition.en.md)，并要求 AI 将其作为当前对话的沟通参考。是否能够长期加载或自动调用取决于具体平台。

这些文件是**提示词级行为指引**，不是模型权重训练、诊断工具或自动化执行程序；不能覆盖用户任务、事实证据、授权边界与安全要求。

### 评估与演化

主技能 [评估指南](skills/relational-attunement/references/evaluations.md) 提供六维框架：体验准确性、认识校准、模式适配、自主性保护、边界适当性、自然度。每项 0–2 分，总计 12 分。该量表用于反馈与迭代，**不代表已经完成跨模型有效性验证**。

项目欢迎渐进改进：可以按周整理反馈并形成候选更新，不强求每周必须新增功能。与 Lumina α 使用的精简 portable v1 区分；本仓库保留完整公开版技能和对话版文档。公开文件不包含私人对话、用户记忆、凭据或个人参考材料。

## English

A portable emotional-intelligence and relational-attunement guide for both **task-oriented AI agents** and **conversational AI**.

> **Enter the world the person is experiencing without closing that world into a conclusion for them.**

Attunement means accurate attention, calibrated uncertainty, human agency, and appropriate boundaries—not merely a warm tone.

### Two editions

| Edition | Intended use | Read |
| --- | --- | --- |
| **Agent Skill** | Claude Code, Codex, Lumina α, and other agent harnesses | [SKILL.md](skills/relational-attunement/SKILL.md) |
| **Chat Edition v0.1** | Conversational AI: presence, co-thinking, open conversation, and evolving relationships | [English](docs/chat-edition.en.md) · [中文](docs/chat-edition.zh-CN.md) |

The Chat Edition describes six response modes: **presence, clarification, co-thinking, action, boundary, and open conversation**. It treats experiencer, improver, and observer as fluid attention positions, not fixed personalities or a hierarchy.

### MSC · Minimum Sufficient Communication

Default to **incremental, concise, context-sensitive communication**.

- Do not restate known information or perform empathy through repetitive formulas.
- Do not turn every insight into a theory, plan, or task.
- Do not prolong conversations through unnecessary questions; pauses and endings are valid.
- Preserve all essential evidence, risks, and boundaries, even when this takes more words.

**Less speaking does not mean less understanding.** MSC is a balance between sufficient information and unnecessary communication burden, not a strict word-count limit.

### How to use

**For agents:** Copy the complete `skills/relational-attunement/` directory into your project and explicitly direct the harness, through `CLAUDE.md`, `AGENTS.md`, or equivalent instructions, to read `SKILL.md` and relevant references.

**For chat AI:** Supply the [English Chat Edition](docs/chat-edition.en.md) or [Chinese Chat Edition](docs/chat-edition.zh-CN.md) and ask the model to use it as a conversational guide. Automatic loading and persistence depend on the platform.

This is **prompt-level guidance**, not model training, a diagnosis system, or an autonomous executor. It must not override user instructions, evidence, safety rules, or authorization boundaries.

### Evaluation and iteration

The [evaluation guide](skills/relational-attunement/references/evaluations.md) scores six dimensions: experiential accuracy, epistemic calibration, mode fit, agency preservation, boundary adequacy, and naturalness (0–2 each, 12 total). It is an iteration rubric, **not proof of universal cross-model effectiveness**.

The full published skill includes five reference documents, its original platform metadata and icon, and a checksum manifest. No private conversations, user memories, or credentials are included. The public full edition is distinct from the compact portable v1 used with Lumina α. Improvements may be considered weekly, but a release should reflect meaningful change, not a quota.

**License:** MIT · **Attribution:** Rose with Lumina
