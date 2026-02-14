---
url: https://github.com/creack/pty
type: github-repo
tags: [go, pty, pseudo-terminal, unix]
date_saved: 2026-02-14
---
# pty

## Summary
pty is a Go package for working with Unix pseudo-terminals. It provides a simple API to start commands with a PTY, handle terminal resizing, and manage raw mode I/O.

## Key Points
- Simple API: `pty.Start(cmd)` to run commands with a pseudo-terminal
- Supports terminal window size inheritance and SIGWINCH handling
- Works with raw mode via `golang.org/x/term`
- Widely used Go library for terminal emulation and CLI tools
- Cross-platform Unix support

## Related
- [[go-libraries]]
- [[terminal-emulation]]
- [[unix-pty]]
