---
url: https://github.com/hwchase17/deepagents
type: github-repo
tags: [agents, langchain, langgraph, planning, sub-agents]
date_saved: 2026-02-14
---
# Deep Agents

## Summary
Batteries-included agent harness by LangChain built on LangGraph. Provides an opinionated, ready-to-run agent with planning, filesystem, shell access, sub-agents, and automatic context management out of the box.

## Key Points
- Built-in tools: planning (todos), filesystem (read/write/edit), shell, sub-agents
- Auto-summarization when conversations get long
- Simple quickstart: `pip install deepagents` → `create_deep_agent()`
- CLI available via `uv tool install deepagents-cli` with memory, web search, remote sandboxes
- MCP support via langchain-mcp-adapters

## Related
- [[graphiti]]
- [[instructor]]
- [[claude-loop]]
