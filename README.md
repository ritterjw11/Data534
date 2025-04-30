# Predicting College Basketball Revenue Using Team Performance

This project uses machine learning to predict NCAA Division I men's basketball program revenue based on season-level team performance metrics and structural characteristics.

The goal is to determine whether on-court success (e.g., win percentage, tournament results) or institutional factors (like conference affiliation) are stronger predictors of annual revenue.


---

## Tools & Environment

- Python
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`

---

## Model Summary
Models used: Linear Regression, Random Forest, XGBoost

Target variable: Log-transformed revenue

Best model: Linear Regression (R² ≈ 0.87)

Top feature: Conference affiliation

## Code Origin and Updates
This notebook was developed by the author for a graduate level course

Updates made:
Manual name alignment between EADA and performance datasets

Log transformation of skewed revenue data

One-hot encoding of categorical variables (e.g., conferences)

Model evaluation with R² and RMSE

Final model testing and visualization

Feature importance and visualizations 
