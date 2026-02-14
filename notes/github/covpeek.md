---
url: https://github.com/Chapati-Systems/covpeek
type: github-repo
languages: [Go]
tags: [coverage, cli, multi-language, testing]
date_saved: 2026-02-14
---
# covpeek - Cross-language Coverage Report CLI Parser

## Summary
covpeek is a Go CLI tool that parses coverage reports from multiple languages (Rust, Go, TypeScript/JavaScript, Python) with one unified tool. It supports auto-detection of formats, multiple output formats (table, JSON, CSV), an interactive TUI, and direct upload to SonarQube and Codecov.

## Key Points
- Parses LCOV, Go native (.out), Cobertura XML, and JSON coverage formats
- Auto-detects coverage file format by extension or content
- Interactive TUI for exploring coverage data
- CI integration with threshold checks and coverage diff between git commits
- Direct upload to SonarQube and Codecov platforms

## Related
- [[code-coverage]]
- [[cli-tools]]
- [[continuous-integration]]
