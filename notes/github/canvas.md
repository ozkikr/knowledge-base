---
url: https://github.com/tdewolff/canvas
type: github-repo
languages: [Go]
tags: [vector-graphics, svg, pdf, rendering, 2d-graphics]
date_saved: 2026-02-14
---
# canvas - Vector Graphics in Go

## Summary
Canvas is a Go library for vector graphics that can output SVG, PDF, EPS, raster images (PNG, JPG, GIF), HTML Canvas via WASM, OpenGL, and Gio. It includes path manipulation (flattening, stroking, dashing), text formatting with Knuth's line-breaking algorithm, and font embedding/subsetting.

## Key Points
- Multi-format output: SVG, PDF, EPS, PNG, JPG, GIF, HTML Canvas (WASM), OpenGL, Gio
- Comprehensive path manipulation: flattening, stroking, dashing, boolean operations
- Text formatter with Donald Knuth's line-breaking algorithm and LTR/RTL support
- Font embedding and subsetting (TTF, OTF, WOFF, WOFF2, EOT)
- Can be considered a Cairo or node-canvas alternative in Go

## Related
- [[go-graphics]]
- [[svg]]
- [[pdf-generation]]
