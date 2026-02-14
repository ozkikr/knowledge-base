---
url: https://laurentsv.com/blog/2024/10/19/no-nonsense-go-package-layout.html
type: article
tags: [go, project-structure, best-practices, package-layout]
date_saved: 2026-02-14
---
# No Nonsense Guide to Go Projects Layout

## Summary
A pragmatic guide to Go project layout that pushes back against over-engineering. The author argues against cargo-culting patterns like `internal/`, `pkg/`, and `cmd/` when they're not needed, emphasizing Go's philosophy of simplicity and writing code before structuring.

## Key Points
- Official guide at go.dev/doc/modules/layout is the starting point; most projects don't need `internal/` or `cmd/`
- The "golang-standards/project-layout" repo is NOT an official standard (see issue #117)
- Put `main` in the root for shortest `go install` path; move it only when you also ship a library
- `pkg/` is outdated; `internal/` is a toolchain feature, not a requirement — skip unless shipping to many third parties
- Stick to 0.x semver as long as possible to avoid Go's v2/v3 module path pain

## Related
- [[go-best-practices]]
- [[go-modules]]
- [[project-structure]]
