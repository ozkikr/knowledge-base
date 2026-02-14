---
url: https://github.com/Danau5tin/multi-agent-coding-system
type: github-repo
tags: [multi-agent, coding, terminal-bench, orchestration]
date_saved: 2026-02-14
---
# Orchestrator: Multi-Agent Coding System

## Summary
A multi-agent AI coding system that reached #13 on Stanford's TerminalBench leaderboard, placing higher than Claude Code. It uses an orchestration agent that dispatches explorer and coder subagents, building compound intelligence through knowledge artifacts shared across tasks.

## Key Points
- Orchestrator dispatches multiple explorer and coder agents with explicit knowledge artifact contracts
- Reached #13 on Stanford's TerminalBench (above Claude Code)
- Orca-Agent-v0.1: RL-trained 14B model with 160% relative increase on TerminalBench
- Scaled RL training to 32x H100s with 256 concurrent Docker environments
- Fully async, supports different models for orchestrator vs subagents

## Related
- [[claude-code-agent-farm]]
- [[claude-squad]]
- [[ccpm]]
