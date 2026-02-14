---
url: https://kau.sh/blog/agent-forking/
type: article
tags: [agentic-coding, tmux, subagents, workflow, claude-code]
date_saved: 2026-02-14
---
# Forking Subagents in an AI Coding Session with tmux

## Summary
Kaushik Gopal describes a lightweight approach to spawning subagent sessions during agentic coding using a simple Bash script and tmux. The method lets you fork a new agent instance with existing context to pursue tangential exploration or parallel work, while keeping the main session focused.

## Key Points
- Uses a thin Bash script + tmux — no heavy framework, tool-agnostic across Claude Code, Codex CLI, Gemini
- Forks preserve context from the main session; long transcripts are auto-summarized before seeding
- Subagent sessions are interactive (not one-shot), labeled in tmux windows for tracking
- Keeps tangential work out of the main session to avoid context bloat
- Copy-paste between tmux panes is the primary way to bring results back

## Related
- [[agentic-coding]] [[claude-code]] [[tmux]] [[developer-workflows]] [[subagents]]
