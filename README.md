# RuralLens model checkpoints

This is an earlier combined snapshot of three experimental RuralLens PyTorch checkpoints and their comparison metadata. For a model-specific download and a user guide with a PyTorch loading example, use one of the dedicated repositories below.

## Folders

## Separate model repositories

- [Animal / livestock model](https://github.com/MR-CODESPIKE/rurallens-animal-doctor)
- [Crop / plant model](https://github.com/MR-CODESPIKE/rurallens-crop-doctor)
- [Human visible-skin model](https://github.com/MR-CODESPIKE/rurallens-human-skin-doctor)

## Important limitations and rights

These are experimental visual-triage artifacts, **not validated diagnostic models**. The project's hard acceptance gate (90%+ leakage-safe held-out accuracy for all 20 classes in each domain) was not met and was not fully evaluated; no valid full 20-class held-out accuracy is reported. The per-folder comparison JSON documents covered classes and subset validation information.

The project audit records upstream data sources with non-commercial and/or no-derivatives restrictions, plus per-source attribution requirements. Commercial use or redistribution rights for the checkpoints are not assured by this upload. Review applicable dataset licenses and the project boundary report before reusing these files. This repository does not add a blanket license or grant rights beyond those the uploader holds.

Human-skin results are not a medical diagnosis. Do not use these models as a substitute for qualified medical or veterinary judgment.

Audit and licensing report: https://github.com/MR-CODESPIKE/rurallens-training-pipeline/blob/main/docs/phase1-final-boundary-report.md
