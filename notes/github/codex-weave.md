---
url: https://github.com/rosem/codex-weave
type: github-repo
languages: [Rust, TypeScript, Shell]
tags: [codex-cli, multi-agent, orchestration, developer-tools]
date_saved: 2026-02-15
---
# codex-weave
## Summary
codex-weave is a fork of the Codex CLI that adds native agent-to-agent coordination. It introduces shared Weave sessions where multiple CLI agents can collaborate, relay tasks, and exchange control commands. The project keeps a familiar Codex workflow while extending it toward multi-agent orchestration.
## Key Points
- Extends Codex CLI with session-based multi-agent coordination.
- Adds relay messaging and agent control commands like `/new` and `/interrupt`.
- Provides a local coordinator service and shared agent identity features.
- Supports concurrent collaborative workflows without changing core CLI ergonomics.
- Distributed via npm as `@rosem_soo/weave`.
## Related
- [[Multi-Agent Systems]]
- [[CLI Tools]]
- [[Codex]]
