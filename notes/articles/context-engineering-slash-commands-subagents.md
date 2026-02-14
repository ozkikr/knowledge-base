---
url: https://jxnl.co/writing/2025/08/29/context-engineering-slash-commands-subagents/
type: article
tags: [context-engineering, ai-agents, subagents, claude-code, llm]
date_saved: 2026-02-14
---
# Slash Commands vs Subagents: How to Keep AI Tools Focused

## Summary
Jason Liu explores the architectural choice between slash commands and subagents in AI coding tools. Subagents handle messy, token-intensive tasks in isolation and return distilled insights, achieving 8x cleaner context (76% useful vs 91% junk) compared to slash commands.

## Key Points
- Context pollution: cheap but toxic—loading logs destroys valuable reasoning context
- Subagents isolate messy work and return only distilled insights to the main thread
- Slash commands dump all output into main context (169K tokens, 91% junk)
- Subagent pattern: 21K tokens, 76% useful information—8x cleaner
- Pattern applies beyond coding: customer support, financial analysis, medical diagnosis

## Related
- [[context-engineering]] [[Claude-Code]] [[AI-agents]] [[prompt-engineering]]
