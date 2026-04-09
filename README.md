# 📊 Customer Behavior Analysis

## 📌 Project Overview
This project analyzes customer purchase behavior to identify key drivers of **revenue, customer retention, and product performance**.  
The goal is to transform raw data into **actionable business insights** using **Python, SQL, and Power BI**.

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
