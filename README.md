# Ovarian Cancer Early Detection Project

# Overview

This project looks at using machine learning for early detection of ovarian cancer. I compared a logistic regression model with a simple neural network, used PCA to see which features (genes) were most important, and did a small scenario analysis to test how the model reacts when important features shift.

# Dataset

- Used the Multi_group_batch.csv dataset (gene expression data).
_ Target column: group (cancer vs non-cancer).

# Models

- Logistic Regression (baseline) → accuracy ~0.89
- Neural Network → accuracy ~0.84 (some overfitting)
- 
# PCA

- PCA showed which genes mattered most (like MTMR2, CLP1, PSEN1). These explained most of the variance in the data.

# Scenario Analysis

- I made 3 scenarios by adjusting some of the top PCA features.
- Accuracy stayed about the same (~0.74) across all scenarios.
- This shows the model wasn’t really sensitive to those changes.

# Files in this repo

notebook.ipynb → all code

scenario_results.csv → scenario predictions

dashboard.twbx → Tableau dashboard (toggle between scenarios)
Python (pandas, numpy, sklearn, tensorflow)

Tableau
