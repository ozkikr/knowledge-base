---
url: https://github.com/holon-run/holon
type: github-repo
languages: [Go, Shell, JavaScript, TypeScript, CSS, HTML]
tags: [headless, ci-cd, coding-agent]
date_saved: 2026-02-15
---
# Holon

## Summary
Holon runs coding agents headlessly to convert issues into PR-ready patches and summaries. It standardizes outputs as artifacts (patch, summary, manifest) so runs are easier to audit in local or CI pipelines. The project is designed around sandboxed execution and repeatable automation.

## Key Points
- Automates issue/PR context collection, agent execution, and PR updates in one flow.
- Uses a patch-first artifact contract for deterministic downstream review and tooling.
- Supports containerized sandbox runs with optional persistent state mounts.
- Provides GitHub Actions workflows and local CLI usage with similar behavior.
- Allows custom skills/agent bundles to extend behavior without changing core workflow.

## Related
- [[Headless Automation]]
- [[Pull Requests]]
- [[AI Coding Agents]]
