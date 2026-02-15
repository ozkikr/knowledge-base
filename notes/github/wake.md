---
url: https://github.com/joemckenney/wake
type: github-repo
languages: [Rust, Shell]
tags: [terminal-recording, mcp, claude-code]
date_saved: 2026-02-15
---
# wake
## Summary
Wake records terminal sessions, command outputs, and context so Claude Code can reference recent shell activity. It pairs a CLI recorder with an MCP server for structured retrieval. The design is local-first, with optional local LLM summarization for long outputs.

## Key Points
- Captures command lifecycle events, output streams, and session metadata.
- Stores data in a local SQLite database and exposes it via MCP tools.
- Supports search, export, annotation, retention controls, and pruning.
- Includes local summarization using a small on-device model.

## Related
- [[Model Context Protocol]]
- [[Terminal Logging]]
- [[Claude Code]]
