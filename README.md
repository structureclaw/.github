# StructureClaw

AI-assisted structural engineering organization for AEC (Architecture, Engineering, Construction) workflows.

We turn natural-language engineering intents into verifiable, traceable, and reproducible analysis workflows, helping teams move from problem statements to analysis artifacts and reports.

<details>
<summary>中文说明</summary>

面向 AEC（Architecture, Engineering, Construction）场景的 AI 辅助结构工程组织。

我们致力于把自然语言需求转化为可验证、可追踪、可复现的工程分析流程，帮助团队从“描述问题”走到“形成分析与报告产物”。

</details>

## What We Build

- Conversational engineering workflow from natural language to structural analysis outputs
- Unified orchestration loop: draft -> validate -> analyze -> code-check -> report
- Integrated platform combining web app, API services, and analysis engine
- Regression and contract checks for repeatable and auditable engineering computation

<details>
<summary>中文说明</summary>

- 构建对话式工程工作流：自然语言输入到结构分析产出
- 打通统一编排闭环：draft -> validate -> analyze -> code-check -> report
- 将 Web 应用、API 服务和分析引擎整合为一致的工程平台
- 提供回归与契约校验能力，确保工程计算流程可重复、可验证

</details>

## Core Capabilities

- Engineering intent understanding: map expert intent to executable tasks
- Analysis as services: standardized validation, conversion, analysis, and code checks
- Decoupled multi-layer architecture: frontend interaction, backend orchestration, core engine
- Delivery-oriented artifact chain: reports, metrics, and analysis artifacts are auditable

<details>
<summary>中文说明</summary>

- 工程语义理解：将工程师意图映射为可执行任务
- 结构分析服务化：校核、转换、分析与规范检查标准化
- 多层协同架构：前端交互、后端编排、核心分析引擎解耦协作
- 面向交付的产物链路：报告、指标与分析工件可审计

</details>

## Architecture

```text
frontend (Next.js)
	-> backend (Fastify + Prisma + Agent orchestration)
	-> core (FastAPI analysis engine)
	-> reports / metrics / artifacts
```

<details>
<summary>中文说明</summary>

以上为技术架构概览。

</details>

## Repositories

- [Structureclaw](https://github.com/structureclaw/Structureclaw)
  A monorepo workspace that integrates frontend, backend, and core structural analysis engine.

<details>
<summary>中文说明</summary>

- [Structureclaw](https://github.com/structureclaw/Structureclaw)
  AI-assisted structural engineering workspace，包含前端、后端与核心分析引擎的一体化实现。

</details>

## Typical Workflow

1. Users provide engineering requirements in natural language
2. The system drafts and validates structured tasks
3. The analysis engine runs validation, conversion, and analysis
4. Code checks are applied with traceable results
5. Reports and engineering artifacts are produced for review and archival

<details>
<summary>中文说明</summary>

1. 用户输入工程需求（自然语言）
2. 系统生成并校验结构化任务草案
3. 调用分析引擎执行验证、转换与分析
4. 进行规范检查并生成可追踪结果
5. 输出报告与工程产物供复核与归档

</details>

## Engineering Principles

- Skills are enhancement layers, not the only execution path
- When selected skills do not match, fall back to generic no-skill modeling
- User-facing content supports both Chinese and English
- Keep module boundaries explicit across frontend, backend, and core

<details>
<summary>中文说明</summary>

- 技能层是增强机制，不是唯一执行路径
- 选中技能不匹配时，回退到通用无技能建模流程
- 用户可见内容同时支持中文与英文
- 保持 frontend、backend、core 的模块边界清晰

</details>

## Contributing

Contributions via Issues and Pull Requests are welcome.

Before submitting changes, please review the contribution guide and docs in the target repository to align with engineering flow, regression checks, and API contracts.

<details>
<summary>中文说明</summary>

欢迎通过 Issue 和 Pull Request 参与建设。

在提交改动前，建议先阅读目标仓库中的贡献指南与文档说明，确保改动与工程流程、回归校验和接口契约保持一致。

</details>

## License

Each repository is governed by its own LICENSE file.

<details>
<summary>中文说明</summary>

各仓库许可证请以对应项目内 LICENSE 文件为准。

</details>