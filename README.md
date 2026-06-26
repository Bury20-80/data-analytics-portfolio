# Data Analytics Portfolio — Bartłomiej Gołek

SQL · Excel · Power Query · Power BI · DAX

---

## 🔴 Marketplace Risk Analytics
[Repo](https://github.com/Bury20-80/marketplace-risk-analytics)

Seller risk scoring system built on the Olist Brazilian e-commerce dataset (99K orders, 3,095 sellers). Identifies which sellers pose operational risk, how much revenue flows through them, and which product categories are most exposed.

- Designed a dbt-style SQL architecture: staging → intermediate → marts
- Built a WATCH tier guard clause to exclude low-sample sellers from risk scoring
- Implemented Spearman correlation in DAX from scratch (r = −0.46)
- Caught and fixed a timestamp vs date bug that was misclassifying 1,292 deliveries as late

`PostgreSQL` `Power BI` `DAX`

---

## 🟡 Customer Analytics — Cohort & RFM
[Repo](https://github.com/Bury20-80/customer-analytics-sql)

End-to-end customer analytics on 100K customers and 200K transactions (2015–2024). Covers revenue trends, RFM segmentation, churn analysis, and product performance — built on a single reusable SQL view.

- RFM segmentation using NTILE(5) quintiles mapped to 9 business segments
- Churn analysis with 6-month inactivity threshold across cohort years
- IQR-based LTV segmentation: top 25% of customers generate 66% of revenue
- New vs Returning revenue crossover identified at mid-2022

`PostgreSQL` `AI visualizations`

---

## 🔵 Multi-Asset Portfolio Simulator
[Repo](https://github.com/Bury20-80/multi-asset-portfolio-simulator)

Interactive portfolio backtesting tool covering May 2023 – April 2026 (BTC, GLD, QQQ, SPY). User sets initial capital and allocation weights — all metrics update automatically without VBA.

- Calendar alignment across assets with different trading schedules via Power Query
- Correct Max Drawdown using running peak column, not global min vs max
- 60-day rolling volatility chart revealing regime changes over time
- Sharpe, Calmar, CAGR, Win Rate calculated dynamically from daily returns

`Excel` `Power Query (M)` `Financial KPI Modeling`

---

## ⚪ Data Job Market Analysis
[Repo](https://github.com/Bury20-80/data-job-market-analysis)

Skill demand and salary analysis across 100K+ real job postings.

- Skill Efficiency Index: salary per required skill by role
- Skill Value Index: salary weighted by market likelihood
- US vs Non-US salary premium quantified per role

`Excel` `Power Pivot` `DAX` `Power Query`
