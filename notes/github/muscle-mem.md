---
url: https://github.com/pig-dot-dev/muscle-mem
type: github-repo
tags: [ai-agents, caching, automation, python]
date_saved: 2026-02-14
---
# Muscle Memory

## Summary
A Python SDK that acts as a behavior cache for AI agents. It records tool-calling patterns as agents solve tasks, then deterministically replays learned trajectories on repeat encounters, falling back to agent mode for edge cases. The goal is removing LLMs from the hot path for repetitive tasks.

## Key Points
- Records agent tool-call trajectories and replays them on cache hits
- Cache validation determines if it's safe to replay vs. invoke the agent
- Framework-agnostic: plug in your own agent implementation
- Reduces token costs, latency, and variability for repetitive tasks
- Supports parameterization and tags for flexible matching

## Related
- [[ai-agents]]
- [[tool-use]]
- [[workflow-automation]]
