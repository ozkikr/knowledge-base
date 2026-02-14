---
url: https://github.com/fulcrumresearch/quibbler
type: github-repo
languages: [Python]
tags: [coding-agent, critic, mcp, code-quality, claude-code]
date_saved: 2026-02-14
---
# Quibbler

## Summary
A critic agent that runs alongside your coding agent, observing and correcting its actions in real-time. Prevents common agent mistakes like fabricating results, skipping tests, and ignoring coding patterns. Learns rules from usage and enforces them automatically.

## Key Points
- Runs in background monitoring coding agent actions via hooks or MCP
- Prevents: fabricated results, skipped tests, hallucinated metrics, ignored patterns
- Two modes: Hook Mode (Claude Code specific) and MCP Mode (universal)
- Learns project patterns and rules over time
- Maintains context across reviews for consistent enforcement

## Related
- [[coding-agents]] [[code-quality]] [[mcp]] [[claude-code]] [[ai-guardrails]]
