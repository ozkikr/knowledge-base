---
url: https://github.com/simonw/rodney
type: github-repo
languages: [Go, Shell]
tags: [browser-automation, cli, chrome]
date_saved: 2026-02-15
---
# rodney
## Summary
Rodney is a Go CLI for controlling a persistent headless Chrome instance from the terminal. Each command connects to the same long-running browser process, enabling scriptable multi-step automation without rebuilding session state every invocation. The tool includes navigation, DOM interaction, screenshots, JS execution, and accessibility inspection commands.

## Key Points
- Uses go-rod and Chrome DevTools Protocol over WebSocket to control a persistent browser.
- Separates short-lived CLI commands from long-lived Chrome runtime state.
- Supports common automation primitives: click, type, wait, extract, screenshot, and tab management.
- Includes accessibility-focused commands (`ax-tree`, `ax-find`, `ax-node`) for testing workflows.
- Handles authenticated proxy environments with a local forwarding proxy strategy.

## Related
- [[chromedevtools-protocol]]
- [[cli-automation]]
- [[accessibility-testing]]
