---
url: https://microsoft.github.io/presidio/
type: article
tags: [pii, data-protection, anonymization, microsoft, privacy]
date_saved: 2026-02-14
---
# Microsoft Presidio: Data Protection and De-identification SDK

## Summary
Presidio is Microsoft's open-source SDK for identifying and anonymizing PII (personally identifiable information) in text and images. It supports credit card numbers, names, locations, SSNs, and more using NER, regex, and rule-based logic.

## Key Points
- Modules: analyzer (text PII detection), anonymizer (de-identification), image redactor (OCR-based), structured (semi-structured data)
- Uses Named Entity Recognition, regex, rule-based logic, and checksums with context
- Supports Python, PySpark, Docker, and Kubernetes deployments
- Extensible with custom recognizers and external PII detection models
- Not a guarantee of complete PII detection — should be combined with other safeguards

## Related
- [[data-privacy]]
- [[named-entity-recognition]]
- [[pii-detection]]
