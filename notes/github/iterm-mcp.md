---
url: https://github.com/ferrislucas/iterm-mcp
type: github-repo
languages: [TypeScript]
tags: [mcp, iterm, terminal, repl, cli]
date_saved: 2026-02-14
---
# iterm-mcp — MCP Server for iTerm Sessions

## Summary
A Model Context Protocol server that provides AI models access to your iTerm terminal session. It enables natural integration where you share iTerm with the model for REPL interaction, command execution, and terminal control.

## Key Points
- Efficient token use: model inspects only the output lines it needs
- Full terminal control including REPLs and control characters (Ctrl-C, Ctrl-Z)
- Minimal dependencies, runnable via `npx`
- Tools: write_to_terminal, read_terminal_output, send_control_character
- Easy integration with Claude Desktop and other MCP clients

## Related
- [[mcp]]
- [[wcgw]]
- [[terminal-tools]]
