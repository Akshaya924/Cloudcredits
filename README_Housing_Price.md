# Housing Price Prediction 🏡

## 🔍 Objective
To predict house sale prices based on various features such as area, quality, and construction year using machine learning models.

## 🗂️ Dataset
- Source: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- Files Used: train.csv

## 🧪 Steps Followed
1. Data Cleaning:
   - Dropped columns with too many missing values
   - Filled missing numeric values with median and categorical values with mode
   - Removed irrelevant columns (e.g., ID)
2. Data Preprocessing:
   - One-Hot Encoding for categorical variables
3. Model Training:
   - Linear Regression
   - Random Forest Regressor
4. Model Evaluation:
   - Compared R² Score, Mean Absolute Error, and Root Mean Squared Error
5. Feature Importance:
   - Identified top factors influencing house prices

## ✅ Results
- **Best Model:** Random Forest Regressor
- **Performance Metrics:**
  - Higher R² score with lower errors compared to Linear Regression

## 💡 Key Insights
- Important features influencing price:
  - Overall Quality of house (`OverallQual`)
  - Living area size (`GrLivArea`)
  - Garage capacity (`GarageCars`)
  - Basement size (`TotalBsmtSF`)
  - Construction year (`YearBuilt`)
- Quality and living space significantly impact house prices.

## 🎯 Recommendations
- Focus on improving overall material quality to maximize property value.
- Highlight living area and garage capacity in property listings.
- Renovate older properties to align with newer building standards.

## 📊 Tools & Libraries Used
- Python (pandas, numpy, seaborn, matplotlib, scikit-learn)
- Jupyter Notebook
