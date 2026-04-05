# Solar Investment Analysis: ROI, Cash Flow & Performance Optimization

## 📊 Project Overview
This project provides a comprehensive financial performance analysis of a solar energy asset.  
The study focuses on profitability, cash flow, and Return on Investment (ROI), while examining the impact of maintenance on overall earnings.

The analysis is based on real financial data and allows understanding of the investment’s long-term viability.

---

## 💼 Business Problem
Solar energy investments involve high upfront costs and long-term financial commitments.  
The project addresses key strategic questions:

- **Breakeven Analysis:** When will the investment pay for itself?  
- **Net Profitability:** What is the actual margin after loan repayments and operational costs?  
- **Equity Impact:** How does the ownership structure affect long-term earnings?  
- **Maintenance ROI:** Does panel cleaning increase revenue in a measurable way?

---

## 📂 Data & Preprocessing
The analysis uses multiple data sources:

- **Internal Records:** Monthly invoices, revenue logs, and payment schedules.  
- **External Data:** Solar radiation metrics to validate system efficiency (not directly affecting actual income).

**Preprocessing Steps:**  
- Data cleaning: automated outlier detection and duplicate removal  
- Temporal alignment: synchronizing invoice cycles with production months to ensure data integrity

---

## 🛠 Methodology
The project follows a professional Data Science pipeline:

1. **ETL:** Data ingestion and cleaning using Python (Pandas)  
2. **Database Management:** SQL-based validation and aggregation  
3. **Financial Modeling:** Calculation of custom KPIs, including Wealth Velocity and Cumulative ROI  
4. **Impact Evaluation:** Comparative analysis before and after maintenance actions

---

## 💡 Key Insights
- **Seasonality:** The asset is profitable throughout most of the year, except during winter (Dec–Feb)  
- **Maintenance Impact:** Panel cleaning (May 2025) increased net profit by ₪1,729 over 7 months  
- **Loan Optimization:** Maintenance actions reduced the effective loan burden by ~0.5 days per month  
- **Breakeven Forecast:** The investment is projected to pay for itself by September 2029

---

## 🚀 Technologies Used
- **Languages:** Python (Pandas, Matplotlib)  
- **Database:** SQL (SQLite)  
- **Environment:** Jupyter Notebook / Google Colab

---

## 🔮 Future Improvements
- **Increase Data Sample:** Expand analysis over more months or additional assets to improve accuracy  
- **Maintenance Evaluation:** Explore additional maintenance actions and their impact on profitability
