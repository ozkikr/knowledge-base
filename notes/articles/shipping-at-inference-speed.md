---
url: https://steipete.me/posts/2025/shipping-at-inference-speed
type: article
tags: [ai-coding, vibe-coding, coding-agents, gpt5, codex, claude-code]
date_saved: 2026-02-14
---
# Shipping at Inference Speed

## Summary
Peter Steinberger's updated take on vibe coding in late 2025. The main unlock was GPT 5 and Codex — he now ships at a pace limited mainly by inference time, rarely reads code directly, and has found Codex significantly better than Claude Opus for large refactors due to its deep code-reading before editing.

## Key Points
- GPT 5/Codex was the key unlock: reads code for 10-15 minutes before writing, leading to fewer fix-the-fix loops vs Claude Opus
- Go-to languages: TypeScript (web), Go (CLIs), Swift (macOS/UI) — Go chosen because agents write it well and linting is fast
- Built "Oracle" CLI tool to let agents query GPT 5 Pro for hard problems; usage dropped dramatically with GPT 5.2
- Codex's plan mode is unnecessary with newer models — just conversational prompting + "build" command
- ~30% of Ramp PRs written by their Inspect agent; Codex one-shots almost anything with GPT 5.2
- Knowledge cutoff advantage: GPT 5.2 (August) vs Opus (March) — 5 month gap matters for latest tools

## Related
- [[Coding Agents]]
- [[Vibe Coding]]
- [[GPT 5]]
- [[Claude Code]]
