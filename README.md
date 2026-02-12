# 📊 Retail Superstore Sales Analysis

## 📌 Project Overview

This project performs comprehensive **Exploratory Data Analysis (EDA)**
on a Retail Superstore dataset containing 9,000+ sales records across
multiple regions, product categories, and years.

The objective is to uncover meaningful business insights related to
revenue growth, profitability, discount impact, and regional
performance.

------------------------------------------------------------------------

## 🎯 Business Objectives

-   Analyze overall sales and profit trends\
-   Identify high-performing and underperforming categories\
-   Detect loss-making sub-categories\
-   Evaluate the impact of discount on profit\
-   Perform regional and state-level analysis\
-   Generate actionable business recommendations

------------------------------------------------------------------------

## 🛠 Tools & Technologies Used

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn\
-   Jupyter Notebook

------------------------------------------------------------------------

## 📂 Dataset Information

-   Records: 9,000+\
-   Columns: 21\
-   Multi-year transactional retail data

### Key Features:

-   Order Date\
-   Region\
-   State\
-   Category\
-   Sub-Category\
-   Sales\
-   Quantity\
-   Discount\
-   Profit

------------------------------------------------------------------------

## 🧹 Data Cleaning & Preparation

-   Converted Order Date to datetime format\
-   Extracted Year and Month features\
-   Checked and handled missing values\
-   Removed duplicate records\
-   Created new feature: **Profit Margin %**

### Profit Margin Formula:

    Profit_Margin = (Profit / Sales) * 100

------------------------------------------------------------------------

## 📊 Exploratory Data Analysis

### 1️⃣ Overall Sales Performance

-   Revenue shows steady year-over-year growth\
-   Profit growth is slower compared to revenue

**Insight:** Increasing revenue does not always mean increasing
profitability.

------------------------------------------------------------------------

### 2️⃣ Category Analysis

-   Technology generates highest revenue and profit\
-   Office Supplies shows stable performance\
-   Furniture category has lower margins

------------------------------------------------------------------------

### 3️⃣ Sub-Category Analysis

-   Tables and Bookcases show consistent negative profit\
-   High discounting impacts margin significantly

------------------------------------------------------------------------

### 4️⃣ Discount Impact Analysis

-   Strong negative correlation between Discount and Profit\
-   High discounts (\>20--30%) frequently lead to losses

**Recommendation:** Implement margin-based discount strategy.

------------------------------------------------------------------------

### 5️⃣ Regional Analysis

-   West region contributes highest revenue\
-   Some regions show high sales but lower profitability

------------------------------------------------------------------------

### 6️⃣ Customer Analysis

-   Top 10 customers contribute significant revenue\
-   Opportunity for loyalty and retention programs

------------------------------------------------------------------------

## 📈 Key Insights Summary

-   Revenue is growing but profitability growth is slower\
-   Excessive discounting reduces profit margins\
-   Technology is the most profitable category\
-   Furniture sub-categories contribute to losses\
-   Regional optimization required

------------------------------------------------------------------------

## 💡 Business Recommendations

1.  Reduce excessive discounting\
2.  Re-price or review loss-making sub-categories\
3.  Focus marketing on high-margin regions\
4.  Introduce customer loyalty programs\
5.  Optimize logistics and operational costs

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Build interactive dashboard using Streamlit\
-   Perform Sales Forecasting\
-   Implement RFM Customer Segmentation\
-   Integrate SQL for backend querying

------------------------------------------------------------------------

## 👤 Author

**Vikash Bhandari**\
Aspiring Data Analyst\
Python \| SQL \| Power BI

GitHub: https://github.com/vikash-2k25\
LinkedIn: https://linkedin.com/in/vikash-bhandari
