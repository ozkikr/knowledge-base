---
url: https://github.com/shelvick/quoracle
type: github-repo
languages: [Elixir, JavaScript]
tags: [multi-agent, consensus, orchestration]
date_saved: 2026-02-15
---
# Quoracle
## Summary
Quoracle is a Phoenix LiveView system for recursive agent orchestration where actions are selected through multi-model consensus rather than a single LLM. Agents can spawn child agents, exchange messages, and operate under explicit capability and budget controls. The platform persists state in PostgreSQL and exposes real-time task visibility in a browser dashboard.

## Key Points
- Uses parallel model voting and action clustering to choose majority-consensus actions.
- Supports hierarchical delegation with child-agent spawning, scoped budgets, and shared constraints/context.
- Persists task state, logs, messages, and costs; LiveView UI streams updates in real time.
- Includes profile-based capability controls for file, API, execution, and hierarchy operations.
- Implements security measures like encrypted credentials, secret scrubbing, and untrusted-content tagging.

## Related
- [[multi-agent-systems]]
- [[llm-consensus]]
- [[phoenix-liveview]]
