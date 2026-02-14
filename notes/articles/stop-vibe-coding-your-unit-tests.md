---
url: https://www.andy-gallagher.com/blog/stop-vibe-coding-your-unit-tests/
type: article
tags: [testing, llm, vibe-coding, software-engineering, code-quality]
date_saved: 2026-02-14
---
# Stop Vibe Coding Your Unit Tests

## Summary
Andy Gallagher argues that LLM-generated unit tests are unconstructive, noisy, and brittle. The core problem: LLMs write too many tests that verify what code *does* rather than validating what it *should* do, producing PRs full of meaningless coverage.

## Key Points
- LLMs generate too many unit tests that add noise without value
- AI tests verify implementation (what code does) not specification (what it should do)
- Common workflow: generate code → generate tests → iterate — produces brittle tests
- Even excellent developers submit good code with nonsense AI-generated tests
- Tests should encode intent and specification, not mirror implementation

## Related
- [[testing]] [[vibe-coding]] [[code-quality]] [[llm-limitations]]
