---
url: https://github.com/steveklabnik/docket
type: github-repo
languages: [Rust]
tags: [task-management, cli, ai-assisted-development]
date_saved: 2026-02-15
---
# Docket
## Summary
Docket is a command-line task and bug tracker built for AI-assisted software workflows. It integrates tightly with Claude Code and Jujutsu (jj) to manage work item state, workspaces, and completion handoff. The tool is centered on structured execution from draft to done.

## Key Points
- Implements a lightweight lifecycle for work items: Draft → Approved → InProgress → Done.
- `docket work` creates context-aware workspaces and launches assistant-oriented implementation flows.
- `docket done` supports completion and commit-message generation workflows.
- Includes shell completion generation and local configuration options.
- Targets developers who want issue tracking embedded directly in terminal workflows.

## Related
- [[CLI Task Management]]
- [[Jujutsu]]
- [[AI Coding Workflow]]
