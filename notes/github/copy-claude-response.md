---
url: https://github.com/Twizzes/copy-claude-response
type: github-repo
languages: [Shell]
tags: [claude-code, cli, clipboard, automation]
date_saved: 2026-02-15
---
# copy-claude-response
## Summary
A lightweight Claude Code hook that adds a `/copy-response` command for copying assistant responses to your clipboard. It supports grabbing the latest response, selecting by index, listing recent responses, and searching by keyword. The project is designed for fast day-to-day terminal workflows across macOS, Linux, and WSL.

## Key Points
- Adds a slash-command style workflow for copying prior Claude responses quickly.
- Supports `list` and `find` modes so you can browse or search previous outputs before copying.
- Works across platforms via native clipboard tools (`pbcopy`, `xclip`, `clip.exe`).
- Implemented as a hook script that intercepts prompt submissions before normal model handling.
- Requires common CLI dependencies (notably `jq`) and executable hook setup.

## Related
- [[claude-code]]
- [[cli-automation]]
- [[developer-tooling]]
