# 🚴 Swiggy Sales Analysis

---

## 📌 Executive Summary

This project analyzes food delivery sales data from Swiggy — one of India’s leading quick commerce platforms — to uncover key insights about order patterns, revenue trends, customer behavior, and product performance.

By applying SQL-driven exploration and analytical techniques, the goal was to identify high-impact business opportunities that can help improve operations, marketing decisions, and customer engagement strategies.

This analysis is relevant for business stakeholders including operations managers, marketing leaders, category managers, and executive decision-makers.

---

## 🏢 Business Problem

Swiggy operates in an ultra-competitive food delivery market where understanding demand trends, customer preferences, and revenue drivers is critical to maintaining growth and profitability.

Key business questions addressed include:

- When are peak order periods during the day and week?
- Which food categories generate the most revenue?
- How do customer segments differ in buying patterns?
- What operational patterns impact revenue?
- How can Swiggy optimize performance during high demand?

Without structured analysis, decisions may rely on intuition rather than data, which can lead to missed opportunities or suboptimal strategies.

---

## 🧪 Methodology

The project followed a structured analytics framework:

### 1️⃣ Data Understanding
- Reviewed dataset attributes such as order times, categories, revenue values, and customer identifiers.
- Assessed completeness and consistency of records.

### 2️⃣ Data Cleaning & Preparation
- Handled missing and inconsistent values.
- Standardized date and time formats.
- Removed duplicates and invalid orders.

### 3️⃣ SQL-Driven Analysis

The analysis utilized key SQL techniques:

- **CTEs (Common Table Expressions)** for building modular queries
- **Joins** to combine related data from multiple tables
- **CASE statements** for conditional segmentations
- Aggregations using `GROUP BY` to calculate revenue and counts
- Filtering with `WHERE` and `HAVING`
- Time-based trend analysis

### 4️⃣ Exploratory & Business Analysis

- Hourly and daily order trend assessment  
- Food category revenue performance  
- Customer behavior patterns  
- Region or outlet performance (if available)

---

## 🛠 Skills Used

### 🔹 Technical Skills
- SQL (CTEs, Joins, CASE statements)
- Data cleaning and transformation
- Time-based trend analysis
- Revenue aggregation and segmentation
- Exploratory data analysis (EDA)
- Insight development for stakeholders

### 🔹 Tools
- SQL
- Jupyter Notebook (for analytics workflow)
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- CSV / structured data handling

---

## 📊 Results & Key Findings

The analysis surfaced several insights:

- Clear **peak ordering times** during lunch and dinner windows.
- High-revenue **food categories** consistently contribute the majority of sales.
- Patterns in customer behavior indicate segments with higher frequency orders.
- Revenue shows **time-based trends** that can inform dynamic pricing or promotions.
- Some categories or times may represent **under-optimized revenue opportunities**.

These results quantify demand patterns and provide clarity on what drives sales most effectively.

---

## 💼 Business Recommendations

Based on findings, the following recommendations can help stakeholders:

### 🎯 Operational Optimization
- Increase delivery fleet availability during peak order times.
- Align restaurant onboarding with high-performing categories to increase supply.

### 📣 Marketing Strategy
- Offer targeted promotions during mid-day low order periods.
- Personalize offers for high-frequency customers to increase retention.

### 📦 Category & Resource Planning
- Expand resources for categories that generate the highest revenue.
- Evaluate underperforming categories for strategy refinement.

### 📈 What Stakeholders Care About

Stakeholders care most about:

- Revenue growth
- Order fulfillment efficiency
- Customer retention and repeat purchase
- Marketing ROI
- Operational scalability

This analysis provides insights aligned with these priorities.

---

## 🚀 Next Steps

To further enhance business value and impact:

- Build an **interactive dashboard** for real-time monitoring (Power BI / Tableau / Streamlit)
- Apply **predictive analytics** to anticipate demand
- Integrate with CRM to deliver **personalized customer campaigns**
- Train business users on how to interpret and act on the insights
- Automate periodic reporting for leadership and operations teams

---

## 📁 Repository Structure

Swiggy-Sales-Analysis/
│
├── Swiggy Sales Analysis.ipynb # Main analytical notebook
├── swiggy_data.csv # Source dataset
├── requirements.txt # Python and SQL dependencies
└── README.md # Project documentation
