# 📊 Marketing Campaign & Sales Performance Analysis
 
## 📝 Project Overview
This project was developed as a **Junior Data Analyst** assignment to measure the effectiveness of marketing campaigns and identify top-performing products. By analyzing a comprehensive dataset of customer demographics, transactions, and campaign responses, this project provides actionable business insights to optimize future marketing spend.

## 🎯 Objectives
* **EDA:** Conduct a deep dive into the dataset using Python to understand customer distributions.
* **Statistical Analysis:** Perform hypothesis testing to validate the impact of campaigns on sales.
* **Data Transformation:** Utilize Power Query to pivot/unpivot and clean data for a relational model.
* **Data Modeling:** Build a robust star schema in Power BI.
* **Data Visualization:** Design an interactive "Campaign Performance" dashboard.

---

## 🛠️ Technical Stack
* **Python:** `pandas`, `numpy`, `scipy`, `statsmodels`, `matplotlib`, `seaborn`.
* **Power BI:** Power Query (M), DAX, Data Modeling.

---


## 🚀 Execution Steps

### 1. Exploratory Data Analysis (Python)
* **Variable Identification:** Classified data into continuous and discrete variables.
* **Descriptive Statistics:** Calculated mean, median, min, max, and standard deviation.
* **Visualization:** * Histogram & Boxplots for sales and product amounts.
    * Bar charts for campaign acceptance rates.
* **Data Cleaning:** Addressed anomalies, missing values, and duplicates.

### 2. Statistical Testing
* **Impact Analysis:** Conducted **t-tests** and **ANOVA** to compare average sales amounts across different campaign groups.
* **Categorical Testing:** Applied **Chi-Square** tests to find dependencies between campaign acceptance and geography.
* **Correlation:** Evaluated the relationship between demographic variables and purchasing behavior.
* **Significance:** Interpreted p-values to filter out statistically insignificant factors.

### 3. Transformation & ETL (Power Query)
* **Unpivoting:** Restructured "Campaigns," "Products," and "Platforms" into attribute/value pairs for dynamic filtering.
* **Data Cleaning:** Standardized column names and data types.
* **Relational Prep:** Established a clear link via `Customer ID` to connect transactions to demographics.

### 4. Data Modeling (Power BI)
* **Star Schema:** Defined 1:N relationships between the central customer table and pivoted fact tables.
* **DAX Measures:** Developed custom measures for:
    * Total Sales per campaign/product.
    * Customer conversion counts.
    * Platform-specific revenue distribution.

### 5. Interactive Dashboard
The final "Campaign Performance" dashboard includes:
* **Campaign Reach:** Number of customers per campaign.
* **Revenue Analysis:** Revenue breakdown by product and campaign.
* **Platform Distribution:** Sales split between Web, Catalog, and Store.
* **Dynamic UX:** Slicers for deep-dive analysis into specific demographics or timeframes.

---

## 📅 Project Timeline
* **Duration:** 5 Working Days (April 6 — April 10, 2026).
* **Status:** Completed.

---

## 👤 Author
**[Abdelali Ouhsine]**
*Junior Data Analyst*
