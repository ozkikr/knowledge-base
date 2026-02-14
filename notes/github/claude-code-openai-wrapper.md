---
url: https://github.com/RichardAtCT/claude-code-openai-wrapper/tree/main
type: github-repo
tags: [claude-code, openai-api, wrapper, api-compatibility, python]
date_saved: 2026-02-14
---

# Claude Code OpenAI API Wrapper

## Summary
An OpenAI API-compatible wrapper for Claude Code, powered by the official Claude Agent SDK v0.1.18. Provides both OpenAI /v1/chat/completions and Anthropic /v1/messages endpoints with streaming, multi-provider auth, and session management.

## Key Points
- Production-ready v2.2.0 with dual API compatibility (OpenAI + Anthropic formats)
- Multi-provider auth: API key, Bedrock, Vertex AI, CLI auth
- Optional tool execution (Read, Write, Bash) — disabled by default for speed
- Real-time cost/token tracking, session continuity across requests
- Interactive landing page with API explorer

## Related
- [[claude-code-api]] - another OpenAI-compatible gateway for Claude Code
- [[mcphost]] - CLI host for LLM interactions
