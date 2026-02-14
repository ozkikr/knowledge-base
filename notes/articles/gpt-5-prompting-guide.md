---
url: https://cookbook.openai.com/examples/gpt-5/gpt-5_prompting_guide
type: article
tags: [gpt-5, prompting, openai, agentic, best-practices]
date_saved: 2026-02-14
---
# GPT-5 Prompting Guide

## Summary
Official OpenAI cookbook guide for prompting GPT-5, covering agentic workflow predictability, controlling eagerness, coding performance, and instruction following. Emphasizes using Responses API where reasoning persists between tool calls.

## Key Points
- GPT-5 trained for improved tool calling, instruction following, and long-context understanding
- Control agentic eagerness via reasoning_effort parameter (low/medium/high)
- Define clear context-gathering criteria to reduce unnecessary exploration
- Can set fixed tool call budgets for predictable latency
- Recommends Responses API for agentic flows (reasoning persists between tool calls)

## Related
- [[prompt-engineering]]
- [[openai]]
- [[agentic-workflows]]
- [[reasoning-models]]
