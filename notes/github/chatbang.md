---
url: https://github.com/ahmedhosssam/chatbang
type: github-repo
tags: [cli, chatgpt, go, terminal]
date_saved: 2026-02-14
---
# Chatbang

## Summary
Chatbang is a CLI tool written in Go that lets you access ChatGPT from the terminal without needing an API key. It works by automating a Chromium-based browser session to interact with ChatGPT's web interface.

## Key Points
- No API key required — uses browser automation with a Chromium-based browser
- Written in Go, installable via binary download or from source
- Requires initial login via `chatbang --config` to set up a Chromium session
- Clipboard permission must be granted for ChatGPT's website
- Does not work with Snap-installed browsers

## Related
- [[gemini-cli]] - another CLI for LLM access
- [[plock]] - LLM access from anywhere you can type
