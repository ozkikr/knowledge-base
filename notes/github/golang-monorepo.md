---
url: https://github.com/flowerinthenight/golang-monorepo
type: github-repo
tags: [golang, monorepo, ci-cd, circleci, github-actions]
date_saved: 2026-02-14
---

# golang-monorepo

## Summary
An example of a Go-based monorepo structure that only builds modified services/commands per commit, with smart dependency detection for shared code changes. Supports CircleCI 2.1 and GitHub Actions.

## Key Points
- Selective builds: only builds services modified in a commit
- Dependency-aware: rebuilds all affected services when common/internal code changes
- Vendor-aware: rebuilds all when vendor code changes
- Uses bash scripts + Makefiles, portable to other CI systems
- GO111MODULE=on with -mod=vendor setup

## Related
- [[Context-Engineering]] - project structure as context
