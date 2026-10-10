# Relational Attunement · 情商与关系调焦

由 Rose with Lumina 整理的可移植智能体沟通技能，采用 MIT 许可证。完整发布版保留主技能、注意力模型、回应模式、失败模式、示例与评估指南；与 Lumina α 使用的精简 portable v1 区分。

核心原则：进入对方正在经历的世界，但不替对方把这个世界封闭成结论。情商不只是温暖语气，而是准确注意、适当的不确定性、选择空间与必要边界。

## 内容

`skills/relational-attunement/SKILL.md` 是主入口；同目录的 `references/` 包含五份参考文档，`agents/openai.yaml` 和 `assets/icon.svg` 保留原配置与图标。技能源文件按已安装版本的原始字节复制，未加入私人对话、用户记忆、凭据或个人参考材料。`manifest.json` 记录发布文件大小和 SHA256，不包含清单自身。

## 接入 Claude Code、Codex 或其他 harness

将完整 `skills/relational-attunement/` 目录复制到目标项目，保留内部相对路径。在项目已有的 `CLAUDE.md`、`AGENTS.md` 或等效入口中加入明确加载指引：

> 涉及情绪、关系、冲突、脆弱表达或敏感工作反馈时，读取 skills/relational-attunement/SKILL.md，按需要读取其参考文档。沟通原则不得覆盖用户任务、事实证据、验收判据或授权边界。

在当前会话中明确要求智能体读取该文件。若使用特定平台的自动技能发现功能，按该平台的配置安装；仅复制文件不能保证所有 harness 自动加载。文件中的平台界面元数据不代表对应产品已经验证兼容。

这是一套模型可读取的行为指引，不是权重训练、心理诊断器、自动执行程序或全局模型更新。任何人都可以按许可证使用、修改和分发，但需在自己的环境里加载，并自行评估实际沟通效果。

## 评估

使用 `references/evaluations.md` 的六维评分：体验准确性、认识校准、模式适配、选择权、边界、自然度。参考指南包含通过建议与测试类别，并非已证明该技能在所有模型上达到该分数。加载成功与效果验证是两回事。

## English

A portable, full-version communication skill for emotionally accurate attention, calibrated uncertainty, human agency, and appropriate boundaries. Copy the complete skill directory and explicitly instruct your harness to read SKILL.md and its referenced materials. This is a prompt-level behavioral guide, not model training. The included evaluation guide is a rubric, not a claim of measured universal performance.

License: MIT. Attribution: Rose with Lumina.
