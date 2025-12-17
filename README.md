Nigeria Gas Production & Utilisation Analysis (2025)
 Project Overview
-----------------------------------
This project analyzes Nigeria’s monthly gas production and utilisation performance for 2025 (January – September) using official data from the Nigerian National Petroleum Company Limited (NNPC).

The goal is to evaluate:

Gas production trends

Utilisation efficiency

Gas flaring performance (ESG focus)

Domestic vs export gas allocation

Operational efficiency indicators

The project demonstrates real-world energy analytics, combining data cleaning, exploratory analysis, visualization, and insight generation using Python.

🛢️ Industry Context

Natural gas plays a critical role in Nigeria’s:

Power generation

Industrial growth

Export revenue (LNG)

Environmental sustainability

Gas flaring is a major environmental and economic issue, making utilisation efficiency a key national KPI. Nigeria targets 95%+ gas utilisation — this analysis evaluates progress toward that goal.

📂 Dataset

Source: NNPC Monthly Gas Production Reports

Period Covered: January – September 2025

Unit: MMSCF (Million Standard Cubic Feet)

Data Type: Aggregated national production data

Key Columns

AG Production (Associated Gas)

NAG Production (Non-Associated Gas)

Total Gas Production

Field Use

Domestic Sales

Export Sales

Total Gas Utilised

% Utilised

Total Gas Flared

% Flared

Gas Shrinkage

⚠️ Note: July and September data are marked provisional by NNPC.

🧰 Tools & Technologies

Python

Pandas – data cleaning & analysis

Matplotlib – visualizations

Jupyter Notebook – analysis workflow

CSV / PDF extraction – data preparation

📊 Analysis Performed
1️⃣ Monthly Gas Production Trend

Total gas production trend across months

Comparison of AG vs NAG contribution

Insight:
Production fluctuates across the year, with mid-year peaks driven mainly by increased NAG production.

2️⃣ Gas Utilisation Efficiency Analysis

Mean utilisation rate

Best and worst performing months

Comparison against the 95% national target

Key Findings:

Average utilisation: ~92.5%

Best month: July

Worst month: September

Nigeria did not consistently meet the 95% target.

3️⃣ Gas Flaring Analysis (ESG Focus)

Monthly flaring volume and percentage

Flaring intensity (flared ÷ produced)

Insight:
Although utilisation remains relatively high, gas flaring persists and increases in some months, highlighting continued environmental and economic losses.

4️⃣ Domestic vs Export Gas Sales

Monthly domestic gas supply

Monthly export gas volumes

Domestic-to-export ratio

Insight:
Exports account for a significant share of gas utilisation, reflecting Nigeria’s LNG dependency, while domestic supply fluctuates.

5️⃣ Gas Flow Efficiency (Value Chain View)

Tracks gas movement from:

Production → Field Use → Domestic → Export → Flared

This provides a clear energy value-chain perspective for stakeholders.

6️⃣ Shrinkage Analysis

Computed gas shrinkage percentage as an operational efficiency metric

Insight:
Shrinkage represents processing and transmission losses, which may indicate infrastructure or operational inefficiencies.

7️⃣ Production vs Utilisation Correlation

Scatter analysis of total production vs utilisation %

Insight:
Higher production does not always translate to better utilisation, highlighting capacity and infrastructure constraints.

8️⃣ Cumulative Performance Analysis

Cumulative gas produced

Cumulative gas utilised

Cumulative gas flared

Insight:
Shows year-to-date progress toward annual gas management targets.

📈 Key Insights Summary

Nigeria’s average gas utilisation in 2025 remains below the 95% target

Gas flaring, while reduced compared to production, is still significant

Export demand plays a major role in gas allocation

Operational inefficiencies (shrinkage & flaring) present improvement opportunities

💡 Why This Project Matters

This project demonstrates:

Energy sector domain knowledge

ESG-focused analytics

End-to-end data workflow (PDF → CSV → Analysis → Insights)

Industry-relevant KPIs used by regulators and operators

It is suitable for roles in:

Energy & Financial Analytics

Data Analysis / Data Science

ESG & Sustainability Analytics

Oil & Gas Strategy & Reporting

🚀 Next Improvements

Add 2024 vs 2025 year-on-year comparison


Add forecasting (ARIMA / regression)

Expand analysis to crude oil (upstream)
