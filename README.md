# House Price Prediction — Linear Regression

## Overview
End-to-end machine learning project predicting house sale prices using the 
Ames Housing dataset from Kaggle. The project demonstrates a complete pipeline 
from exploratory data analysis through model evaluation.

## Results
| Metric | Score |
|--------|-------|
| R²     | 0.90  |
| RMSE   | ~24,600 USD |

## Project Structure
- Exploratory Data Analysis — univariate, bivariate and multivariate visualizations
- Feature Selection — correlation analysis, scatter plots, outlier detection
- Preprocessing — one-hot encoding, log transformation of target, standard scaling
- Modeling — Linear Regression with residual analysis

## Key Findings
- `OverallQual` and `GrLivArea` are the strongest numeric predictors of sale price
- `Neighborhood` is a dominant feature — location alone accounts for dramatic price differences across the dataset
- Log transformation of `SalePrice` corrected right skew and improved model fit
- Residual plot confirmed no curved pattern, making polynomial regression unnecessary

## Dataset
Download `train.csv` from the [Ames Housing Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) on Kaggle.

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
