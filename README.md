# Solar Investment Analysis: ROI, Cash Flow & Performance Optimization

## 📊 Project Overview
This project provides an end-to-end financial performance analysis of a solar energy asset.  
The study focuses on profitability, cash flow, and Return on Investment (ROI), while evaluating the impact of operational maintenance on overall earnings.

The analysis integrates real-world financial records with external meteorological data to validate system efficiency against expected solar radiation.

---

## 💼 Business Problem
Solar energy investments involve high upfront costs and long-term financial commitments. This project addresses key strategic questions:

- **Breakeven Analysis:** When will the investment become self-sustaining?  
- **Net Profitability:** What is the actual margin after loan repayments and operational costs?  
- **Equity Impact:** How does the ownership structure affect long-term earnings?  
- **Maintenance ROI:** Does panel cleaning provide a statistically significant revenue lift?

---

## 📂 Data Description & Preprocessing
The analysis is built on multi-source datasets:

**Internal Records:** Monthly invoices, revenue logs, and payment schedules.  
**External Data:** Solar radiation metrics from the national meteorological service.

**Preprocessing Steps:**
- Data Sanitization: Automated outlier detection and duplicate removal.  
- Temporal Alignment: Synchronizing invoice cycles with production months to ensure data integrity.

---

## 🛠 Methodology
The project follows a professional data science pipeline:

1. **ETL Process:** Data ingestion and cleaning using Python (Pandas)  
2. **Database Management:** SQL-based validation and aggregation for structured querying  
3. **Financial Modeling:** Calculation of custom KPIs, including Wealth Velocity and Cumulative ROI  
4. **Impact Evaluation:** Comparative analysis of pre-and-post maintenance performance

---

## 💡 Key Insights
- **Seasonality:** The asset remains profitable year-round, except for the winter trough (Dec–Feb)  
- **Efficiency Gap:** Identified a performance lag in March relative to solar radiation peaks  
- **Maintenance Lift:** Panel cleaning (May 2025) generated a net profit increase of ₪1,729 over 7 months  
- **Loan Optimization:** Maintenance actions reduced the effective loan burden by ~0.5 days per month  
- **Breakeven Forecast:** The investment is projected to reach full ROI by September 2029

---

## 🚀 Technologies Used
- **Languages:** Python (Pandas, Matplotlib)  
- **Database:** SQL (SQLite)  
- **Environment:** Jupyter Notebook / Google Colab

---

## 🔮 Future Improvements
- **Predictive Modeling:** Implementing Machine Learning to forecast energy production based on historical weather patterns  
- **Real-time Integration:** Incorporating live weather APIs for dynamic ROI adjustments  
- **Portfolio Scaling:** Extending the logic to analyze a diversified portfolio of multiple solar assets
