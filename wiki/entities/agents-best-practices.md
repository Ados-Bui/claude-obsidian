---
type: entity
title: "agents-best-practices"
created: 2026-07-02
updated: 2026-07-02
tags:
  - entity
  - skill
  - agent-skill
  - best-practices
  - architecture
status: evergreen
related:
  - "[[Các repo cần chú ý - Phân loại]]"
entity_type: product
role: Provider-neutral SKILL.md đóng gói best practices thiết kế agentic system
---

# agents-best-practices

Provider-neutral Agent Skill cho Codex, Claude Code, và agentic harness design. Repository: [DenisSergeevitch/agents-best-practices](https://github.com/DenisSergeevitch/agents-best-practices)

## Chức năng chính

Đóng gói best practices thiết kế agentic system qua SKILL.md portable. Nguyên tắc cốt lõi: model proposes / application validates & executes; risk-tiered permission loop (read → draft → write → external → financial → destructive); draft-before-commit cho high-risk actions.

## Chức năng phụ

- Tài liệu tham khảo: MVP blueprints, architecture, agentic loops, tools & permissions, orchestration, context & memory
- Hoạt động như Codex skill, Claude Code skill, hoặc bất kỳ Agent-Skill-aware runtime nào
- License MIT
