Overview
This project was developed as part of a hackathon challenge focused on analyzing high-dimensional genetic data. The objective was to identify genes that significantly impact a given phenotype in a dataset containing gene expression data for 50 mice across 2000 genes.

Problem Statement
A genetic study was conducted where gene expression data for 2000 genes and a phenotype variable were collected for 50 mice. The goal was to determine which genes have a significant effect on the phenotype using high-dimensional regression techniques.

Approach
The project explores multiple statistical and machine learning methods to handle high-dimensional data, including:

Feature Screening: A simple screening method was used to reduce the number of covariates to 200.
Ordinary Least Squares (OLS): Evaluated feasibility and necessity of using an intercept.
Regularized Regression:
Ridge Regression: Applied to manage multicollinearity.
Lasso Regression: Used for feature selection and sparsity.
Bayesian Regression: Investigated the advantages of a Bayesian approach to high-dimensional regression.
Key Findings
Compared Ridge and Lasso regression for feature selection and prediction accuracy.
Discussed the suitability of Bayesian methods in this context.
Identified genes that significantly impact the phenotype.
Technologies Used
Python (NumPy, pandas, scikit-learn, matplotlib, seaborn)
Statistical Modeling (OLS, Ridge, Lasso, Bayesian Regression
