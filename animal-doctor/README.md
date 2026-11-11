---
pretty_name: RuralLens Animal / livestock visual triage
task_categories:
- image-classification
library_name: pytorch
tags:
- rurallens
- research
---

# RuralLens Animal / livestock visual triage (experimental checkpoint)

11 animal categories; not the complete 20-class target. Documented animal sources include gaps and diseases that may require laboratory or clinical diagnosis.

## Files

- `animal-mobilenet_v3_small-optimized.pt` — PyTorch checkpoint (`.pt`).
- `animal-optimized-comparison.json` — comparison metadata, class names/counts, split details, and training/validation metrics.

The comparison metadata reports an image size of 160 px for this training run. Consult the app and training code before interpreting preprocessing, tensor layout, class ordering, or output semantics.

## Important limitations and rights

This checkpoint is an experimental research artifact for visual triage, **not** a validated diagnostic model. The project hard gate of at least 90% leakage-safe held-out accuracy across all 20 classes in each domain was not met; the full 20-class gate was not evaluated and there is no valid final 20-class held-out accuracy to report. The checkpoint covers only the subset listed in its comparison JSON. Validation metrics in that JSON are subset validation results, not full-domain held-out test results.

The project audit documents upstream image sources with non-commercial and/or no-derivatives restrictions, plus per-source attribution requirements. Consequently, commercial use and redistribution rights for this checkpoint are not assured by this upload. Review the source dataset licenses and the project boundary report before reuse. This repository does not add a blanket license or grant rights beyond those the uploader holds.

These artifacts must not be presented as medical or veterinary diagnosis. Seek qualified professional review for health-related decisions.

Project audit and licensing notes: https://github.com/MR-CODESPIKE/rurallens-training-pipeline/blob/main/docs/phase1-final-boundary-report.md

