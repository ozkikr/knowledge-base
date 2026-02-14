---
url: https://github.com/alinaqi/claude-bootstrap
type: github-repo
languages: [TypeScript]
tags: [claude-code, developer-tools, tdd, ai-coding, security]
date_saved: 2026-02-14
---
# Claude Bootstrap

## Summary
Claude Bootstrap is an opinionated project initialization system for Claude Code featuring agent teams by default, strict TDD pipeline, multi-engine code review, and security-first design. It coordinates AI agents (Team Lead, Quality, Security, Code Review, Merger, Feature) following an immutable pipeline.

## Key Points
- Agent teams: Team Lead, Quality, Security, Code Review, Merger, and Feature agents
- Immutable pipeline: Spec → Tests → Fail → Implement → Pass → Review → Security → PR
- Strict constraints: 20 lines/function, 200 lines/file, 3 params max
- Multi-engine code review with severity-based blocking
- Security by default with dependency scanning and pre-commit hooks

## Related
- [[claude-code]] - AI coding assistant
- [[tdd]] - Test-driven development
- [[ai-coding]] - AI-assisted development workflows
