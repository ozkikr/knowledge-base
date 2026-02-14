---
url: https://github.com/atlekbai/stateless
type: github-repo
languages: [Go]
tags: [state-machine, library, generics, go, visualization]
date_saved: 2026-02-14
---
# Stateless

## Summary
A feature-complete, generic state machine library for Go inspired by the .NET Stateless library. Supports hierarchical states, guard conditions, parameterized triggers, and graph generation in DOT/Mermaid formats.

## Key Points
- Generic types: use any comparable type for states and triggers
- Fluent configuration API with guard conditions, entry/exit actions, and dynamic transitions
- Hierarchical states (substates/superstates) and internal/reentry transitions
- Graph export to DOT (Graphviz) and Mermaid for visualization
- Thread-safe with queued firing mode; full context.Context and error support

## Related
- [[finite-state-machines]] - CS concept
- [[go-libraries]] - Go ecosystem
- [[workflow-engines]]
