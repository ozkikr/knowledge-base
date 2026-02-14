---
url: https://github.blog/ai-and-ml/github-copilot/how-to-write-a-great-agents-md-lessons-from-over-2500-repositories/
type: article
tags: [agents-md, github-copilot, ai-agents, prompt-engineering, developer-tools]
date_saved: 2026-02-14
---
# How to Write a Great agents.md: Lessons from Over 2,500 Repositories

## Summary
GitHub's analysis of 2,500+ agents.md files reveals what makes effective agent definitions for GitHub Copilot. The key pattern: give agents a specific persona, exact commands, well-defined boundaries, and clear examples. The article provides templates and recommends six types of agents worth building (docs, test, security, lint, migration, review).

## Key Points
- Put executable commands early in the file with flags and options, not just tool names
- Code examples beat explanations — show what good output looks like
- Set three-tier boundaries: always do, ask first, never do
- Be specific about your stack with versions and key dependencies
- Cover six core areas: commands, testing, project structure, code style, git workflow, and boundaries

## Related
- [[agents-md]]
- [[context-engineering-for-agents]]
- [[how-to-turn-claude-code-into-a-domain-specific-coding-agent]]
