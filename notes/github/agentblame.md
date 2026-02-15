---
url: https://github.com/mesa-dot-dev/agentblame
type: github-repo
languages: [TypeScript, CSS, Shell]
tags: [code-attribution, github-pr, ai-governance]
date_saved: 2026-02-15
---
# agentblame
## Summary
Agent Blame tracks which code lines were AI-generated versus human-authored and exposes that signal in CLI and browser extensions. It captures attribution through hooks, persists metadata in Git notes, and preserves provenance through squash/rebase merges. This helps teams focus reviews and analytics on higher-risk AI-generated changes.
## Key Points
- Annotates PRs with line-level AI markers and file/repo AI percentages.
- Integrates with Cursor, Claude Code, and OpenCode via local hooks.
- Uses Git notes and workflows to retain attribution under non-linear merge patterns.
- Includes repo analytics for tools/models usage and contributor-level AI ratios.
## Related
- [[Code Review]]
- [[AI Governance]]
- [[Software Supply Chain]]
