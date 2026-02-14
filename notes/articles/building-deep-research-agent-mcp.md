---
url: https://thealliance.ai/blog/building-a-deep-research-agent-using-mcp-agent
type: article
tags: [deep-research, mcp, agents, orchestrator-pattern, llm-agents]
date_saved: 2026-02-14
---
# Building a Deep Research Agent Using MCP-Agent

## Summary
Sarmad Qadri documents building an open-source deep research agent using MCP (Model Context Protocol). The philosophy: connect LLMs to MCP servers with simple design patterns for tool calls, context gathering, and decision-making. The journey progresses from a basic Orchestrator pattern to a more sophisticated Deep Orchestrator.

## Key Points
- Core philosophy: "MCP is all you need" — connect LLMs to MCP servers and let them make tool calls and decisions
- Started with Anthropic's Orchestrator pattern (planner → sub-agents → synthesizer) but hit limitations: hallucinated agent names, token inefficiency, rigid upfront planning
- MCP integration enables connecting to any data source (internal warehouses, APIs) and mutating state, not just research
- Progressive context management: outputs from sequential steps inform later decisions
- Open-source Deep Orchestrator available at github.com/lastmile-ai/mcp-agent

## Related
- [[mcp]]
- [[deep-research]]
- [[orchestrator-pattern]]
- [[llm-agents]]
