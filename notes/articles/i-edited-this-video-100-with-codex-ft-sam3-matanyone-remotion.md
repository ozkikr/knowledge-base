---
url: https://adithyan.io/blog/codex-text-effects-toolchain
type: article
tags: [codex, video-editing, remotion]
date_saved: 2026-02-15
---
# I Edited This Video 100% With Codex ft. SAM3 + MatAnyone + Remotion
## Summary
This post shows a full AI-assisted video workflow where Codex is used as a “terminal video editor” instead of traditional timeline tools. The author combines SAM3 for segmentation, MatAnyone for tracked foreground mattes, and Remotion for final compositing and text effects. The result is production of advanced occlusion effects through iterative code and prompt-driven refinement.

## Key Points
- The pipeline is SAM3 (seed mask) → MatAnyone (full-video matte tracking) → Remotion (composition and animation).
- The author reports this is currently slower than manual editing, but useful for building reusable editing primitives.
- Codex is used iteratively with a storyboard JSON and timestamped transcript JSON for word-level animation timing.
- Multiple Codex sessions are run in parallel for different storyboard parts.
- Self-review loops (rendering selected frames and critiquing outputs) improve iteration speed and quality.

## Related
- [[Codex]]
- [[Remotion]]
- [[Video Compositing]]
