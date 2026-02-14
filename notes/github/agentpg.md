---
url: https://github.com/youssefsiam38/agentpg
type: github-repo
languages: [Go]
tags: [ai-agents, postgresql, distributed, event-driven, framework]
date_saved: 2026-02-14
---
# AgentPG

## Summary
A fully event-driven Go framework for building async AI agents using PostgreSQL for state management and distribution. Provides stateful, distributed, transaction-safe agent execution with Claude API integration. Features batch API (50% cost savings) and streaming modes.

## Key Points
- PostgreSQL LISTEN/NOTIFY for real-time coordination with polling fallback
- Race-safe work claiming with SELECT FOR UPDATE SKIP LOCKED
- Transaction-first API with user transaction support
- Multi-agent hierarchies via agent-as-tool pattern
- Automatic context compaction for long conversations

## Related
- [[ai-agents]]
- [[postgresql]]
- [[distributed-systems]]
- [[context-engineering]]
