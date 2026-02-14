---
url: https://www.docker.com/blog/docker-sandboxes-a-new-approach-for-coding-agent-safety/
type: article
tags: [docker, sandboxing, coding-agents, security, microvm]
date_saved: 2026-02-14
---
# Docker Sandboxes: A New Approach for Coding Agent Safety

## Summary
Docker introduces sandboxes for running coding agents (Claude Code, Gemini, Codex, Kiro) unsupervised but safely. The approach uses microVM-based isolation to let agents execute code without risking the host system, addressing the growing need for secure agent execution environments.

## Key Points
- MicroVM-based isolation for coding agent execution
- Supports Claude Code, Gemini, Codex, and Kiro
- Enables unsupervised agent operation with safety guarantees
- Part of Docker's broader security push including Hardened Images
- Addresses the trust problem in background coding agents

## Related
- [[feedback-loops-background-coding-agents-part-3]] - Spotify's agent verification
- [[facilitating-ai-adoption-at-imprint]] - AI adoption strategy
- [[AgentFlow]] - Agentic system framework
