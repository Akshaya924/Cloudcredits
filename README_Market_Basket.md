# Market Basket Analysis 🛒

## 🔍 Objective
To identify patterns in customer purchasing behavior and discover associations between products using the Apriori algorithm.

## 🗂️ Dataset
- Source: [Kaggle - Online Retail II Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
- Data collected from an online retail store based in the UK.

## 🧪 Steps Followed
1. Data Cleaning:
   - Removed missing values
   - Filtered out canceled transactions
   - Focused analysis on United Kingdom customers
2. Data Transformation:
   - Converted transactions into basket format (Invoice × Product matrix)
   - 1 = Item bought, 0 = Item not bought
3. Market Basket Analysis:
   - Applied the Apriori algorithm to find frequent itemsets
   - Generated association rules (based on lift and confidence)

## ✅ Results
- Discovered strong associations between frequently bought products.
- Identified product pairs with high confidence and lift values.
- Example Rule:
  - **Antecedent:** [Product A]
  - **Consequent:** [Product B]
  - **Lift:** 2.5 (meaning customers buying A are 2.5x more likely to buy B)

## 💡 Business Insights
- Customers often purchase related products together.
- Some products act as "driver items" that trigger additional purchases.

## 🎯 Recommendations
- Create combo offers for strongly associated products to increase basket size.
- Place associated products closer together on the website or in stores.
- Offer cross-sell promotions for high-confidence product pairs.

## 📊 Tools & Libraries Used
- Python (pandas, numpy, seaborn, matplotlib)
- Machine Learning: mlxtend (Apriori, Association Rules)
- Jupyter Notebook
