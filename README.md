# Fanfiction Success Analysis

## Introduction
This repository contains the code and results of an analysis conducted to explore the relationship between certain variables and fanfiction success. The analysis aimed to investigate whether low levels of masculinity in male characters positively affect fanfiction success when controlling for publication year and lexical richness.

## Analysis Summary
- **Hypothesis**: The hypothesis posited a positive relationship between low masculinity levels in male characters and fanfiction success when controlling for publication year and lexical richness.
- **Methodology**: 
  - Multiple Linear Regression was performed with "kudos" as the dependent variable and "masculine_power_score", "published_year", and "lexical_richness" as independent variables.
  - Residual Analysis included normality and homoscedasticity tests on the residuals.
  - Model Evaluation involved adjusted R-squared, F-test, and t-tests for individual coefficients.
  - Multicollinearity Check was conducted using Variance Inflation Factor (VIF).
- **Results**:
  - The regression model had an adjusted R-squared of 0.162, indicating limited explanatory power.
  - Only time of publishment showed statistically significant effects on fanfiction success.
  - Residual analysis revealed departures from normality for "published_year" and "lexical_richness", while "masculine_power_score" residuals appeared normally distributed.
  - VIF values indicated no significant multicollinearity issues.
- **Conclusion**: 
  - The hypothesis was not fully supported by the analysis.
  - Further investigation is needed to better understand the factors influencing fanfiction success.
- **Reflection**:
  - Limitations include lengthy code execution and potential data quality issues.
  - Suggestions for future research include exploring alternative variables or methodologies.

## Files
- "AD_Assignment_2.ipynb": Jupyter Notebook containing the analysis code.
- "BTS_short_100.csv": Dataset used for the analysis.
