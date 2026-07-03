---
type: entity
title: "agent-skills (addyosmani)"
created: 2026-07-02
updated: 2026-07-02
tags:
  - entity
  - skill
  - agent-skill
  - engineering
  - production
  - claude-code
status: evergreen
related:
  - "[[Các repo cần chú ý - Phân loại]]"
entity_type: product
role: Production-grade engineering skills cho AI coding agent
---

# agent-skills (addyosmani)

Production-grade engineering skills cho AI coding agent. Repository: [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)

## Chức năng chính

24 skills (23 lifecycle + 1 meta) — mỗi skill là workflow có steps, checkpoint, và exit criteria cụ thể. Không phải tài liệu tham khảo mà là quy trình agent phải follow, kết thúc bằng evidence requirements (tests passing, build output, runtime data).

## Chức năng phụ

- 3 composable layers: Skills (`SKILL.md`), Personas (`agents/<role>.md`), Slash commands (`.claude/commands/`)
- Cài qua Claude Code marketplace: `/plugin marketplace add addyosmani/agent-skills`
- Từ Addy Osmani — Chrome DevTools, web performance
