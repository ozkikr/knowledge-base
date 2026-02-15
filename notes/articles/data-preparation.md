---
url: https://docs.distillabs.ai/how-to/data-preparation
type: article
tags: [distillation, data-prep, model-training]
date_saved: 2026-02-15
---
# Data Preparation
## Summary
This Distil Labs guide outlines the required inputs for a training job: job description, training data, test data, configuration, and optional unstructured data. It emphasizes quality over quantity, especially for labeled examples, and frames test data as the key generalization check before deployment. The page also links to task-specific formatting guides and provides a Python upload example.

## Key Points
- A clear job description defines task intent, output format, and constraints for training.
- Training examples should be representative and high quality; a few dozen can be enough.
- Test data is kept separate to validate generalization and expose weak spots.
- Optional unstructured data helps inject domain context without additional labels.
- Config files control model size, task type, and training behavior; upload is handled through the Distil Labs API.

## Related
- [[Knowledge Distillation]]
- [[Dataset Curation]]
- [[Model Evaluation]]
