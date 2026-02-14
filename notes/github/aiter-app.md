---
url: https://github.com/pranftw/aiter-app
type: github-repo
languages: [TypeScript]
tags: [ai-agents, mcp, tool-discovery, code-execution, vercel-ai-sdk]
date_saved: 2026-02-14
---
# aiter-app

## Summary
An app built with the aiter framework that demonstrates dynamic, in-memory MCP tool discovery — eliminating the need for filesystem-based tool file generation. Implements the approach from Anthropic's "Code Execution with MCP" blog post but without the overhead of generating TypeScript files.

## Key Points
- Dynamic in-memory MCP tool discovery — no generated files needed
- Eliminates synchronization, versioning, and disk overhead of filesystem approach
- Tools always in sync via live MCP connection
- Built on Vercel AI SDK's MCP support
- Progressive tool discovery with lightweight helper tools

## Related
- [[mcp]]
- [[code-execution-with-mcp]]
- [[ai-agents]]
