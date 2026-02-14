---
url: https://github.com/OppieAI/ToolsFilter
type: github-repo
tags: [mcp, llm, tool-selection, optimization]
date_saved: 2026-02-14
---
# ToolsFilter (OppieAI)

## Summary
A Precision-driven Tool Recommendation (PTR) system for filtering MCP tools based on conversation context. It fetches only relevant tools for the ongoing conversation, reducing costs and increasing LLM response precision by addressing the "tool overload" problem.

## Key Points
- Solves the tool overload problem where too many tools degrade LLM performance
- Filters MCP tools based on conversation context using vector search
- Reduces token costs by sending only relevant tools to the LLM
- Based on research from PTR (Precision-driven Tool Recommendation) paper
- Includes automatic fallback mechanisms and evaluation framework

## Related
- [[mcp]] - Model Context Protocol
- [[llm-optimization]] - Reducing LLM costs
- [[witsy]] - Universal MCP client
