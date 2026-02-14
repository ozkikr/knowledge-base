---
url: https://engineering.atspotify.com/2025/12/feedback-loops-background-coding-agents-part-3
type: article
tags: [coding-agents, spotify, verification, ci-cd, automation]
date_saved: 2026-02-14
---
# Background Coding Agents: Predictable Results Through Strong Feedback Loops (Part 3)

## Summary
Part 3 of Spotify's series on background coding agents focuses on designing environments for agents running without human supervision to produce correct, reliable results. The article introduces verification loops — independent verifiers (e.g., Maven, build systems) that abstract complexity and give agents incremental feedback without consuming their context window.

## Key Points
- Three failure modes: no PR produced (minor), PR fails CI (frustrating), PR passes CI but is functionally incorrect (worst — erodes trust)
- Verification loops let agents check their work incrementally before committing
- Verifiers are abstracted via MCP tools — the agent doesn't know the underlying build system details
- Verifiers parse build output with regex to return only relevant error messages, preserving context window
- Runs all verifiers before opening a PR; uses Claude Code stop hooks for enforcement

## Related
- [[facilitating-ai-adoption-at-imprint]] - AI adoption strategy
- [[AgentFlow]] - Agentic system optimization
- [[docker-sandboxes-coding-agent-safety]] - Agent safety
