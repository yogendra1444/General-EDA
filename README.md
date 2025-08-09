# 📊 Global Superstore Sales Analysis

## 📌 Project Overview
This project analyzes the **Global Superstore** dataset (2011–2014) to identify sales trends, top-performing regions & categories, and the impact of discounts on profit.  
It also includes a predictive model to estimate sales based on key business factors.

---

## 🎯 Objectives
- Clean and preprocess the dataset for accurate analysis.
- Perform **Exploratory Data Analysis (EDA)** to identify trends and insights.
- Build a **predictive model** to forecast sales.
- Provide **business recommendations** based on findings.

---

## 📂 Dataset
- **Name:** Global Superstore
- **Period:** 2011–2014
- **Key Columns:**  
  `Order Date`, `Ship Date`, `Region`, `Category`, `Sub-Category`, `Sales`, `Quantity`, `Discount`, `Profit`

---

## 🛠️ Tools & Libraries
- **Language:** Python 3.x
- **Libraries:**
  - `pandas` — Data manipulation
  - `numpy` — Numerical operations
  - `matplotlib`, `seaborn` — Data visualization
  - `scikit-learn` — Machine learning
  - `joblib` — Model saving

---

## 🔍 Project Workflow
1. **Data Cleaning**
   - Removed duplicates
   - Handled missing values
   - Converted dates to proper format
   - Treated outliers

2. **Feature Engineering**
   - Extracted `Year`, `Month`, `Day of Week`
   - Calculated `Ship_Days`, `Unit_Price`, `Profit_Margin`

3. **EDA & Visualization**
   - Monthly sales trend
   - Sales by Region / Category / Sub-Category
   - Top 10 products by sales
   - Profit vs Discount scatter plot
   - Correlation heatmap
   - Profit distribution by sub-category

4. **Modeling**
   - Target: Sales prediction
   - Algorithm: RandomForestRegressor
   - Metrics: R² Score, RMSE

5. **Insights**
   - West region had the highest sales
   - Technology category led sales, but Furniture had variable profit
   - Discounts above 20% negatively impacted profit


