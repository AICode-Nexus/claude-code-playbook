# Runtime Guide

## English

Use this section to understand how `claude-code-runtime` is structured, how to run it, and how to extend it without confusing compatibility work with official product claims.

### Current runtime contract

- `ProviderAdapter`: normalizes provider planning behavior
- `CommandRegistry`: stable command discovery and dispatch
- `ToolContract`: executable capability units
- `SessionContext`: task-scoped execution state
- `PluginHook`: extension lifecycle around runtime execution

### Current workflow

1. CLI parses a command
2. runtime loads config and picks a provider
3. provider returns a tool-oriented plan
4. runtime executes tools in order
5. plugins observe the execution lifecycle

## 中文

本部分用于说明 `claude-code-runtime` 的结构、运行方式，以及如何在不混淆“兼容实现”和“官方产品”的前提下扩展它。

### 当前稳定抽象

- `ProviderAdapter`：统一 provider 规划行为
- `CommandRegistry`：稳定的命令发现与分发
- `ToolContract`：可执行能力单元
- `SessionContext`：任务级执行状态
- `PluginHook`：围绕运行时执行的扩展生命周期

### 当前执行流

1. CLI 解析命令
2. runtime 读取配置并选择 provider
3. provider 返回面向 tool 的执行计划
4. runtime 依次执行工具
5. plugin 观察整个执行生命周期
