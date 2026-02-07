# used-car-price-analysis

This project analyzes a used car dataset to understand key factors influencing car prices.
The focus is on data preparation, exploratory data analysis, feature engineering, and
a comparison of regression models.

## Feature Importance
A Random Forest model was used to inspect feature importance.
The analysis showed that variables such as model year, gearbox type,
and mileage were among the most influential features.
However, the results also highlight that feature importance reflects
model usage rather than causal relationships.

## Project Overview
- Data cleaning and preparation
- Exploratory data analysis (EDA)
- Feature engineering (car age, log-transformed price)
- One-hot encoding of categorical features
- Train/test split
- Model comparison:
  - Linear Regression
  - Random Forest Regression

## Results
Linear Regression achieved a lower RMSE on the test set than Random Forest.
This indicates that the main relationships in the data (e.g. mileage and age vs. price)
are largely linear and that the dataset size is limited for more complex models.

## Tools & Technologies
- Python
- pandas, NumPy
- seaborn, matplotlib
- scikit-learn
- JupyterLab

## Notes
This project is intended as an analysis and learning project.
The models are not meant for real-world price prediction.

## Data Source
The dataset was obtained from Kaggle (used cars dataset).
