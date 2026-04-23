# 📊 E-Commerce Sales Analysis & Machine Learning Project

## 🚀 Project Overview
This project focuses on analyzing an e-commerce dataset to extract meaningful business insights and build machine learning models to predict profitability and identify loss-making transactions.

The goal is to move beyond sales analysis and focus on **profit-driven decision making**.



## 📁 Dataset Information
The dataset includes:
- Order details (Order ID, Dates, Ship Mode)
- Customer information (Segment, Region, City)
- Product details (Category, Sub-Category)
- Financial metrics (Sales, Profit, Discount)



## 🧹 Data Preprocessing
- Handled missing values
- Converted date columns into datetime format
- Created new time-based features
- Replaced infinite values
- Engineered financial features



## ⚙️ Feature Engineering
Key features created:
- Shipping Time
- Profit Margin
- Discount Amount
- Price per Unit
- Sales to Profit Ratio



## 📊 Exploratory Data Analysis (EDA)
Key insights:
- High sales do NOT always mean high profit
- Some categories consistently generate losses
- Discounts strongly impact profitability
- Outliers exist in both sales and profit distributions


## 🤖 Machine Learning Models

### 1. Regression Model
- Predicts **Profit value**
- Captures relationships between sales, discount, and profit

### 2. Classification Model
- Predicts whether a transaction is:
  - Profit (0)
  - Loss (1)



## 📈 Key Results
- Discount is the most influential factor in losses
- Certain product categories are consistently underperforming
- Profit is highly sensitive to pricing strategy



## ⚠️ Limitations
- No cost structure available (true profit not fully accurate)
- Some engineered features may cause leakage
- Model trained only on historical data



## 🚀 Future Improvements
- Use advanced models (XGBoost / LightGBM)
- Add cost and supply chain data
- Deploy model as web app
- Perform hyperparameter tuning



## 🧠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn



## 👨‍💻 Author
Data Science Portfolio Project by Muhammad Bilal# data-science-portfolio
