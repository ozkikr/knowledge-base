---
url: https://github.com/riverlytech/srt
type: github-repo
languages: [Go, C, Python, Shell]
tags: [sandboxing, security, runtime, linux]
date_saved: 2026-02-15
---
# srt
## Summary
srt is a Go-based Linux sandbox runtime inspired by Anthropic's sandbox-runtime architecture. It wraps arbitrary commands with filesystem and network controls using bubblewrap, with optional seccomp filtering. The project aims for secure-by-default execution in local or automated environments.
## Key Points
- Go implementation of a command sandbox focused on Linux.
- Enforces filesystem and network policies via JSON configuration.
- Integrates bubblewrap and optional seccomp filters.
- Supports explicit allow/deny rules for domains and write paths.
- Includes CLI tooling and tests for sandbox behavior.
## Related
- [[Sandboxing]]
- [[Seccomp]]
- [[Agent Runtime Security]]
