---
url: https://github.com/pranshuparmar/witr
type: github-repo
languages: [Go]
tags: [devops, debugging, process-management, system-administration]
date_saved: 2026-02-14
---
# witr - Why Is This Running?

## Summary
CLI tool that answers "Why is this running?" for any process, service, or port-bound thing on a system. Unlike ps/top/lsof which show *what* is running, witr traces the causal chain explaining *why* something is running — supervisors, containers, services, or shells.

## Key Points
- Makes process causality explicit in a single human-readable output
- Traces chains across supervisors, containers, services, and shells
- Single static binary for Linux, macOS, FreeBSD, and Windows
- Available via Homebrew, Conda, Winget, and other package managers
- Correlates data from ps, lsof, ss, systemctl, docker in one view

## Related
- [[process-management]]
- [[system-debugging]]
- [[docker]]
