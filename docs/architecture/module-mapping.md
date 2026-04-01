# Module Mapping

## English

This document maps the public sourcemap findings to the portfolio vocabulary used by AICode-Nexus: commands, tools, services, context, coordinator, plugins, and skills.

| Public clue | Interpretation in this portfolio | Lands in repo |
| --- | --- | --- |
| `commands` | user-facing task surface and CLI verbs | `claude-code-runtime` |
| `tools` | executable capability boundary | `claude-code-runtime`, `operator-kernel` |
| `services` | provider, transport, and support services | `claude-code-runtime` |
| `context` | session and execution state | `claude-code-runtime` |
| `coordinator` | multi-step orchestration and planning | `operator-kernel` |
| `plugins` | extension lifecycle surface | `claude-code-runtime`, `operator-kernel` |
| `skills` | docs and implementation guidance patterns | `claude-code-playbook` |

The goal is not to reproduce every path literally. The goal is to preserve useful architectural boundaries while keeping the implementation legally and technically clean.

## 中文

本文把公开 sourcemap 暴露出的模块线索，映射到 AICode-Nexus 的项目语言里：commands、tools、services、context、coordinator、plugins、skills。

| 公开线索 | 在本项目集中的解释 | 对应仓库 |
| --- | --- | --- |
| `commands` | 面向用户的任务入口和 CLI 命令面 | `claude-code-runtime` |
| `tools` | 可执行能力边界 | `claude-code-runtime`、`operator-kernel` |
| `services` | provider、transport 与支撑服务 | `claude-code-runtime` |
| `context` | 会话与执行状态 | `claude-code-runtime` |
| `coordinator` | 多步骤编排与计划执行 | `operator-kernel` |
| `plugins` | 扩展生命周期接口 | `claude-code-runtime`、`operator-kernel` |
| `skills` | 文档化的经验与实现指导 | `claude-code-playbook` |

我们不是逐字逐目录复刻，而是保留有价值的架构边界，同时把实现维持在合法、可公开、可维护的范围内。
