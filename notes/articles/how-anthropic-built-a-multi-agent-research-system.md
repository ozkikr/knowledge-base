---
url: https://blog.bytebytego.com/p/how-anthropic-built-a-multi-agent
type: article
tags: [multi-agent, anthropic, claude, research-system, ai-architecture]
date_saved: 2026-02-14
---
# How Anthropic Built a Multi-Agent Research System

## Summary
ByteByteGo analysis of Anthropic's multi-agent research system architecture. The system uses Claude Opus 4 as lead agent with Claude Sonnet 4 subagents for parallel breadth-first exploration, outperforming single-agent setups by over 90% in internal evaluations.

## Key Points
- Multi-agent architecture with lead agent (Opus 4) orchestrating subagents (Sonnet 4)
- Outperforms single-agent setup by 90%+ through parallel exploration
- Performance gains linked to token usage scaling across independent context windows
- Enables breadth-first exploration of large search spaces
- Each discovery can shift inquiry direction, making fixed pipelines inadequate

## Related
- [[multi-agent-systems]]
- [[claude]]
- [[ai-architecture]]
