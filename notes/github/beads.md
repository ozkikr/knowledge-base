---
url: https://github.com/steveyegge/beads
type: github-repo
languages: [Go, JavaScript, Python]
tags: [task-tracking, ai-agents, graph-database, git, issue-tracker]
date_saved: 2026-02-14
---
# Beads - Memory Upgrade for Coding Agents

## Summary
Beads (bd) is a distributed, git-backed graph issue tracker designed for AI coding agents. It replaces unstructured markdown plans with a dependency-aware task graph, enabling agents to handle long-horizon tasks without losing context. Powered by Dolt for version-controlled SQL with cell-level merge.

## Key Points
- Dependency-aware graph with hash-based IDs (bd-a1b2) preventing merge collisions in multi-agent workflows
- Supports hierarchical task IDs for epics, tasks, and sub-tasks
- Semantic "memory decay" compaction summarizes old closed tasks to save context window
- Messaging system with threading, ephemeral lifecycle, and mail delegation
- Graph links: relates_to, duplicates, supersedes, replies_to for knowledge graphs

## Related
- [[babyagi]] - autonomous agent task planning
- [[go-arch-lint]] - Go tooling
- [[centrifugo]] - Go infrastructure
