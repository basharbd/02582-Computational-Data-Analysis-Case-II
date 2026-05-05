# CDA Case II — Wearable Biosignal Representation

This folder contains the Jupyter notebook for Case II in 02582 Computational Data Analysis.

## How to run

Place the local data file here:

```text
data/HR_data.csv
```

Then open and run:

```text
case2_analysis_unified_FINAL_READY.ipynb
```

The notebook writes generated figures to `figures/` and numerical tables to `results/`.

## Main analysis structure

The notebook follows the project pipeline:

```text
Data preprocessing → Representation → Evaluation
```

It includes:

- missing-value inspection and handling,
- physiological feature scaling,
- PCA representation,
- unsupervised phase-alignment diagnostic,
- phase-classification diagnostic with subject-aware GroupKFold,
- CCA analysis between physiological features and emotion ratings,
- factor-handling analysis using eta-squared,
- final numerical summary for the report.

## Important note

The raw dataset is not included in this folder. Keep the dataset local and do not redistribute it publicly.
