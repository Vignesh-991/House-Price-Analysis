# House-Price-Analysis
House price prediction using Linear Regression with EDA and multicollinearity analysis

## 📌 Objective
The objective of this project is to analyze housing data and build a regression model to predict house prices based on socio-economic and structural features.

## 📊 Dataset
Boston Housing Dataset containing features such as:
- Crime rate (CRIM)
- Number of rooms (RM)
- Pollution level (NX)
- Property tax rate (TAX)
- Percentage of lower status population (LSTAT)
- Median house value (MEDV)

## 🔎 Key Insights
- Number of rooms (RM) shows strong positive impact on house price.
- Pollution (NX) and lower status population percentage (LSTAT) negatively impact price.
- RAD and TAX showed high correlation (multicollinearity).
- After removing one correlated feature, R² decreased from 0.65 to 0.61, so both were retained.

## Model Performance
- R² Score: 0.65
- Evaluation Metric: MAPE

## Project Structure
- Data Loading
- Exploratory Data Analysis
- Correlation Analysis
- Linear Regression Modeling
- Model Evaluation
