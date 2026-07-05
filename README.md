# PRODIGY_ML_01
"Linear regression model to predict house prices"
# PRODIGY_ML_01 - House Price Prediction using Linear Regression

## Task
Implement a linear regression model to predict house prices based on:
- Square footage (GrLivArea)
- Number of bedrooms (BedroomAbvGr)
- Number of bathrooms (FullBath)

## Dataset
[House Prices - Advanced Regression Techniques (Kaggle)](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

## Approach
1. Loaded and cleaned the dataset (handled missing values)
2. Selected relevant features: square footage, bedrooms, bathrooms
3. Split data into training (80%) and testing (20%) sets
4. Trained a Linear Regression model using scikit-learn
5. Evaluated performance using RMSE and R² score

## Results
- **RMSE:** ~52,975
- **R² Score:** 0.634

The model explains about 63% of the variance in house prices using just these three features.

## Learnings
- Linear regression provides a simple, interpretable baseline for price prediction
- Feature coefficients reveal how each variable impacts price — for example, square footage had a strong positive effect, while adding bedrooms without increasing total space could reduce price (since rooms become smaller)
- Model accuracy could be improved by including more features (location, house condition, year built, etc.)

## Tools Used
- Python
- Pandas
- Scikit-learn
- Google Colab

## Internship
This task was completed as part of the Prodigy Infotech Machine Learning Internship.
