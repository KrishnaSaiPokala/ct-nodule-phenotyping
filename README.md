# Pulmonary Nodule Phenotyping from CT Scans

![Status](https://img.shields.io/badge/status-portfolio%20project-blue) ![Python](https://img.shields.io/badge/python-3.x-informational) ![CT Imaging](https://img.shields.io/badge/CT%20Imaging-relevant-lightgrey) ![Phenotyping](https://img.shields.io/badge/Phenotyping-relevant-lightgrey) ![Medical Imaging](https://img.shields.io/badge/Medical%20Imaging-relevant-lightgrey)

Leakage-aware imaging workflow with annotation QC and phenotype-focused analysis.

## Why this project matters
This project shows dataset curation, label standardization, leakage prevention and subgroup-based result review.

## Project purpose
This repository documents a graduate portfolio project completed in healthcare and biomedical analytics. The goal was to build a workflow that is clear, reviewable and grounded in sound data handling rather than only optimizing for a headline model score.

## Project highlights
- Defined inclusion criteria for nodule-level analysis
- Organized scan and annotation data into a usable analysis set
- Added QC checks for annotation completeness and outlier measurements
- Reviewed performance by nodule size and annotation disagreement

## Dataset
- **Dataset:** LIDC-IDRI / TCIA
- **Task:** Pulmonary nodule phenotyping from CT scans and radiologist annotations

## Workflow
1. Load scan and annotation data
2. Define inclusion criteria
3. Build a nodule-level analysis set
4. Apply QC checks and leakage-aware splitting
5. Train baseline models
6. Review edge cases and disagreement patterns

## Methods and tools
- Python
- Pandas
- NumPy
- Matplotlib
- Baseline classification
- Leakage-aware splitting
- Annotation completeness checks
- Outlier review
- Error review by subgroup

## Results
This project helped convert scan and annotation data into a cleaner nodule-level analysis setup. Review by nodule size and annotation disagreement showed that data quality and label uncertainty were important factors in downstream model behavior.

Planned additions to this repository:
- main performance summary
- notes on annotation completeness
- error review by nodule size
- examples of edge cases or disagreement patterns

## Repository structure
- `notebooks/` project walkthrough and exploratory work
- `src/` preprocessing, training and evaluation scripts
- `outputs/figures/` saved charts, plots or confusion matrices
- `outputs/metrics/` summary text or metric tables
- `docs/` short project notes or exported summaries
- `assets/` images used in the README if needed

## How to run
```bash
pip install -r requirements.txt
python src/preprocess.py
python src/train.py
python src/evaluate.py
```

## Notes
- This repository documents a graduate portfolio project and is intended to present the workflow clearly for review
- Raw imaging files are not included in this repository
- Additional model development and validation would be useful future work
