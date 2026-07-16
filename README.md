# Income Classification — Supervised ML on the Adult Dataset

A supervised machine learning project predicting whether an individual earns over $50K/year from census features, using the classic UCI Adult dataset. Built for the Machine Learning module at Keele University.

## Overview
An end-to-end classification workflow: exploratory analysis, preprocessing of mixed categorical/numerical data, model training, and evaluation with a focus on comparing algorithms and interpreting results.

## What's inside
- `income_classification.ipynb` — the full analysis notebook (run this)
- `income_classification.html` — rendered version (open in a browser, no setup needed)
- `adult.data` / `adult.test` — training and test sets
- `adult.names` — feature descriptions

## Method
1. **EDA** — distributions, class imbalance, categorical cardinality.
2. **Preprocessing** — encoding categorical variables, scaling, handling missing values.
3. **Modelling** — trained and compared classification models.
4. **Evaluation** — accuracy, precision/recall, and confusion-matrix analysis.

## Tech stack
Python · pandas · NumPy · scikit-learn · matplotlib

## How to run
```bash
pip install pandas numpy scikit-learn matplotlib jupyter
jupyter notebook income_classification.ipynb
```

---
*Author: Varun Suresh · BSc Data Science & Human Biology, Keele University*
