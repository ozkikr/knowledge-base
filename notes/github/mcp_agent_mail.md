---
url: https://github.com/Dicklesworthstone/mcp_agent_mail
type: github-repo
languages: [Python]
tags: [mcp, multi-agent, coordination, fastmcp, git, sqlite]
date_saved: 2026-02-14
---
# MCP Agent Mail

## Summary
MCP Agent Mail is an asynchronous coordination layer for AI coding agents, providing identities, inboxes, searchable message threads, and advisory file leases. Built on FastMCP + Git + SQLite, it acts like email for coding agents to prevent conflicts and share context.

## Key Points
- Agents register memorable identities and get inbox/outbox with GFM markdown + image support
- Advisory file reservation "leases" to signal intent and avoid edit conflicts
- Git-backed for human-auditable artifacts; SQLite for indexing and queries
- Works with Claude Code, Codex, Gemini CLI, Factory Droid, and other MCP clients
- Includes a companion iOS app for fleet management and automated prompt scheduling

## Related
- [[agents-council]] - real-time multi-agent collaboration
- [[rwx]] - autonomous agent loops
- [[codex-container]] - containerized agent environment
