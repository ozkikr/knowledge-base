---
url: https://github.com/Bigsy/mcpmu
type: github-repo
languages: [Go]
tags: [mcp, cli, tui, server-management, go]
date_saved: 2026-02-15
---
# mcpmu
## Summary
mcpmu is a Go-based MCP multiplexer that lets users manage many MCP servers behind one endpoint. It centralizes setup so multiple coding agents can reuse the same configured tools instead of maintaining duplicate configs. The project includes a TUI and namespace/permission controls for practical day-to-day operations.

## Key Points
- Aggregates local stdio and remote HTTP/SSE MCP servers into a single served endpoint.
- Provides namespace profiles and per-tool permissions for context isolation.
- Includes interactive terminal UI for monitoring, logs, and lifecycle control.
- Supports OAuth flows and hot-reload behavior for smoother operations.

## Related
- [[Model Context Protocol]]
- [[CLI Tools]]
- [[Terminal UI]]
- [[Agent Tooling]]
