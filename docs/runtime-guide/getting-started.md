# Getting Started With claude-code-runtime

## English

Install dependencies, run tests, and execute the runtime with a task string. Use this guide to understand the difference between the public compatibility surface and future platform extraction into `operator-kernel`.

The runtime now supports two execution modes:

- default mode: local deterministic planning, no credentials required
- `--live` mode: calls Anthropic or an OpenAI-compatible API using environment variables

## 中文

安装依赖、运行测试，然后用一个任务字符串启动 runtime。本指南用于帮助读者区分“公开的兼容运行时表面”与未来会抽取到 `operator-kernel` 的平台内核能力。

当前 runtime 有两种执行模式：

- 默认模式：本地确定性规划，不需要凭据
- `--live` 模式：通过环境变量调用 Anthropic 或 OpenAI-compatible API

建议同时为不同 provider 设独立模型变量，例如 `ANTHROPIC_MODEL` 和 `OPENAI_MODEL`，不要强行共用同一个模型名。
