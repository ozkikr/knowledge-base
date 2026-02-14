---
url: https://github.com/tobilg/ai-observer
type: github-repo
languages: [Go]
tags: [observability, ai-coding, opentelemetry, monitoring, developer-tools]
date_saved: 2026-02-14
---
# AI Observer

## Summary
AI Observer is a self-hosted, single-binary, OpenTelemetry-compatible observability backend for monitoring AI coding tools like Claude Code, Gemini CLI, and OpenAI Codex CLI. It tracks token usage, costs, API latency, error rates, and session activity in a unified dashboard with zero external dependencies.

## Key Points
- Single ~54MB binary with embedded frontend, no external dependencies
- Supports Claude Code, Gemini CLI, and OpenAI Codex CLI
- Real-time dashboard via WebSocket with customizable drag-and-drop widgets
- DuckDB-powered storage for fast analytics
- Historical import from local JSONL/JSON files with cost calculation for 67+ models

## Related
- [[claude-code]] - AI coding assistant
- [[opentelemetry]] - Observability standard
- [[developer-tools]]
