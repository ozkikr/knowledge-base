---
url: https://simonwillison.net/2025/Oct/16/claude-skills
type: article
tags: [claude, skills, anthropic, ai-agents, mcp]
date_saved: 2026-02-14
---
# Claude Skills Are Awesome, Maybe a Bigger Deal Than MCP

## Summary
Simon Willison covers Anthropic's Claude Skills — markdown files with instructions, scripts, and resources that Claude loads on-demand for specialized tasks. Skills are conceptually simple but powerful: token-efficient frontmatter scanning at session start, with full details loaded only when relevant. Document creation features (.pdf, .docx, .xlsx, .pptx) are entirely implemented as skills.

## Key Points
- Skills are markdown files + optional scripts that teach Claude how to do specific tasks
- Token-efficient: only frontmatter scanned at session start, full content loaded on demand
- Claude's document creation abilities are entirely skill-based implementations
- Skills depend on a coding environment (code interpreter) to execute scripts
- Potentially bigger than MCP due to simplicity — just files on disk, no server needed

## Related
- [[claude-code-decoded-handoff-protocol]] - Claude Code patterns
- [[just-talk-to-it]] - agentic engineering
- [[inkeep-agents]] - agent frameworks
