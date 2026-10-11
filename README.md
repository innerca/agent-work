# agent-work

A bilingual delivery prompt for capable agents: clarify outcomes, exercise judgment, verify evidence, and own the final result.

面向高能力 Agent 的双语交付 Prompt：明确目标、自主判断、验证证据，并对最终结果负责。

[中文 Prompt](PROMPT.zh-CN.md) · [English Prompt](PROMPT.en.md)

## What this is / 这是什么

`agent-work` is a delivery charter for agents working on long-running, open-ended tasks. It focuses on outcome ownership, scope discipline, pragmatic engineering, evidence-based verification, and maintainable delivery.

这是一份面向长任务和开放性任务的交付章程。它强调结果负责、范围控制、务实工程、基于证据的验证，以及可维护的交付。

The prompt assumes that the agent can think and make decisions independently. It describes the quality and judgment expected from the agent rather than reducing the work to a rigid checklist.

这份 Prompt 假设 Agent 能够独立思考和判断。它描述的是对 Agent 的工作质量和判断力的要求，而不是把工作压缩成机械的步骤清单。

## Usage / 使用方式

Use the language version that fits your agent and place it in the system or developer instructions for a project. Adapt it to the project's existing constraints, tools, and approval boundaries.

选择适合 Agent 的语言版本，将其放入项目的 system 或 developer instructions 中，并根据项目现有约束、工具和审批边界进行调整。

## Principles / 核心原则

- Keep complexity proportional to the actual goal.
- Understand and reuse the existing project before introducing change.
- Align on decisions that materially affect scope, interfaces, data, UX, security, or architecture.
- Validate the result with appropriate evidence and disclose what remains unverified.
- Keep documentation, observability, and operational support proportional to the project.
- Let the primary agent own integration, verification, and delivery.

- 让复杂度与真实目标相匹配。
- 先理解并复用现有项目，再引入变化。
- 对会显著影响范围、接口、数据、用户体验、安全或架构的决策达成一致。
- 用适当的证据验证结果，并明确说明仍未验证的部分。
- 让文档、可观测性和运行支持与项目实际规模相匹配。
- 由主 Agent 负责整合、验证和交付。

## License

[MIT License](LICENSE)
