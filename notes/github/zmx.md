---
url: https://github.com/neurosnap/zmx
type: github-repo
languages: [Zig]
tags: [terminal, session-persistence, tmux-alternative, pty]
date_saved: 2026-02-14
---
# zmx - Session Persistence for Terminal Processes

## Summary
zmx is a lightweight terminal session persistence tool written in Zig. It allows attaching/detaching from shell sessions without killing them, similar to tmux but focused solely on session persistence without windows, tabs, or splits.

## Key Points
- Persist terminal shell sessions (pty processes) with attach/detach
- Multiple clients can connect to the same session simultaneously
- Re-attaching restores previous terminal state and output with native scrollback
- Send commands to sessions without attaching; print scrollback as plain text
- Works on macOS and Linux; does NOT provide windows, tabs, or splits

## Related
- [[tmux]]
- [[terminal-multiplexer]]
- [[screen]]
