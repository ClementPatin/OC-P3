# OC-P3
# Analysing Food Data

## Project scenario

The French Public Health Agency has launched a call for projects to make health data more accessible. The agency wants to explore and visualize data so that its agents can exploit it.

The exploratory analysis is conducted using the **Open Food Facts dataset**.

The goal is to brainstorm an application idea based on this data, then conduct exploratory analysis to assess its feasibility.

## Analysis steps

- General description
- App idea : Assist doctors and patients by offering an app that, based on a product label scan, provides a personalized "MyHealthScore" that takes into account the patient's medical conditions.
- Feature selection
- Data cleaning (duplicates, outliers, formatting)
- Missing data imputation
  - create a test dataset to evaluate imputations, by adding artificial missing values
  - for categorical features :
    - create a custom iterative "kNN-based" imputer
    - evaluate with % of errors
  - for numerical features :
    - KNN imputer, Iterative imputer
    - feature selection based on correlation
    - evaluation with RMSE, R2
- Univariate analysis (statistical measures, empirical distributions)
- Bivariate analysis (One-Way ANOVA)
- Multivariate analysis (Principal Component Analysis)
