---
type: entity
title: "mattpocock/skills"
created: 2026-07-02
updated: 2026-07-02
tags:
  - entity
  - skill
  - agent-skill
  - engineering
  - claude-code
status: evergreen
related:
  - "[[Các repo cần chú ý - Phân loại]]"
entity_type: product
role: Engineering skills cho AI coding agent từ Matt Pocock
---

# mattpocock/skills

Tập hợp engineering skills cho AI coding agent. Repository: [mattpocock/skills](https://github.com/mattpocock/skills)

## Chức năng chính

Fix common failure modes của Claude Code, Codex và các coding agent. Các skill nhỏ, composable, dễ adapt. Skills nổi bật: `triage` (issue state machine), `improve-codebase-architecture` (HTML report), `to-issues` (break plan → vertical slice issues), `grill-with-docs` (domain model + CONTEXT.md).

## Chức năng phụ

- Router skill `ask-matt` dispatch sang các skill con
- Tích hợp với GitHub Issues, Linear, hoặc local files
- Setup qua `/setup-matt-pocock-skills`
