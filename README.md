# RuralLens model checkpoints

Three separate experimental model bundles from the RuralLens 2026-10-22 snapshot. Each folder contains one PyTorch checkpoint (`.pt`), its comparison metadata JSON, and a README with limitations and licensing cautions.

## Folders

- [`animal-doctor/`](animal-doctor/) — Animal/livestock checkpoint (11 classes).
- [`crop-doctor/`](crop-doctor/) — Crop/plant checkpoint (14 classes).
- [`human-skin-doctor/`](human-skin-doctor/) — Human visible-skin checkpoint (16 classes).

## Important limitations and rights

These are experimental visual-triage artifacts, **not validated diagnostic models**. The project's hard acceptance gate (90%+ leakage-safe held-out accuracy for all 20 classes in each domain) was not met and was not fully evaluated; no valid full 20-class held-out accuracy is reported. The per-folder comparison JSON documents covered classes and subset validation information.

The project audit records upstream data sources with non-commercial and/or no-derivatives restrictions, plus per-source attribution requirements. Commercial use or redistribution rights for the checkpoints are not assured by this upload. Review applicable dataset licenses and the project boundary report before reusing these files. This repository does not add a blanket license or grant rights beyond those the uploader holds.

Human-skin results are not a medical diagnosis. Do not use these models as a substitute for qualified medical or veterinary judgment.

Audit and licensing report: https://github.com/MR-CODESPIKE/rurallens-training-pipeline/blob/main/docs/phase1-final-boundary-report.md
