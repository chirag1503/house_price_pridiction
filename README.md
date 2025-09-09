# house_price_pridiction
“Machine Learning project to predict house prices using regression models (Linear, Random Forest, XGBoost, etc.)"

# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts housing prices based on various features such as square footage, number of rooms, neighborhood, etc.  
It uses multiple machine learning models and compares their performance.

## 📊 Dataset
- **Source:** [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- **Train Data:** 1460 rows, 81 columns (includes target `SalePrice`)
- **Test Data:** 1459 rows, 80 columns (predict `SalePrice`)

## ⚙️ Workflow
1. Data Exploration (EDA)
2. Data Preprocessing (missing values, encoding, scaling)
3. Model Building
   - Linear Regression
   - Decision Tree
   - Random Forest
   - Gradient Boosting
   - XGBoost
4. Model Evaluation (RMSE & R² comparison)
5. Hyperparameter Tuning (Random Forest example)
6. Feature Importance

## 📈 Results
| Model              | RMSE           | R²    |
|--------------------|----------------|-------|
| Linear Regression  | 49048.340187   | 0.686358 |
| Decision Tree      | 43069.911296   | 0.758157 |
| Random Forest      | 28996.040769   | 0.890387 |
| Gradient Boosting  | 28632.344343   | 0.893119 |
| XGBoost            | 26278.566780   | 0.909970 |


## 🛠️ Tech Stack
- Python, Pandas, Numpy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost


