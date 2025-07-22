# High-Dimensional-Regression-for-Gene-Phenotype-Analysis

# Gene Expression Analysis for Phenotype Prediction

This project analyzes high-dimensional gene expression data from 50 mice to identify genes significantly influencing a specific phenotype. Using machine learning and statistical techniques, the study focuses on model performance and feature selection.

## Objectives
- Identify significant genes impacting phenotype.
- Apply and compare regression models: Ridge, Lasso, and Bayesian Regression.
- Perform dimensionality reduction using correlation-based screening.

## Methods
- **Data:** 2000 gene features × 50 samples + phenotype data.
- **Feature Selection:** Correlation-based screening (Top 200 genes).
- **Models:** Ridge, Lasso, and Bayesian Regression.
- **Best Fit:** Lasso Regression (R² = 0.9576), selected 11 key genes.

## Results
Lasso outperformed other models, reducing features from 2000 to 11 significant genes influencing the phenotype.

## Tools & Libraries
- Python (NumPy, Pandas, Scikit-learn)
- Matplotlib / Seaborn (for visualization)


