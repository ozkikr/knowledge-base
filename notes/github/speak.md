---
url: https://github.com/agentify-sh/speak
type: github-repo
languages: [Shell]
tags: [codex, tts, swiftbar, developer-experience]
date_saved: 2026-02-15
---
# speak
## Summary
A macOS-focused utility that makes Codex CLI speak assistant responses after each turn. It installs a notifier script and optional SwiftBar integration for quick play/stop control from the menu bar. The tool supports low-latency native speech and an optional higher-latency Pocket TTS mode.

## Key Points
- Hooks into Codex turn completion and reads out an intelligent summary of the latest response.
- Provides menu bar status and controls through a SwiftBar plugin.
- Supports replay, full replay, stop, and engine switching commands from terminal.
- Handles overlapping completions by queueing and speaking the newest pending result.
- Keeps runtime state locally without storing credentials.

## Related
- [[codex-cli]]
- [[text-to-speech]]
- [[swiftbar]]
