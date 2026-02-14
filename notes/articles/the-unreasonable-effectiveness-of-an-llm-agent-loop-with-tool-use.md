---
url: https://sketch.dev/blog/agent-loop
type: article
tags: [llm, agents, tool-use, coding-assistant]
date_saved: 2026-02-14
---
# The Unreasonable Effectiveness of an LLM Agent Loop with Tool Use

## Summary
Philip Zeyliger from Sketch describes how a surprisingly simple 9-line agent loop (LLM + tool calls) is the core of powerful AI coding assistants. With just bash as a tool, current models like Claude can handle many real-world programming tasks autonomously.

## Key Points
- The core agent loop is shockingly simple: prompt → LLM response → handle tool calls → repeat
- A single general-purpose tool (bash) is enough for many tasks
- Specialized tools improve quality and speed (e.g., text editing tools)
- LLMs struggle with sed one-liners, reaffirming the value of visual editors
- Agent loops will increasingly handle day-to-day automation

## Related
- [[ai-agents]] [[coding-assistants]] [[sketch]] [[tool-use]]
