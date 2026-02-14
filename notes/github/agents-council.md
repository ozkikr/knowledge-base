---
url: https://github.com/MrLesk/agents-council
type: github-repo
languages: [TypeScript]
tags: [multi-agent, mcp, collaboration, ai-agents, council]
date_saved: 2026-02-14
---
# Agents Council

## Summary
Agents Council is an MCP-based tool that bridges active AI agent sessions (Claude Code, Codex, Gemini, Cursor) for collaboration. It enables agents to communicate, brainstorm, and peer-review without leaving their current context, inspired by Andrej Karpathy's LLM Council.

## Key Points
- Centralized agent communication via MCP stdio server (no peer-to-peer networking)
- Can summon Claude or Codex into the council on demand, reusing local auth
- Session preservation: start agents with context, let them collaborate, resume when done
- Includes a local web chat UI for human participation/monitoring
- Private and local: state stored on disk at `~/.agents-council/state.json`

## Related
- [[mcp-agent-mail]] - async agent coordination via mail-like system
- [[rwx]] - autonomous agent loops
- [[tool-ui]] - AI interface components
