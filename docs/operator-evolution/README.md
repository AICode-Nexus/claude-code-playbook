# Operator Evolution

## English

This section explains how the learnings from `claude-code-runtime` are abstracted into the new-brand `operator-kernel` platform.

### Extraction logic

- keep CLI compatibility concerns in `claude-code-runtime`
- move reusable planning and execution primitives into `operator-kernel`
- treat shells as replaceable adapters around the kernel

### Stable kernel abstractions

- `Kernel`
- `Task`
- `ExecutionPlan`
- `Tool`
- `Provider`
- `Plugin`

## 中文

本部分解释如何把 `claude-code-runtime` 中沉淀出来的经验抽象成全新品牌的 `operator-kernel` 平台。

### 提炼原则

- CLI 兼容性问题继续留在 `claude-code-runtime`
- 可复用的规划与执行原语迁移到 `operator-kernel`
- 各类壳层都应该被视作内核之外的可替换适配器

### 当前稳定内核抽象

- `Kernel`
- `Task`
- `ExecutionPlan`
- `Tool`
- `Provider`
- `Plugin`
