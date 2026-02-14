---
url: https://github.com/severity1/claude-code-prompt-improver
type: github-repo
languages: [JavaScript]
tags: [claude-code, prompt-engineering, developer-tools, hooks]
date_saved: 2026-02-14
---
# Claude Code Prompt Improver

## Summary
A UserPromptSubmit hook for Claude Code that enriches vague prompts before execution. It evaluates prompt clarity using conversation history, and for vague prompts, invokes a skill to research context and ask targeted clarifying questions.

## Key Points
- Intercepts prompts and evaluates clarity automatically
- Clear prompts pass through with zero overhead
- Vague prompts trigger research plan, context gathering, and 1-6 grounded questions
- Skill-based architecture achieves 31% token reduction (v0.4.0)
- Requires Claude Code 2.0.22+ for AskUserQuestion tool

## Related
- [[Wegent]] - AI agent systems
- [[optimizing-repos-for-ai]]
