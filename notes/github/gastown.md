---
url: https://github.com/steveyegge/gastown
type: github-repo
languages: [Python]
tags: [multi-agent, claude-code, orchestration, workspace-manager]
date_saved: 2026-02-14
---
# Gas Town - Multi-Agent Workspace Manager

## Summary
Gas Town is a multi-agent orchestration system for Claude Code with persistent work tracking. It coordinates 20-30 agents working on different tasks using git-backed hooks for state persistence, built-in mailboxes for communication, and a hierarchical architecture (Mayor → Town → Rigs → Crews/Polecats).

## Key Points
- Solves agent context loss on restart via git-backed hooks (Beads ledger)
- Scales to 20-30 concurrent agents with built-in coordination (mailboxes, identities, handoffs)
- Architecture: Mayor (AI coordinator) → Town workspace → Rigs (per-project) → Crew members + Polecats (workers)
- Uses git worktrees for persistent storage across agent restarts
- By Steve Yegge, designed for large-scale coding workflows

## Related
- [[the-future-of-coding-agents]]
- [[claude-code]]
- [[multi-agent-orchestration]]
