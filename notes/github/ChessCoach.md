---
url: https://github.com/chrisbutner/ChessCoach
type: github-repo
languages: [C++, Python]
tags: [chess, neural-network, self-play, natural-language, alphazero]
date_saved: 2026-02-14
---
# ChessCoach

## Summary
ChessCoach is a neural network-based chess engine (~3450 Elo) capable of natural language commentary on moves and positions. It uses AlphaZero-style self-play training, starting from just the rules of chess and learning through a feedback cycle of stronger evaluation and stronger search.

## Key Points
- Approximately 3450 Elo — beats most humans but loses to top engines like Stockfish 14
- AlphaZero-style self-play training from scratch (no human games needed)
- Additional neural network generates English commentary on moves/positions
- Supports GPU and TPU training/inference on Linux and Windows
- Available on Lichess as @PlayChessCoach

## Related
- [[alphazero]] - inspiration for the training approach
- [[self-play]] - core training methodology
- [[neural-network-chess]] - neural network evaluation in chess
