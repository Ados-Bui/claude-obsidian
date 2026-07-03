---
type: entity
title: "last30days-skill"
created: 2026-07-02
updated: 2026-07-02
tags:
  - entity
  - skill
  - agent-skill
  - research
  - information-synthesis
status: evergreen
related:
  - "[[Các repo cần chú ý - Phân loại]]"
entity_type: product
role: Skill nghiên cứu chủ đề bất kỳ trong 30 ngày qua từ nhiều nguồn
---

# last30days-skill

AI agent skill nghiên cứu topic bất kỳ qua 30 ngày gần nhất. Repository: [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)

## Chức năng chính

Scrape song song Reddit, X, YouTube, HN, Polymarket, GitHub — score kết quả theo engagement thực (upvote, like, transcript, Polymarket odds) rồi synthesize thành 1 bản tóm tắt có căn cứ qua AI judge.

## Chức năng phụ

- Hỗ trợ 50+ agent host: Claude Code, Codex, Cursor, Gemini CLI...
- Plugin cache versioned, tự cập nhật khi release mới
- Reddit, HN, Polymarket, GitHub hoạt động ngay; X, YouTube, TikTok unlock sau setup 30 giây
