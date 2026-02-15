---
url: https://bonsplit.alasdairmonk.com/
type: article
tags: [macos, swift, ui-components, tab-management, split-view]
date_saved: 2026-02-15
---
# Bonsplit - Native macOS Tab Bar with Split Panes
## Summary
This page documents Bonsplit, a macOS UI component system for tabs and split panes, with a configuration-first API reference. It outlines feature toggles, layout constraints, insertion behavior, and lifecycle strategies for tab content views. The content reads as a practical implementation reference for developers building IDE-like macOS interfaces.

## Key Points
- `BonsplitConfiguration` controls key behavior like tab reordering, cross-pane movement, and pane auto-close.
- Supports different content lifecycle modes (`recreateOnSwitch` vs `keepAllAlive`) with memory/performance tradeoffs.
- Provides tunable appearance settings such as tab sizing, spacing, pane minimums, and animation control.
- Includes built-in presets (`default`, `singlePane`, `readOnly`) for quick configuration.

## Related
- [[macos-development]]
- [[swift-ui-components]]
- [[split-view-layouts]]
