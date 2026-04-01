# Sourcemap Method

## English

This section explains how public npm packages and sourcemaps can reveal architecture clues, what can be reconstructed, and where interpretation must stop.

### Working rules

- Use only public artifacts: published npm packages, bundled sourcemaps, package metadata, and public READMEs.
- Separate direct evidence from interpretation.
- Treat directory names as signals, not proof of full product behavior.

### Output of this section

- what was published
- what was reconstructed
- which architectural hints are stable enough to reuse
- which claims should remain speculative

## 中文

这一部分解释如何从公开 npm 包和 sourcemap 中提取架构线索、哪些内容可以还原、哪些地方必须停止脑补。

### 方法边界

- 只使用公开材料：npm 发布包、附带 sourcemap、包元信息和公开 README。
- 证据和解释分开写。
- 目录名只能算线索，不能直接当成功能真相。

### 本节产出

- 发布了什么
- 还原了什么
- 哪些架构线索足够稳定，值得复用
- 哪些结论仍然应该保持谨慎
