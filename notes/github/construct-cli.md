---
url: https://github.com/EstebanForge/construct-cli
type: github-repo
languages: [Go]
tags: [ai-agents, sandbox, security, containers, docker]
date_saved: 2026-02-14
---
# Construct CLI

## Summary
Construct CLI is a single-binary tool that boots isolated sandboxed containers preloaded with AI agents (Claude Code, Codex, etc.). It protects against LLM prompt injection attacks and accidental file deletion by keeping agents in secure containers with configurable network isolation.

## Key Points
- One command to run any AI agent inside a secured, isolated container sandbox
- Works with Docker, Podman, or macOS native container runtime; auto-detects best option
- Network isolation modes: permissive, strict, offline with domain allow/block lists
- SSH agent forwarding, full clipboard bridge (text + images), and headless browser automation
- Persistent volumes for agent configs but ephemeral containers for clean host

## Related
- [[claude-code]]
- [[docker]]
- [[ai-safety]]
- [[sandboxing]]
