# E-Commerce Customer Analytics: RFM Segmentation & CLV Prediction

A customer analytics project that segments e-commerce customers using RFM (Recency, Frequency, Monetary) analysis and predicts Customer Lifetime Value (CLV). Built to simulate the kind of data-driven decision support that growth and marketing teams rely on.

**Dashboard:** [Tableau Public](https://public.tableau.com/views/E-Commerce_RFM_CLV_Analysis/Dashboard1)

---

## Motivation

Raw transaction data alone doesn't tell a business who its most valuable customers are or who is at risk of churning. This project addresses that gap by building a full customer intelligence pipeline — from data preprocessing to actionable segmentation to an interactive dashboard that non-technical stakeholders can use.

---

## What Was Built

### 1. Data Preprocessing & Exploration
- Cleaned and standardized raw transaction records
- Handled missing values, outliers, and inconsistent date formats
- Conducted exploratory data analysis to identify purchase patterns and seasonal trends

### 2. RFM Customer Segmentation
Segmented customers into behavioral groups based on:
- **Recency** — how recently did they purchase?
- **Frequency** — how often do they buy?
- **Monetary** — how much do they spend?

Resulting segments: VIP Customers, Loyal Customers, At-Risk Customers, and Dormant Customers — each with distinct recommended actions.

### 3. CLV Prediction
Built a predictive model to estimate future customer value, enabling the business to prioritize retention efforts and marketing spend on high-value segments.

### 4. Tableau Dashboard
Designed an interactive dashboard for business stakeholders covering:
- Customer segment distribution
- Geographic sales concentration
- Top product categories by revenue
- Seasonal sales trends

**Technologies:** Python (Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn), Tableau

---

## Business Insights Generated

- Identified the top customer segment (VIP) representing ~15% of customers but driving the majority of revenue
- Mapped geographic clusters where targeted logistics optimization could improve delivery efficiency
- Flagged at-risk customers suitable for re-engagement campaigns
- Revealed peak sales periods to inform inventory and campaign planning

---

## Key Takeaways

- Translated raw transactional data into strategic customer segments that directly support marketing decisions
- Built a CLV model that bridges data science output with business planning
- Practiced communicating findings to a non-technical audience through dashboard design

---

## Project Structure

```
E-CommerceProject/
├── e-commerce.ipynb           # EDA and preprocessing
├── RFM.ipynb                  # RFM segmentation
├── CLV.ipynb                  # CLV prediction model
├── categories.ipynb           # Category analysis
├── data_visualization.ipynb   # Visual exploration
└── README.md
```
