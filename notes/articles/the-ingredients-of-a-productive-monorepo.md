---
url: https://blog.swgillespie.me/posts/monorepo-ingredients/
type: article
tags: [monorepo, developer-productivity, build-systems, devtools, source-control]
date_saved: 2026-02-14
---

# The Ingredients of a Productive Monorepo

## Summary
A practitioner's guide to what it actually takes to run a productive monorepo, written by a developer infrastructure engineer. Dispels the hype from Google/Meta blog posts and lays out the concrete tools and principles you'll need to build yourself.

## Key Points
- **Golden Rule**: Every operation must be O(change), not O(repo) — this principle drives all monorepo tooling decisions
- Source control: git works longer than you think, but eventually you'll need sparse checkouts or virtual filesystems; Jujutsu is promising
- Build systems: stick with your language's native build system as long as possible before reaching for Bazel; keep the monorepo single-language if you can
- Generated code (protobuf, thrift) amplifies source control and build problems significantly
- Honest framing: you WILL NOT replicate Google/Meta's experience; better motivations are consistency, organizational coherence, and shared tooling

## Related
- [[developer-productivity]] — the team that owns this work
- [[build-systems]] — Bazel, Cargo, Go build tooling
