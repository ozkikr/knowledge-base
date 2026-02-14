---
url: https://github.com/agentify-sh/safeexec
type: github-repo
languages: [Bash]
tags: [safety, destructive-commands, ai-agents, codex, shell-protection]
date_saved: 2026-02-14
---
# SafeExec

## Summary
SafeExec is a Bash-based safety layer that intercepts destructive commands (like `rm -rf` or `git reset --hard`) and enforces interactive confirmation gates. Designed to protect against accidental or AI-hallucinated destructive operations on Ubuntu/Debian/WSL and macOS.

## Key Points
- TTY-based confirmation gate — requires typing "confirm" via real terminal device, not stdin
- Gates destructive `rm` (recursive + force), `git reset`, `git revert`, `git checkout`, `git clean -f`, etc.
- Blocks commands entirely when no usable TTY is available (exit 126)
- Includes sudo protection via sudoers.d integration
- macOS support with Homebrew git shim coverage for both Apple Silicon and Intel

## Related
- [[coding-agents]]
- [[how-to-build-a-coding-agent]]
