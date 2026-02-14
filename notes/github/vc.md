---
url: https://github.com/steveyegge/vc
type: github-repo
languages: [Go]
tags: [ai-agents, coding, orchestration, multi-agent, sqlite]
date_saved: 2026-02-14
---
# VC - VibeCoder v2

## Summary
VC is an AI-orchestrated coding agent colony that coordinates multiple coding agents (Amp, Claude Code, etc.) to work on small, well-defined tasks guided by AI supervision. Built on lessons from a 350k LOC TypeScript prototype, it uses a SQLite-based issue tracker with dependency awareness.

## Key Points
- Zero Framework Cognition: all decisions delegated to AI, no heuristics or regex
- Issue-oriented orchestration with SQLite tracker (Beads) and dependency awareness
- Nondeterministic idempotence: workflows can be interrupted and resumed
- AI supervisor (Sonnet 4.5) manages worker agents through assessment → execution → analysis loop
- 254 issues closed through dogfooding with 90.9% quality gate pass rate

## Related
- [[ai-agents]]
- [[claude-code]]
- [[multi-agent-systems]]
- [[orchestration]]
