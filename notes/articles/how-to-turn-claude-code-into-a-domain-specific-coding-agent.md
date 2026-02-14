---
url: https://blog.langchain.com/how-to-turn-claude-code-into-a-domain-specific-coding-agent/
type: article
tags: [claude-code, coding-agents, context-engineering]
date_saved: 2026-02-14
---
# How to Turn Claude Code into a Domain Specific Coding Agent

## Summary
LangChain tested four Claude Code configurations to improve code generation for custom/niche libraries (LangGraph, LangChain). The key finding: high-quality condensed information in Claude.md combined with tools for on-demand details produced the best results.

## Key Points
- Tested: vanilla, +MCP docs, +Claude.md, +MCP+Claude.md configurations
- Raw documentation access filled context windows too fast without proportional improvement
- Concise structured guides in Claude.md always outperformed just wiring in doc tools
- Best results from combining base knowledge (Claude.md) with doc access tools (MCPDoc)
- Built open-source MCPDoc server for providing any library's docs to coding agents

## Related
- [[effective-context-engineering-for-ai-agents]] - Context engineering strategies
- [[agenta]] - LLMOps platform
