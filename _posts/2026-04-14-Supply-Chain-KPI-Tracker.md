---
layout: post
title: Supply Chain KPI Tracker
subtitle: Analyzing 2 years of operational data across Saudi Arabia and the Middle East
cover-img: 
thumbnail-img: "https://github.com/user-attachments/assets/991e2693-32aa-4747-a4e0-9c6b5cee579a"
share-img: 
tags: [Supply-Chain, Analytics, Python, PowerBI, SQL]
author: Heba Elgamal
---

![Supply Chain Dashboard](https://github.com/user-attachments/assets/c5185094-896c-45df-b09e-ce147ce722e4)

### Project Overview
An end-to-end supply chain analytics solution analyzing 2 years of operational data (Jan 2023 - Dec 2024). The project tracks performance across **15 suppliers**, **6 warehouses**, and **15 major customers** within Saudi Arabia and the wider Middle East region.

### Key Performance Indicators (KPIs)
* **Delivery & Fulfillment:** On-Time Delivery (OTD), Order Fill Rate, Perfect Order Rate.
* **Inventory & Warehouse:** Inventory Turnover, Warehouse Utilization, Stockout Rate.
* **Quality & Cost:** Supplier Defect Rate, Return Rate, Freight Cost per Unit.
* **Customer Experience:** Customer Satisfaction Score (CSAT).

### Tools & Technologies
* **Python:** `Pandas` for cleaning, `Matplotlib` & `Seaborn` for trend analysis.
* **SQL:** `SQLite` for structured data querying and KPI calculation.
* **Power BI:** Interactive dashboard for real-time monitoring.
* **Excel:** Automated report generation for stakeholders.

### Key Findings & Insights

| Metric | Current Value | Target / Benchmark | Status |
| :--- | :--- | :--- | :--- |
| **On-Time Delivery** | 61% | > 90% | 🔴 Critical |
| **Perfect Order Rate** | 0.6% | > 95% | 🔴 Critical |
| **Return Rate** | 8.2% | < 3% | ⚠️ High |
| **Customer Satisfaction** | 2.86 / 5 | > 4.5 | ⚠️ Low |
| **Warehouse Utilization** | 70.8% | 85% | 🟢 Optimizable |

* **Delivery Bottlenecks:** 422 delayed orders were primarily driven by supplier lead time variability and customs delays.
* **Quality Gaps:** The **2.34% Supplier Defect Rate** directly correlates with the high return rate and low satisfaction scores.
* **Cost Optimization:** Freight cost per unit ($17.76) indicates potential savings through route optimization and shipping consolidation.

---

### Project Structure
```text
Supply-Chain-Analytics/
    ├── data/                 # 10 interconnected CSV files (8,000+ records)
    ├── charts/               # Generated Python visualizations
    ├── Supply_Chain_KPI_Analysis.ipynb   # Full Python analysis
    ├── Supply_Chain_KPI_Report.xlsx       # Excel summary report
    └── Supply_Chain_KPI_Dashboard.pbix    # Power BI interactive dashboard
```
### Dataset Description
The analysis is based on a realistic **Middle Eastern supply chain dataset**, meticulously structured to reflect regional logistics challenges:

* **8,000+ Transactions:** A comprehensive dataset covering the entire lifecycle of **procurement**, **warehousing**, and **distribution**.
* **Multi-entity Tracking:** Detailed data flow mapping the interactions between **15 global suppliers** and **6 regional warehouses**.
* **Strategic Timeframe:** Continuous historical data spanning from **January 2023 to December 2024**, allowing for deep trend analysis and seasonality detection.

---

### Conclusion & Recommendations
> Based on the data findings, the primary focus for the next phase should be **Supplier Relationship Management (SRM)** and **Logistics Optimization** to improve the 61% On-Time Delivery rate and enhance the overall customer experience in the Saudi market.
