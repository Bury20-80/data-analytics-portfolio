# Data Analytics Portfolio. Bartłomiej Gołek

SQL · Excel · Power Query · Power BI · DAX

---

## 🔴 Marketplace Risk Analytics
[Repo](https://github.com/Bury20-80/marketplace-risk-analytics)

Seller risk scoring system built on the Olist Brazilian e-commerce dataset (99K orders, 3,095 sellers). Identifies which sellers pose operational risk, how much revenue flows through them, and which product categories are most exposed.

- Designed a dbt-style SQL architecture: staging → intermediate → marts
- Built a WATCH tier guard clause to exclude low-sample sellers from risk scoring
- Implemented Spearman correlation in DAX (r = −0.46)
- Developed an interactive Power BI dashboard with key insights

`PostgreSQL` `Power BI` `DAX`

---
## 🟡 Customer Analytics. SQL + Python (Cohort, RFM & Statistical Analysis)
[Repo](https://github.com/Bury20-80/customer-analytics-sql)

End-to-end customer analytics on 100K customers and 200K transactions (2015-2024). SQL builds the core metrics. Python validates the data, creates every chart, and adds statistical analysis that corrected a churn measurement flaw in the original query.
- RFM segmentation using NTILE(5) quintiles mapped to 9 business segments
- Churn threshold corrected from 180 to 558 days after validating purchase-gap distribution in pandas
- Gini coefficient (0.567) and Lorenz curve quantify revenue concentration: top 25% of customers generate 66% of revenue
- New vs Returning revenue crossover identified at mid-2022

`PostgreSQL` `Python` `pandas` `matplotlib` `seaborn` 

---

## 🔵 Multi-Asset Portfolio Simulator
[Repo](https://github.com/Bury20-80/multi-asset-portfolio-simulator)

Interactive portfolio backtesting tool covering May 2023 – April 2026 (BTC, GLD, QQQ, SPY). User sets initial capital and allocation weights. All metrics update automatically without VBA.

- Calendar alignment across assets with different trading schedules via Power Query
- 60-day rolling volatility chart revealing regime changes over time
- Sharpe, Calmar, CAGR, Win Rate calculated dynamically from daily returns

`Excel` `Power Query (M)` `Financial KPI Modeling`

---

## ⚪ Data Job Market Analysis
[Repo](https://github.com/Bury20-80/data-job-market-analysis)

Skill demand and salary analysis across 100K+ real job postings.

- salary per required skill by role
- salary weighted by market likelihood
- US vs Non-US salary premium quantified per role

`Excel` `Power Pivot` `DAX` `Power Query`
