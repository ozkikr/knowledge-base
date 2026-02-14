---
url: https://github.com/lanegrid/agtrace
type: github-repo
languages: [TypeScript, Rust]
tags: [ai-agents, observability, context-window, tracing, mcp]
date_saved: 2026-02-14
---
# agtrace

## Summary
agtrace is a monitoring dashboard that runs alongside AI coding agents (Claude Code, Codex, Gemini) to show context window usage, token consumption trends, and live activity. It also provides MCP integration so agents can query their own execution history.

## Key Points
- Color-coded context window usage bar shows conversation fullness
- Live activity feed showing tool calls, file reads, and reasoning traces
- MCP server lets agents search past sessions and learn from previous errors
- Session browsing and cross-session search via `agtrace lab grep`
- Available on npm (`@lanegrid/agtrace`) and crates.io

## Related
- [[claude-code]]
- [[mcp]]
- [[observability]]
