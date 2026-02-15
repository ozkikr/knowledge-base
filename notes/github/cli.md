---
url: https://github.com/entireio/cli
type: github-repo
languages: [Go, Shell]
tags: [git-workflow, agent-traceability, developer-productivity]
date_saved: 2026-02-15
---
# cli (Entire)
## Summary
Entire CLI captures AI coding session metadata alongside normal Git workflows so teams can trace why and how code was produced. It stores checkpoint/session data on a dedicated branch while keeping feature branch history clean. The tool supports rewind/resume flows and strategy modes for manual or auto checkpoint behavior.
## Key Points
- Hooks into Git workflows to persist prompts, responses, and touched files.
- Stores metadata on `entire/checkpoints/v1` rather than polluting normal commit history.
- Supports rewind and resume of session state for safer iterative agent usage.
- Works across worktrees and concurrent sessions with strategy-driven checkpointing.
## Related
- [[GitOps]]
- [[AI Code Provenance]]
- [[Developer Experience]]
