---
url: https://github.com/CyberMagician/Project_Golem
type: github-repo
languages: [Python, JavaScript]
tags: [rag, 3d-visualization, vector-database, embeddings, threejs]
date_saved: 2026-02-14
---
# Project Golem

## Summary
A 3D interface for visualizing RAG memory structures in real-time. It projects high-dimensional embeddings (768d) to 3D interactive space using UMAP, allowing visual debugging of how an AI associates concepts.

## Key Points
- Visualizes semantic space as interactive 3D "cortex" using Three.js/WebGL
- Uses Google embedding-gemma-300m via sentence-transformers
- UMAP for dimensionality reduction from 768d to 3D
- LanceDB for storage with local NumPy for fast cosine similarity
- Flask backend, customizable knowledge domains

## Related
- [[rag]] [[vector-databases]] [[embeddings]] [[visualization]] [[umap]]
