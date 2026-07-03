# Các repo cần chú ý — Phân loại theo chức năng

← [[Các repo cần chú ý]]

---

## Skill

Các repo cung cấp SKILL.md / workflow có thể cài vào Claude Code, Codex, Cursor và các agent khác.

**[mattpocock/skills](https://github.com/mattpocock/skills)**
- Chính: Tập hợp engineering skills cho AI coding agent — fix common failure modes của Claude Code, Codex. Có các skill như `triage`, `improve-codebase-architecture`, `to-issues`, `grill-with-docs`.
- Phụ: Router skill `ask-matt` để dispatch sang các skill con; tích hợp với GitHub Issues, Linear.

**[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)**
- Chính: 24 production-grade engineering skills cho AI coding agent — mỗi skill là một workflow có steps, checkpoint, và exit criteria cụ thể (không phải doc tham khảo).
- Phụ: Bao gồm cả personas (roles) và slash commands; cài được qua Claude Code marketplace.

**[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)**
- Chính: Skill nghiên cứu bất kỳ chủ đề nào trong 30 ngày qua — scrape song song từ Reddit, X, YouTube, HN, Polymarket, GitHub rồi synthesize thành 1 bản tóm tắt có điểm engagement.
- Phụ: Hỗ trợ 50+ agent host (Claude Code, Codex, Cursor, Gemini CLI...); tự cập nhật qua plugin cache versioning.

**[DenisSergeevitch/agents-best-practices](https://github.com/DenisSergeevitch/agents-best-practices)**
- Chính: Provider-neutral SKILL.md đóng gói best practices thiết kế agentic system — phân tách rõ "model proposes / application validates & executes", risk-tiered permission loop, draft-before-commit cho high-risk actions.
- Phụ: Tài liệu tham khảo về architecture, security, observability, orchestration, context & memory.

**[obra/superpowers](https://github.com/obra/superpowers)**
- Chính: Framework skills + methodology phát triển phần mềm với agent — luồng Brainstorm → Design → Git worktree → Implement → Review; subagent-driven review từng task.
- Phụ: Hỗ trợ 10+ harness (Claude Code, Cursor, Codex, Kimi Code, Copilot CLI...); có marketplace và skills community repo riêng.

---

## AI Tool

Các repo là công cụ/infrastructure hỗ trợ quy trình làm việc với AI agent.

**[github/spec-kit](https://github.com/github/spec-kit)**
- Chính: Toolkit cho Spec-Driven Development — luồng Spec → Plan → Tasks → Implement, mỗi phase tạo ra Markdown artifact làm context cho phase tiếp theo thay vì prompt ad-hoc.
- Phụ: Tích hợp 30+ AI coding agent (Claude, Copilot, Gemini, Codex, Kiro...); cộng đồng 200+ contributor có thể publish extension/preset/workflow.

**[tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)**
- Chính: Local-first code intelligence graph cho MCP và CLI — parse codebase thành AST với Tree-sitter, lưu dưới dạng graph (functions, classes, imports, call edges), tính "blast radius" khi file thay đổi để AI chỉ đọc đúng files liên quan.
- Phụ: Giảm context ~82x so với đọc toàn bộ corpus; hỗ trợ 30+ ngôn ngữ; có VS Code extension.

**[affaan-m/ECC](https://github.com/affaan-m/ecc)**
- Chính: Agent harness performance optimization system — hệ thống đầy đủ gồm skills, instincts, memory optimization, security scanning, và research-first development workflow cho Claude Code, Codex, Cursor, Opencode.
- Phụ: Cross-harness portability; cài qua npm (`ecc-universal`), GitHub App, hoặc plugin slug; hỗ trợ 12+ language ecosystem.

**[NVIDIA/SkillSpector](https://github.com/nvidia/skillspector)**
- Chính: Security scanner cho AI agent skills — phát hiện 68 vulnerability pattern trên 17 category (jailbreak instructions, "never refuse", "no disclaimers"...) trước khi install skill.
- Phụ: Semantic analysis qua LLM endpoint tùy chọn (OpenAI-compatible, Ollama, vLLM); chạy được qua Docker; giới hạn: không phân tích non-English, ảnh, binary, hoặc runtime behavior.

**[msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)**
- Chính: Bộ 232 specialized agent persona trải rộng 16 division (engineering, design, marketing, product, spatial computing...) — mỗi agent có personality, process riêng, và deliverable cụ thể.
- Phụ: App native (macOS/Linux/Windows) để browse và install 1 click vào Claude Code, Cursor, Codex, Gemini; tự auto-update.

## Threat Intelligence

Các repo tổng hợp tài liệu, mẫu, chỉ số IOC phục vụ nghiên cứu APT/threat intelligence.

**[blackorbird/APT_REPORT](https://github.com/blackorbird/apt_report)**
- Chính: Kho tổng hợp report, sample, malware, technology & intelligence liên quan APT — tổ chức theo từng nhóm threat actor (APT28, APT29, Lazarus, Kimsuky...), 80+ folder.
- Phụ: Gồm PDF report, ma trận threat actor dạng Excel, tài liệu kỹ thuật; có phần riêng cho nhóm Hàn Quốc, Trung Đông, tội phạm tài chính; kèm threat actor encyclopedia và cyber power index.
