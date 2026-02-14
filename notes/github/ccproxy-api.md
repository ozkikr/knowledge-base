---
url: https://github.com/CaddyGlow/ccproxy-api/
type: github-repo
tags: [proxy, ai, claude, codex, copilot, openai-compatible]
date_saved: 2026-02-14
---

# CCProxy API Server

## Summary
A local, plugin-based reverse proxy that unifies access to multiple AI providers (Claude API/SDK, OpenAI Codex, GitHub Copilot) behind a consistent API. Reuses existing subscriptions without API key billing.

## Key Points
- Supports Anthropic Claude, OpenAI Codex, and GitHub Copilot providers
- Exposes unified OpenAI Chat Completions, Responses, and Anthropic Messages endpoints
- Plugin system for logging, tracing, metrics, analytics, and more
- Reuses existing CLI credentials (Claude SDK tokens, Codex credential store)
- DuckDB-backed analytics for captured request logs

## Related
- [[clewdr]] - similar Claude proxy in Rust
- [[claude]] - Anthropic's AI model
- [[github-copilot]] - Microsoft's AI coding assistant
