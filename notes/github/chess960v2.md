---
url: https://github.com/lavren1974/chess960v2
type: github-repo
languages: [Go, TypeScript, SQL]
tags: [chess, simulation, stockfish, tournament]
date_saved: 2026-02-15
---
# chess960v2
## Summary
Chess960v2 is a Fischer Random Chess project that adds a second layer of randomization to produce broader opening diversity for engine play. The repository includes tooling to seed positions, schedule matches, run games with Stockfish, and store results in Supabase/Postgres. It also includes a web UI for reviewing championship progress.
## Key Points
- Implements a full Chess960v2 experiment pipeline: seeding, pairing, game execution, and result storage.
- Built around Go services, with optional Next.js UI and SQL schema for Supabase.
- Uses Stockfish 15.1 and UCI-style engine execution for large tournament runs.
- Supports reproducible championship workflows with environment-based configuration.
## Related
- [[Chess Engines]]
- [[Simulation Pipelines]]
- [[Supabase]]
