---
url: https://github.com/fe3dback/go-arch-lint
type: github-repo
languages: [Go]
tags: [linter, architecture, clean-architecture, ci, static-analysis]
date_saved: 2026-02-14
---
# go-arch-lint - Go Architecture Linter

## Summary
go-arch-lint is a Go architecture linter that checks all project import paths against architecture rules defined in a YAML config file. It enforces layered architecture patterns (hexagonal, onion, DDD, MVC) by validating that components only depend on allowed layers, making it ideal for CI pipelines.

## Key Points
- Declarative YAML config defining components and allowed dependencies
- Supports wildcard matching for package paths (single-level and multi-level)
- Catches architecture violations like handlers importing repositories directly
- Available via Docker, precompiled binaries, or go install
- Designed for CI integration to continuously enforce architecture rules

## Related
- [[centrifugo]] - Go project
- [[how-slow-is-channel-iteration]] - Go development
- [[beads]] - Go tooling for developers
