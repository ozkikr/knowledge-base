---
url: https://seg6.space/posts/making-macos-bearable/
type: article
tags: [macos, tiling-wm, aerospace, tmux, productivity, developer-workflow]
date_saved: 2026-02-14
---
# Making macOS Bearable

## Summary
A developer coming from 8 years of Arch Linux describes how to make macOS feel like a seamless extension of the body rather than a source of friction. The article covers using Aerospace (tiling WM) for deterministic window placement, Ghostty+Tmux for terminal workflow, modal editing philosophy, and a custom Rust tool called `ws` for project session management.

## Key Points
- Navigation hierarchy: shortcuts > fuzzy finding > visual search (avoid Mission Control's "Where's Waldo" problem)
- Aerospace replaces Spaces with rigid, deterministic workspaces — spatially encode apps (browser=1, terminal=2, Spotify=9)
- Tmux with root bindings (no prefix) and auto-creating windows for frictionless navigation
- Custom `ws` tool in Rust for fuzzy-find project switching with stack-based history
- Modal editing (Helix) turns text manipulation into linguistic commands rather than manual labor

## Related
- [[go-qo]] - Terminal TUI tool
