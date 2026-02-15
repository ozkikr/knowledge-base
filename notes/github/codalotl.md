---
url: https://github.com/codalotl/codalotl
type: github-repo
languages: [Go, Python, Shell, MDX]
tags: [go, coding-agent, tui]
date_saved: 2026-02-15
---
# codalotl

## Summary
Codalotl is a Go-specialized coding agent delivered as a TUI and CLI. It focuses on package-scoped workflows to reduce context overload and improve performance on Go development tasks. The project reports benchmark gains in cost and runtime versus general-purpose coding agents for comparable Go prompts.

## Key Points
- Package mode constrains edits to a target Go package while exposing relevant API-level context.
- Generates initial package intelligence (symbols, dependents, build/test/lint status) before prompting.
- Applies gofmt and lint/build checks automatically during patching.
- Intentionally omits direct shell access to reduce out-of-scope exploration.
- Supports subagents for upstream/downstream package changes in larger repos.

## Related
- [[Go]]
- [[AI Coding Agents]]
- [[Terminal UIs]]
