---
url: https://github.com/gitui-org/gitui
type: github-repo
tags: [rust, git, tui, terminal]
date_saved: 2026-02-14
---

# GitUI

## Summary
A blazing fast terminal UI for git written in Rust. Provides the comfort of a git GUI right in the terminal, significantly outperforming alternatives like lazygit and tig on large repositories.

## Key Points
- Parses Linux kernel repo (900k+ commits) in 24s vs lazygit's 57s and tig's 4m20s
- Uses only 0.17GB memory vs lazygit's 2.6GB
- Full feature set: stage/unstage, commit, stash, push/fetch, branch management, log browsing
- Keyboard-driven with context-based help
- Async git API for fluid control

## Related
- [[lazygit]] - alternative git TUI
- [[television]] - another Rust terminal tool
- [[tig]] - text-mode interface for git
