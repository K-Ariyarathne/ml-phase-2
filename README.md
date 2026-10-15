# ML Phase 2 — Baseline Implementation

## Overview

This project implements and evaluates baseline machine learning models for next-day rainfall prediction using the Rain in Australia dataset.

The project compares Random Forest and XGBoost models for two tasks:

- **Classification:** Predicting whether it will rain the following day.
- **Regression:** Predicting the amount of rainfall on the following day.

## Methods

The notebook explores data quality, missing values, feature engineering, chronological data splitting, model training, and evaluation. It compares default models with regularised versions and examines how evaluation choices affect the reported performance.

## Main File

- `Phase2_Technical_Appendix.ipynb` — contains the implementation, experiments, and evaluation.

## Dataset

The experiments use the Rain in Australia weather dataset. Obtain the dataset from its original source and place it in the location expected by the notebook. Check the notebook's data-loading cell for the exact filename and path.

## Requirements

The notebook uses Python and common data science libraries. Check the notebook's import cells to confirm the required packages before running it.

## Reproducibility

The notebook documents the modelling workflow and evaluation. Results may vary depending on package versions and the execution environment.

## Author

D. L. K. D. Ariyarathne