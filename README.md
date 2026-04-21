# Boston Housing Statistical Analysis

Statistical analysis of the Boston Housing dataset using hypothesis testing,
ANOVA, correlation, and linear regression in Python.

## Overview
This project applies inferential statistics to explore relationships between
housing features in the Boston Housing dataset (506 observations, 14 features).

## Analysis Performed
- **Levene's Test** — tested equality of MEDV variances between homes bordering
  and not bordering the Charles River
- **T-Test** — compared mean MEDV between Charles River groups
- **ANOVA** — examined whether MEDV differs significantly across three age groups
- **Pearson Correlation** — assessed the relationship between NOX and INDUS
- **OLS Linear Regression** — evaluated the impact of DIS on MEDV

## Key Findings
- Homes bordering the Charles River have significantly higher median values
- MEDV differs significantly across building age groups (p = 1.43e-12)
- Strong positive correlation between industrial activity and NOX levels (r = 0.76)
- DIS is a statistically significant but weak predictor of MEDV (R² = 0.062)

## Technologies Used
- Python 3.11
- Pandas, NumPy
- SciPy, Statsmodels
- Seaborn, Matplotlib

## Dataset
[Boston Housing Dataset on Kaggle](https://www.kaggle.com/datasets/altavish/boston-housing-dataset)
