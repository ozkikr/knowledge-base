---
url: https://github.com/jamubc/gemini-mcp-tool
type: github-repo
tags: [mcp, gemini, claude-code, ai, llm]
date_saved: 2026-02-14
---

# Gemini MCP Tool

## Summary
An MCP server that enables AI assistants like Claude Code to interact with Google's Gemini CLI. Leverages Gemini's massive token window for large file analysis and codebase understanding, effectively letting you use two AI models together.

## Key Points
- Bridges Claude Code and Gemini CLI via MCP protocol
- Leverages Gemini's large context window for analyzing big files/codebases
- One-line setup: `claude mcp add gemini-cli -- npx -y gemini-mcp-tool`
- Saves tokens on the Claude side by offloading large analysis to Gemini
- Supports brainstorming between multiple AI models

## Related
- [[mcp]] - Model Context Protocol
- [[gemini-cli]] - Google's Gemini command-line interface
- [[claude-code]] - Anthropic's coding agent
