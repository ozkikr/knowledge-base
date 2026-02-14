---
url: https://www.copilotkit.ai/blog/how-to-build-a-frontend-for-langchain-deep-agents-with-copilotkit
type: article
tags: [langchain, deep-agents, copilotkit, frontend, multi-agent, ag-ui]
date_saved: 2026-02-14
---
# How to Build a Frontend for LangChain Deep Agents with CopilotKit

## Summary
Tutorial on connecting LangChain's Deep Agents (structured multi-agent systems with planning, filesystem context, and subagent spawning) to a Next.js frontend using CopilotKit. Uses the AG-UI protocol to keep frontend state in sync with agent execution in real time.

## Key Points
- Deep Agents package plan→delegate→manage-state primitives into a reusable LangGraph-based runtime
- CopilotKit streams agent events and state updates to the frontend via AG-UI protocol
- Deep Agents are just LangGraph graphs, so streaming, checkpoints, and human-in-the-loop work as-is
- Built-in planning tools, filesystem context (ls/read/write/edit), and subagent delegation
- Example builds a job search assistant with real-time UI sync

## Related
- [[langchain]]
- [[langgraph]]
- [[copilotkit]]
- [[multi-agent-systems]]
- [[ag-ui-protocol]]
