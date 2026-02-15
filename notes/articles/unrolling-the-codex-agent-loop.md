---
url: https://openai.com/index/unrolling-the-codex-agent-loop/
type: article
tags: [agent-loop, codex, llm-systems]
date_saved: 2026-02-15
---
# Unrolling the Codex agent loop
## Summary
OpenAI’s post dissects the Codex harness loop: prompt assembly, model inference, tool calls, and termination signaling. It explains practical concerns like stateless request design, prompt caching behavior, and context compaction under long-running conversations. The article serves as a systems-level reference for building robust software agents.

## Key Points
- Breaks down turn-by-turn loop mechanics between user input, tool execution, and model responses.
- Details how role-scoped instructions, tools, and conversation history become model input.
- Discusses performance tradeoffs around prompt growth, caching, and context window limits.
- Explains why Codex prioritizes statelessness (including ZDR-friendly operation) over certain API conveniences.
- Covers automatic compaction strategies to preserve long-horizon agent continuity.

## Related
- [[agent-harness]]
- [[prompt-caching]]
- [[context-management]]
