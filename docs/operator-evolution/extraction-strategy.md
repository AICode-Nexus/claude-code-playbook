# Extraction Strategy

## English

`operator-kernel` should not be a rename of `claude-code-runtime`. It should be the layer that keeps only the reusable planning, tool orchestration, provider abstraction, and plugin mechanics while leaving compatibility UX in the runtime repository.

## 中文

`operator-kernel` 不应该只是 `claude-code-runtime` 的换皮。它应该只保留可复用的计划执行、工具编排、provider 抽象和插件机制，把兼容性导向的 CLI 体验继续留在 runtime 仓库。
