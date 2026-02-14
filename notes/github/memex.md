---
url: https://github.com/nicosuave/memex
type: github-repo
languages: [Rust]
tags: [search, transcripts, ai-agents, tui, embeddings]
date_saved: 2026-02-14
---
# memex

## Summary
memex is a fast local history search tool for Claude Code, Codex CLI, and OpenCode agent logs. It uses BM-25 and optional local embeddings for hybrid search, letting agents query their own past sessions. Includes a TUI for browsing and resuming sessions.

## Key Points
- Indexes agent transcripts with BM-25 and optional embedding models (minilm, bge, nomic, gemma)
- Search modes: exact terms, semantic, or hybrid
- Rich filtering: by project, role, tool, session, source, date range
- Background index service via launchd (macOS) or systemd (Linux)
- TUI for interactive browsing and session resumption

## Related
- [[roborev]] - continuous code review with agent integration
- [[mcp-agent-mail]] - agent coordination and message history
- [[agents-council]] - multi-agent collaboration
