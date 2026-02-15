---
url: https://github.com/0kenx/chief-wiggum
type: github-repo
languages: [Shell, Python, TLA, Nix]
tags: [agent-orchestration, kanban, pr-automation]
date_saved: 2026-02-15
---
# chief-wiggum
## Summary
Chief Wiggum is an opinionated orchestration system that converts Kanban tasks or GitHub issues into merge-ready pull requests. It runs isolated workers per task and pushes work through a full pipeline including planning, implementation, security audit, testing, docs, and validation. The repo frames this as “specs as source” with automation across the PR lifecycle.

## Key Points
- Uses git worktrees and parallel workers to isolate and scale task execution.
- Includes self-correcting loops for failed tests, audit findings, and review comments.
- Supports dependency-aware scheduling and task-priority heuristics.
- Integrates with GitHub issues, labels, and merges for continuous flow.
- Offers configurable default/fast/fix pipelines.

## Related
- [[Coding Agents]]
- [[Task Orchestration]]
- [[Pull Request Automation]]
