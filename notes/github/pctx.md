---
url: https://github.com/portofcontext/pctx
type: github-repo
languages: [Rust, Python, TypeScript]
tags: [ai-agents, mcp, code-mode, sandboxing, tool-execution]
date_saved: 2026-02-14
---
# pctx — Execution Layer for Agentic Tool Calls

## Summary
pctx is an open-source framework that connects AI agents to tools and MCP servers via "Code Mode" — auto-converting agent tools into code that runs in secure sandboxes for token-efficient workflows. It can run as a stateless HTTP server or a unified MCP server.

## Key Points
- Code Mode: converts tool calls into executable code in secure sandboxes
- Python SDK for building agents with custom tools and MCP servers
- Works with any agent SDK (OpenAI Agents SDK, etc.)
- Installable via Homebrew, npm, or curl
- Unified MCP server that exposes Code Mode for registered upstream MCP servers

## Related
- [[mcp]]
- [[ai-agents]]
- [[sandboxing]]
