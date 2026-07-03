---
type: entity
title: "code-review-graph"
created: 2026-07-02
updated: 2026-07-02
tags:
  - entity
  - tool
  - ai-tool
  - mcp
  - code-intelligence
  - context-reduction
status: evergreen
related:
  - "[[Các repo cần chú ý - Phân loại]]"
entity_type: product
role: Local-first code intelligence graph cho MCP và CLI
---

# code-review-graph

Local-first code intelligence graph cho MCP và CLI. Repository: [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)

## Chức năng chính

Parse codebase thành AST với Tree-sitter, lưu dưới dạng graph (nodes: functions, classes, imports; edges: calls, inheritance, test coverage). Khi file thay đổi, tính "blast radius" — set files tối thiểu AI cần đọc thay vì scan toàn bộ project.

## Chức năng phụ

- Giảm context ~82x median (range 38x–528x) so với đọc toàn corpus
- Hỗ trợ 30+ ngôn ngữ (Python, JS/TS, Go, Rust, Java, C/C#, Ruby, Kotlin, Swift, SQL, Vue, Svelte, Jupyter...)
- VS Code extension; build lần đầu ~10s cho project 500 file, sau đó watch mode incremental
