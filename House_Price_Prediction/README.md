# Data Analytics Project 2: House Price Prediction – Oasis Infobyte
# Level 1

This project uses **linear regression** to predict house prices based on various features such as area, number of bedrooms, location accessibility, and amenities.
-------------------------------

# Dataset

- File used: 'Housing.csv'
- Source: [Kaggle – Housing Prices Dataset](https://www.kaggle.com/code/ashydv/housing-price-prediction-linear-regression)

-------------------------------

# Models Used

- **Linear Regression (OLS via StatsModels)**
- Feature selection with **Recursive Feature Elimination (RFE)**

-------------------------------

# Summary

- Cleaned the dataset and removed outliers
- Explored data patterns through visualizations (EDA)
- Encoded categorical columns using label and one-hot encoding
- Scaled numerical features using MinMaxScaler
- Selected the top 6 most important features using RFE
- Trained a linear regression model using the StatsModels OLS method
- Evaluated the model using R² score and residual analysis
- The final model gave a good fit on both training and test data

-------------------------------

# Key Evaluation Metric

- **R² Score (Test Set):** ~0.64

-------------------------------

# Visualizations

- Heatmap of feature correlation
- Residual distribution and scatter plot
- Actual vs. Predicted price comparison

-------------------------------

This project helped build understanding of linear regression, feature selection techniques, and model diagnostics through statistical evaluation.
