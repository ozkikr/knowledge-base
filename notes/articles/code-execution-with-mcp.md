---
url: https://www.anthropic.com/engineering/code-execution-with-mcp
type: article
tags: [mcp, ai-agents, code-execution, anthropic, tool-use]
date_saved: 2026-02-14
---
# Code Execution with MCP: Building More Efficient AI Agents

## Summary
Anthropic engineering blog post exploring how code execution can enable agents to interact with MCP servers more efficiently. As agents connect to hundreds of tools, loading all definitions upfront and passing intermediate results through context becomes costly — code execution offers a solution.

## Key Points
- Tool definitions overload the context window as MCP usage scales
- Intermediate tool results consume additional tokens unnecessarily
- Code execution lets agents discover and call tools progressively
- MCP has seen rapid adoption since Nov 2024 with thousands of community servers
- Approach handles more tools while using fewer tokens

## Related
- [[mcp]]
- [[ai-agents]]
- [[aiter-app]]
- [[context-engineering]]
