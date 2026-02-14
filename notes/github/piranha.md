---
url: https://github.com/uber/piranha
type: github-repo
tags: [code-refactoring, feature-flags, static-analysis, rust]
date_saved: 2026-02-14
---
# Piranha (PolyglotPiranha)

## Summary
PolyglotPiranha is Uber's lightweight code transformation toolset for automating large-scale code changes, primarily used to clean up stale feature flags. It supports rule-based transformations with a graph of cleanup rules across multiple languages.

## Key Points
- Automates large-scale code refactoring, especially stale feature flag cleanup
- Rule graph system: define transformation rules with edges for chained cleanups
- Available as Python library (`polyglot-piranha`) and CLI (built in Rust)
- Supports concrete syntax matching for precise code transformations
- Only supports languages used at Uber; community forks add more

## Related
- [[agenta]] - Production LLM tooling
