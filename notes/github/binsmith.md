---
url: https://github.com/caesarnine/binsmith
type: github-repo
languages: [Python]
tags: [ai-agents, cli-tools, workspace, automation, lattis]
date_saved: 2026-02-14
---
# Binsmith

## Summary
Binsmith is an agent that accumulates small CLI tools in a persistent workspace. Unlike stateless chat agents, it turns repeated work into reusable scripts stored in `~/.binsmith/workspace/bin`, so later tasks can compose existing tools. Distributed as a Lattis plugin with both TUI and web UI.

## Key Points
- Turns repeated agent work into persistent, reusable CLI scripts
- Tools stored in `~/.binsmith/workspace/bin` and carry across projects
- Uses a single tool: bash, with an agent prompt + workspace pattern
- Distributed as a Lattis plugin; also runs standalone via `uvx binsmith`
- Provides both TUI and web UI (localhost:8000)

## Related
- [[how-to-build-agents-with-filesystems-and-bash]]
- [[ai-agents]]
- [[unix-philosophy]]
