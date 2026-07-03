---
type: entity
title: "superpowers"
created: 2026-07-02
updated: 2026-07-02
tags:
  - entity
  - skill
  - agent-skill
  - methodology
  - claude-code
status: evergreen
related:
  - "[[Các repo cần chú ý - Phân loại]]"
entity_type: product
role: Agentic skills framework & software development methodology
---

# superpowers

Framework skills + methodology phát triển phần mềm với AI coding agent. Repository: [obra/superpowers](https://github.com/obra/superpowers)

## Chức năng chính

Luồng phát triển có cấu trúc: **Brainstorm → Design → Git worktree → Implement → Review**. Subagent-driven review từng task — v6.0 rewrite cơ chế review thành cheaper, stricter, harder to game.

## Chức năng phụ

- Hỗ trợ 10+ harness: Claude Code, Cursor, Codex, Kimi Code, Copilot CLI, Pi, Antigravity...
- Có marketplace riêng (`obra/superpowers-marketplace`) và community skills repo (`obra/superpowers-skills`)
- Lab repo (`obra/superpowers-lab`) cho experimental skills
