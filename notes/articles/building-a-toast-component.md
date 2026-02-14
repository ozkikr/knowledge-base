---
url: https://emilkowal.ski/ui/building-a-toast-component
type: article
tags: [react, ui-components, animation, open-source, sonner]
date_saved: 2026-02-14
---
# Building a Toast Component

## Summary
Emil Kowalski describes how he built Sonner, a toast library now downloaded 8M+ times/week and used by Cursor, X, and Vercel. The article covers naming strategy, the signature stacking animation, and technical decisions around CSS transitions vs keyframes.

## Key Points
- Named "Sonner" (French for "to ring") to stand out from generic react-toast libraries
- The stacking animation was the key differentiator that drove viral adoption
- CSS keyframes aren't interruptible; switched to inline styles/transitions for smooth animation
- Now the default toast component in shadcn/ui
- Marketing the animation in announcement videos was crucial for adoption

## Related
- [[react]], [[ui-design]], [[css-animations]], [[shadcn-ui]]
