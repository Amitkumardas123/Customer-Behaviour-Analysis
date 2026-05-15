# 📊 Customer Behavior Analysis
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)

## 📌 Project Overview
This project analyzes customer purchase behavior to identify key drivers of **revenue, customer retention, and product performance**.  
The goal is to transform raw data into **actionable business insights** using **Python, SQL, and Power BI**.

---

## 📊 Dashboard Preview
![image alt](https://github.com/Amitkumardas123/Customer-Behaviour-Analysis/blob/75f374520f414d881a38d1734698ff97692f2809/Dashboard%20Img.png)

---

## 🎯 Business Objective
- Understand customer purchasing patterns  
- Identify high-value and low-engagement customers  
- Analyze product and category performance  
- Evaluate impact of discounts and subscriptions  
- Provide data-driven recommendations to improve business performance  

---

## 🛠️ Tools & Technologies
- **Python (Pandas, NumPy)** → Data cleaning & feature engineering  
- **SQL (MySQL)** → Data analysis & querying  
- **Power BI (DAX)** → Dashboard & KPI tracking  

---

# 🔄 Project Workflow Architecture

```text
Raw Dataset
     ↓
Data Cleaning (Python)
     ↓
Feature Engineering
     ↓
MySQL Database Storage
     ↓
SQL Business Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights & Recommendations
```
---
## 📁 Project File Structure & Workflow

```bash
Customer-Behavior-Analysis/
│
├── data/
│   ├── raw_customer_data.csv
│   │      → Original dataset
│   │
│   └── cleaned_customer_data.csv
│          → Cleaned dataset after preprocessing
│
├── python/
│   ├── data_cleaning.py
│   │      → Handles missing values & formatting
│   │
│   ├── feature_engineering.py
│   │      → Creates age groups, customer segments, rating categories
│   │
│   └── exploratory_analysis.py
│          → Performs EDA and behavioral analysis
│
├── sql/
│   ├── schema.sql
│   │      → Creates MySQL database tables
│   │
│   ├── data_import.sql
│   │      → Imports cleaned dataset into MySQL
│   │
│   └── Customer Behaviour.sql
│          → SQL queries for business insights
│
├── powerbi/
│   ├── customer_behavior_dashboard.pbix
│   │      → Interactive Power BI dashboard
│   │
│   └── dashboard_screenshots/
│          ├── executive_dashboard.png
│          ├── customer_segmentation.png
│          ├── revenue_analysis.png
│          └── product_performance.png
│
├── images/
│   └── workflow_architecture.png
│          → Project workflow diagram
│
├── reports/
│   └── Customer Behaviour(1).pptx
│          → Final business insights & recommendations report
│
├── README.md
│      → Complete project documentation
│
└── requirements.txt
       → Python libraries used in the project
```
---

## 🔄 Project Workflow (Step-by-Step)

### 🧩 Step 1: Data Understanding
Dataset contains ~4K customers with:
- Demographics (age, gender, location)  
- Purchase details (product, category, amount)  
- Behavior metrics (frequency, previous purchases)  
- Ratings and subscription status  

👉 **Impact:** Established a clear understanding of customer behavior variables to guide focused analysis.

---

### 🧹 Step 2: Data Cleaning (Python)
- Handled missing values:
  - `review_rating` filled using **category-wise mean**  
- Removed inconsistencies and formatted columns  
- Ensured data quality for analysis  

👉 **Impact:** Improved data quality and ensured reliable analysis.

---

### ⚙️ Step 3: Feature Engineering
Created new features to improve analysis:
- `age_group` → Young, Adult, Middle Aged, Senior  
- `purchase_frequency_days` → standardized frequency  
- `customer_segment` → based on behavior  
- `rating_category` → grouped rating levels  

👉 **Impact:** Enabled deeper customer segmentation and behavioral insights.

---

### 🗄️ Step 4: Data Storage (SQL)
- Loaded cleaned dataset into **MySQL**  
- Created structured table for analysis  
- Enabled efficient querying  

👉 **Impact:** Structured data for scalable and high-performance analysis.

---

### 🔍 Step 5: SQL Analysis
Performed queries to answer key business questions:
- Revenue by category and demographics  
- Top-performing products within each category  
- High-rated vs low-rated product analysis  
- Discount dependency (~50%)  
- Repeat customers vs subscription behavior  
- Revenue contribution by age group and gender  

👉 **Impact:** Extracted actionable business insights from raw data.

---

### 📊 Step 6: Dashboard Development (Power BI)

**KPI Metrics:**
- Repeat Purchase Rate (~97%)  
- Average Order Value (~$60)  
- Revenue Contribution (%)  

**Visualizations:**
- Category-wise revenue  
- Customer segmentation  
- Rating distribution  
- Demographic analysis (age & gender)  
- Purchase behavior patterns  

👉 **Impact:** Delivered an interactive dashboard for real-time decision-making.

---

### 💡 Step 7: Key Insights
- High repeat purchase rate but low subscription adoption (~70% repeat users not subscribed)  
- Heavy reliance on discounts (~50%), impacting profitability  
- Revenue concentrated in specific segments (Young Male ~18%)  
- Clothing category dominates revenue; Outerwear underperforms  
- Some high-volume products have lower ratings  

👉 **Impact:** Identified critical business gaps and opportunities.

---

### 🚀 Step 8: Business Recommendations
- Improve subscription conversion through loyalty programs  
- Optimize discount strategy to protect margins  
- Target underperforming segments (e.g., female customers)  
- Promote high-rated products for better conversion  
- Improve quality of low-rated products  

👉 **Impact:** Provided actionable strategies to improve growth and retention.

---

## 📈 Final Outcome
- Built an **end-to-end data analysis project**  
- Transformed raw data into **business insights**  
- Created an **interactive dashboard**  
- Delivered **actionable recommendations**  

👉 **Impact:** Demonstrated ability to solve real-world business problems using data.

---

## 🎯 Conclusion
This project showcases the ability to combine **data analysis, SQL querying, and business intelligence tools** to drive **data-driven decision-making** and business growth.

---

⭐ *If you found this project useful, feel free to star the repository!*
