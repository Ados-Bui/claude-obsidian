---
type: entity
title: "spec-kit"
created: 2026-07-02
updated: 2026-07-02
tags:
  - entity
  - tool
  - ai-tool
  - spec-driven-development
  - agent
status: evergreen
related:
  - "[[Các repo cần chú ý - Phân loại]]"
entity_type: product
role: Toolkit cho Spec-Driven Development với AI coding agent
---

# spec-kit

Toolkit của GitHub cho Spec-Driven Development (SDD). Repository: [github/spec-kit](https://github.com/github/spec-kit)

## Chức năng chính

Đặt specification làm trung tâm của quy trình AI-assisted development. Luồng cố định: **Spec → Plan → Tasks → Implement** — mỗi phase tạo ra một Markdown artifact làm input có cấu trúc cho phase tiếp theo, thay vì prompt ad-hoc.

## Chức năng phụ

- Tích hợp 30+ AI coding agent: Claude, Copilot, Gemini, Codex, Kiro, Zed, Forge...
- Template, quality checklist, và cross-artifact analysis sẵn có
- Cộng đồng 200+ contributor có thể publish extension/preset/workflow riêng
- Cài qua `uv tool install specify-cli`
