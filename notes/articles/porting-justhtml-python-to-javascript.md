---
url: https://simonwillison.net/2025/Dec/15/porting-justhtml/
type: article
tags: [coding-agents, html-parser, codex-cli, gpt-5, porting]
date_saved: 2026-02-14
---
# Porting JustHTML from Python to JavaScript with Codex CLI and GPT-5.2

## Summary
Simon Willison ported JustHTML (a pure-Python HTML5 parser) to JavaScript using Codex CLI with GPT-5.2 in ~4.5 hours. The result, justjshtml, passes 9,200 html5lib-tests and consists of 9,000 lines of dependency-free JavaScript across 43 commits.

## Key Points
- Ported a full HTML5 parser from Python to JS using two initial prompts in Codex CLI
- GPT-5.2 ran uninterrupted for hours, producing 9,000 lines across 43 commits
- Passes 9,200 tests from the html5lib-tests suite
- Total cost: ~98M cached input tokens + 625K output tokens
- Done while decorating a Christmas tree and watching a movie

## Related
- [[coding-agents-and-complexity-budgets]]
- [[ai-coding-agents]]
- [[html-parsing]]
- [[codex-cli]]
