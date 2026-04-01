# claude-code-playbook

Architecture notes, sourcemap research, and implementation guides for the AICode-Nexus portfolio.

## Disclaimer

This repository studies public artifacts related to `@anthropic-ai/claude-code`, including community sourcemap analysis.

- It is unofficial.
- It is for research, architecture study, and implementation guidance.
- It does not claim to represent Anthropic's internal repository structure.

本仓库研究 `@anthropic-ai/claude-code` 的公开材料，包括社区的 sourcemap 解析成果。

- 它是非官方的。
- 它服务于研究、架构分析和实现指导。
- 它不代表 Anthropic 的内部仓库结构。

## Reading Order

1. Start here: portfolio overview and repo relationships
2. Read the sourcemap method and architecture mapping docs
3. Explore `claude-code-runtime` to see the compatible runtime in code
4. Move to `operator-kernel` to understand the extracted platform direction

1. 从这里开始，先理解三仓关系
2. 阅读 sourcemap 方法与架构映射
3. 查看 `claude-code-runtime` 的兼容实现
4. 再进入 `operator-kernel` 理解平台化演进

## Repository Roles

- [AICode-Nexus/claude-code-runtime](https://github.com/AICode-Nexus/claude-code-runtime): runnable compatibility runtime
- [AICode-Nexus/operator-kernel](https://github.com/AICode-Nexus/operator-kernel): new-brand agent kernel platform

## Content Map

- [docs/sourcemap/README.md](./docs/sourcemap/README.md)
- [docs/architecture/module-mapping.md](./docs/architecture/module-mapping.md)
- [docs/runtime-guide/README.md](./docs/runtime-guide/README.md)
- [docs/operator-evolution/README.md](./docs/operator-evolution/README.md)
- [docs/articles/zh/README.md](./docs/articles/zh/README.md)
- [docs/articles/en/README.md](./docs/articles/en/README.md)

## Roadmap

See [ROADMAP.md](./ROADMAP.md).
