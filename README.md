# Kaggle Competition: House Prices - Advanced Regression Techniques

This repository is part of the Kaggle competition ["House Prices - Advanced Regression Techniques"](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). Here, we employ sophisticated regression techniques to predict house prices with high accuracy, achieving a Public Leaderboard Score of 0.12076.

## Overview

This project encompasses a variety of machine learning techniques aimed at forecasting house prices. From rigorous data preparation to advanced modeling, we focus on extracting the most predictive features and deploying robust regression models.

## Repository Contents

- **Data Cleaning**: Imputation of missing values and initial data exploration.
- **Feature Engineering**:
  - **Simplification**: Reducing complexity in existing features to enhance model interpretability.
  - **Combination**: Merging multiple features to generate powerful predictors.
  - **Polynomial Features**: Expanding the top 10 features into polynomial space for capturing non-linear effects.
  - **Boolean Features**: Introducing binary variables to encapsulate critical thresholds.
- **Data Transformation**:
  - **Skewness Adjustment**: Applying transformations to normalize data distribution, thus improving model accuracy.
- **Model Development**:
  - **Cross-Validation**: Utilizing cross-validation techniques to fine-tune the Lasso and XGBRegressor models, ensuring robustness and generalization.
  - **Residual Analysis**: Analyzing residuals to better understand model performance and guide the ensemble strategy.
- **Ensemble Methods**: Combining predictions from various models to improve accuracy and stability of final predictions.

## Technologies Used

- Python
- Scikit-Learn
- XGBoost
- Pandas, NumPy

## Getting Started

To replicate the findings and experiment with the models:
1. Clone this repository.
2. Download the dataset from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).
3. Install required Python packages: `pip install -r requirements.txt`.
4. Run the Jupyter notebooks provided in the repository.

## License

This project is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for more details.
