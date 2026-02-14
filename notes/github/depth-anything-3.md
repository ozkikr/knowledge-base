---
url: https://github.com/ByteDance-Seed/depth-anything-3
type: github-repo
languages: [Python]
tags: [depth-estimation, computer-vision, 3d-reconstruction, monocular-depth, pose-estimation]
date_saved: 2026-02-14
---
# Depth Anything 3

## Summary
Depth Anything 3 (DA3) by ByteDance predicts spatially consistent geometry from arbitrary visual inputs with or without known camera poses. It uses a single plain transformer (vanilla DINO encoder) with a unified depth-ray representation, significantly outperforming Depth Anything V2 for monocular depth and VGGT for multi-view depth/pose estimation. Trained exclusively on public academic datasets.

## Key Points
- Single plain transformer backbone without architectural specialization — minimal modeling approach
- Unified depth-ray representation handles monocular depth, multi-view depth, pose estimation, and 3D Gaussian estimation
- Multiple model series: Main (Giant/Large/Base/Small), Metric, Monocular, and Nested
- DA3-Streaming enables ultra-long video inference with <12GB GPU memory via sliding-window
- Includes interactive Gradio web UI, CLI for batch processing, and multiple export formats (glb, npz, ply, 3DGS)

## Related
- [[Hunyuan3D-2]]
- [[OmniParser]]
