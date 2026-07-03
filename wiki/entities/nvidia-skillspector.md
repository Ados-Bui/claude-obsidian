---
type: entity
title: "SkillSpector"
created: 2026-07-02
updated: 2026-07-02
tags:
  - entity
  - tool
  - ai-tool
  - security
  - agent-skill
status: evergreen
related:
  - "[[Các repo cần chú ý - Phân loại]]"
entity_type: product
role: Security scanner cho AI agent skills
---

# SkillSpector

Security scanner cho AI agent skills của NVIDIA. Repository: [NVIDIA/SkillSpector](https://github.com/nvidia/skillspector)

## Chức năng chính

Phát hiện 68 vulnerability pattern trên 17 category trước khi install skill: jailbreak instructions ("never refuse", "always comply"), "no disclaimers", "do not moralize", và các malicious pattern khác.

## Chức năng phụ

- Semantic analysis qua LLM endpoint tùy chọn (OpenAI-compatible, Ollama, vLLM)
- Chạy được qua Docker, không cần cài Python local
- Giới hạn: không phân tích non-English, ảnh, binary/encrypted code, hoặc runtime behavior
