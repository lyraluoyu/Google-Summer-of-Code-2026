# A Machine-Learning Interface for NiMARE

This repository hosts the final work product website for my Google Summer of Code 2026 project with INCF and NiMARE.

## Project overview

This project extends NiMARE with a new machine-learning interface that converts Studyset objects into scikit-learn-compatible datasets. It treats kernel-generated masked activation maps as sparse feature matrices, preserving study and analysis provenance so researchers can trace every row back to its source. The module will support leakage-safe train/test splitting by keeping analyses from the same study together, optional numeric metadata and annotation features, and aligned prediction targets for supervised workflows. It will also provide practical dimensionality-reduction tools, including variance thresholding, truncated SVD, and atlas-based aggregation, with documentation and examples for reproducible neuroimaging prediction pipelines.

The website presents the project motivation, design, implementation, engineering decisions, deliverables, and future directions as a technical case study.
