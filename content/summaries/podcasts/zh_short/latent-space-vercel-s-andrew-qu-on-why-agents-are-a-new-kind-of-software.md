# Vercel's Andrew Qu on why agents are a new kind of software

- Type: podcast
- Profile: zh_short
- Model: deepseek-v4-pro
- Generated: 2026-07-04T22:54:25.671530+00:00
- Channel: Latent Space
- Source: https://www.latent.space/p/vercel-agents-new-software

## Summary

Vercel 首席软件官 Andrew Qu 认为，智能体（Agent）是一种全新的软件形态，其交互、输出和基础设施需求远比传统 Web 应用动态。Vercel 因此构建了智能体框架 `eve`，并将自身平台逐步转变为智能体。

**核心要点**
- **智能体是新软件类别**：它们不可预测，需要上下文、工具、可恢复性和长时间运行等不同原语。
- **技能（Skills）是即时纠错层**：模型知识过时，技能可作为便携式知识，实时引导智能体使用产品的最新版本，避免其依赖已弃用的旧信息。
- **构建面向智能体可读的网络**：Vercel 已开始检测智能体请求，并直接提供 Markdown 格式内容，而非强迫其解析为人类设计的 HTML。
- **人机回环需按任务选择**：并非所有任务都需人类介入，定义清晰的任务可自主循环，而精细工程则需人类适时纠偏。

**值得展开的细节**
- `eve` 框架源于 Vercel 内部构建智能体（如 v0）时积累的实践，包括文件系统智能体、技能、压缩和子智能体等原语。
- 智能体特别适合需要一定推理的重复性任务，如法律合同初审、营销回顾和数据查询。
- 未来重点方向是多人协作的智能体开发，解决团队成员间的上下文共享问题。

**对 AI 与产品的启示**
- 产品方应主动审计并更新旧文档，同时发布技能文件来“前向纠正”模型，确保智能体能准确使用产品。
- 网站和平台需为智能体流量做好准备，提供结构化、机器可读的接口，这将成为新的产品竞争力。
- 智能体平台化趋势明显，Vercel 正将可观测性、评估等功能内置，降低开发者构建智能体的门槛。

**来源**：[Latent Space](https://www.latent.space/p/vercel-agents-new-software)
