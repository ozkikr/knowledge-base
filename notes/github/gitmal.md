---
url: https://github.com/antonmedv/gitmal
type: github-repo
languages: [Go]
tags: [git, static-site-generator, code-browsing, self-hosted]
date_saved: 2026-02-14
---
# Gitmal - Static Page Generator for Git Repositories

## Summary
Gitmal generates static HTML pages from Git repositories with file browsing, commit history, syntax highlighting, and markdown rendering. It enables self-hosting a browsable web interface for your repos without requiring a Git forge.

## Key Points
- Generates static HTML with files, commits, code highlighting, and markdown rendering
- Supports custom code highlighting themes via --theme flag
- Available via `go install`, Docker, or prebuilt binaries
- Handles large repos (e.g., Kubernetes repo in ~25 min on M2 MacBook Air)
- Supports minification and gzip output

## Related
- [[git]]
- [[static-site-generator]]
- [[cgit]]
- [[self-hosted-git]]
