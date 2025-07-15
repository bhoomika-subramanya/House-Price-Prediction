# House-Price-Prediction
Machine learning project with python language

This project aims to predict house prices using multiple machine learning models. We applied various preprocessing and feature engineering techniques to build robust and accurate models. The models were trained and evaluated on a real-world dataset with multiple numerical and categorical variables.

Features

- Data Cleaning and Preprocessing
- Log Transformation for Skewed Features
- Outlier Detection using Isolation Forest
- Feature Scaling using StandardScaler
- Model Training using:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Random Forest Regressor
  - Artificial Neural Network (ANN)
- Model Evaluation using RMSE and R² score
- Visualizations for EDA and model performance

Project Structure
House-Price-Prediction
├── data/
│ └── cleaned_house_data.csv
├── models/
│ └── trained_models.pkl
├── notebooks/
│ └── house_price_prediction.ipynb
├── scripts/
│ ├── train_model.py
│ ├── preprocess.py
│ └── evaluate.py
├── requirements.txt
└── README.md


Dataset

The dataset contains house features like:
- LotArea, OverallQual, YearBuilt, TotalBsmtSF, GrLivArea, etc.
- Categorical variables like Neighborhood, HouseStyle, etc.
- Target variable: `SalePrice`


Model Performance

| Model              | RMSE     | R² Score |
|-------------------|----------|----------|
| Linear Regression | 27,000   | 0.89     |
| Ridge Regression  | 26,500   | 0.90     |
| Lasso Regression  | 27,100   | 0.89     |
| Random Forest     | 23,000   | 0.93     |
| ANN               | 22,500   | 0.94     |




