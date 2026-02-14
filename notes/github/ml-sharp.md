---
url: https://github.com/apple/ml-sharp
type: github-repo
languages: [Python]
tags: [computer-vision, 3d-reconstruction, gaussian-splatting, view-synthesis, apple]
date_saved: 2026-02-14
---
# SHARP - Monocular View Synthesis in Less Than a Second

## Summary
Apple research project for photorealistic view synthesis from a single image. SHARP regresses 3D Gaussian representation parameters from a single photograph in under a second via feedforward neural network, enabling real-time novel view rendering.

## Key Points
- Single-image to 3D Gaussian splatting in <1 second on standard GPU
- Metric-scale 3D reconstruction with absolute scale
- State of the art: 25-34% LPIPS reduction, 21-43% DISTS reduction vs prior work
- 3 orders of magnitude faster synthesis than previous methods
- CLI tool: `sharp predict -i input -o output`
- Zero-shot generalization across datasets

## Related
- [[gaussian-splatting]] - 3D representation format
- [[novel-view-synthesis]]
- [[monocular-depth-estimation]]
