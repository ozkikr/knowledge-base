---
url: https://github.com/covibes/zeroshot
type: github-repo
languages: [TypeScript, JavaScript]
tags: [ai-agents, orchestration, cli, code-generation, multi-agent]
date_saved: 2026-02-14
---
# Zeroshot - Autonomous Engineering Team in a CLI

## Summary
Zeroshot is an open-source AI coding agent orchestration CLI that runs multi-agent workflows to autonomously implement, review, test, and verify code changes. It supports Claude Code, OpenAI Codex, OpenCode, and Gemini CLI as providers, with GitHub, GitLab, Jira, and Azure DevOps as issue backends.

## Key Points
- Multi-agent pipeline: planner → implementer → independent validators, looping until verified
- Supports isolated workspaces (local, worktree, or Docker) for safe implementation
- Crash-safe with persisted state for resume/recovery
- Accepts GitHub issues, markdown files, or inline text as task input
- Provider-agnostic: works with Claude, Codex, Gemini, and OpenCode

## Related
- [[agentic-coding]] [[multi-agent]] [[ci-cd]] [[code-review]] [[orchestration]]
