---
url: https://github.com/mark3labs/mcphost
type: github-repo
tags: [mcp, cli, llm, tool-use, golang]
date_saved: 2026-02-14
---

# MCPHost

## Summary
MCPHost is a CLI host application that enables LLMs to interact with external tools through the Model Context Protocol (MCP). Supports Claude, OpenAI, Google Gemini, and Ollama models with both interactive and script modes.

## Key Points
- Acts as MCP host in client-server architecture connecting LLMs to external tools
- Supports multiple providers: Anthropic, OpenAI, Gemini, Ollama
- Features interactive mode, script mode, non-interactive mode, and hooks system
- Includes tool filtering, environment variable substitution, and auth subcommands
- Written in Go with SDK usage support

## Related
- [[fast-agent]] - another MCP-enabled agent framework
- [[clai]] - CLI LLM tool
- [[autogen]] - multi-agent framework with MCP support
