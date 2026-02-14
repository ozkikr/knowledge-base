---
url: https://github.com/plandex-ai/plandex
type: github-repo
tags: [ai-coding-agent, terminal, multi-file, autonomous-coding]
date_saved: 2026-02-14
---

# Plandex

## Summary
Plandex is a terminal-based AI coding agent designed for large projects and real-world tasks. It handles up to 2M tokens of context, uses tree-sitter project maps, and provides a cumulative diff review sandbox to keep AI changes separate from your project until approved.

## Key Points
- 2M token effective context window; loads only what's needed per step with tree-sitter maps (30+ languages)
- Cumulative diff sandbox with version control, branching, and rollback for every plan update
- Configurable autonomy from full auto mode to fine-grained step-by-step control
- Combines models from Anthropic, OpenAI, Google, and open source via curated model packs
- Plandex Cloud is winding down; self-hosted/local Docker mode is the path forward

## Related
- [[context-engineering-for-agents]] — managing large context windows
