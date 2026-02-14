---
url: https://github.com/PriorLabs/TabPFN
type: github-repo
languages: [Python]
tags: [tabular-data, foundation-model, machine-learning, sklearn, classification, regression]
date_saved: 2026-02-14
---
# TabPFN — Foundation Model for Tabular Data

## Summary
TabPFN is a foundation model for tabular data that provides sklearn-compatible classifiers and regressors. It achieves strong performance on small-to-medium datasets with minimal configuration, offering both local GPU inference and a cloud-based client option.

## Key Points
- Sklearn-compatible API: `TabPFNClassifier` and `TabPFNRegressor`
- GPU recommended (~8GB VRAM); CPU feasible for ≤1000 samples
- Ecosystem includes extensions for interpretability (SHAP), embeddings, outlier detection
- Current version is TabPFN 2.5, with v2 also available
- Free hosted inference available via TabPFN Client for users without GPUs

## Related
- [[scikit-learn]]
- [[Foundation Models]]
- [[AutoML]]
- [[Tabular Data]]
