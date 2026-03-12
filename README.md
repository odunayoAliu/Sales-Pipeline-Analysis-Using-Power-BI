# Sales-Pipeline-Analysis-Using-Power-BI
# Global B2B Sales Pipeline Analytics Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811)
![DAX](https://img.shields.io/badge/Language-DAX-blue)
![Domain](https://img.shields.io/badge/Domain-Sales%20Analytics-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## Project Overview

This project analyzes a **global B2B SaaS sales pipeline** to uncover insights about deal performance, sales engagement, pipeline health, and forecasting reliability.

The dashboard was developed as part of the **FP20 Analytics Data Challenge**, which focuses on building interactive analytics solutions for real-world enterprise sales environments.

The goal was to design a **decision-support dashboard for sales leadership** that helps monitor pipeline performance and identify risks in the deal lifecycle.

---

## Interactive Dashboard

Click the preview below to explore the **live interactive Power BI report**.

[![Sales Pipeline Dashboard](dashboard-preview.png)](https://app.powerbi.com/reportEmbed?reportId=da7b206f-d43d-4214-846c-b7e96dd8db75)

---

## Dashboard Pages

### 1️⃣ Executive Pipeline Snapshot
Provides a high-level overview of sales performance.

Key insights:
- Total pipeline value
- Weighted pipeline
- Closed revenue
- Win rate
- Forecast accuracy
- Regional pipeline distribution

---

### 2️⃣ Pipeline Health & Engagement
Analyzes deal progression and sales activity impact.

Key insights:
- Stage bottlenecks
- Engagement vs win rate relationship
- High-risk deals with low activity
- Sales rep pipeline health

---

### 3️⃣ Performance & Strategic Insights
Focuses on long-term performance drivers.

Key insights:
- Forecast reliability
- Product performance
- SMB vs Enterprise deal dynamics
- Sales rep performance comparison

---

## Data Model

The dataset was modeled using a **star schema** to enable scalable analytics.

Main tables:

- **FactDeals** – deal-level revenue and pipeline metrics
- **FactActivities** – customer engagement and sales activities
- **DimDeal** – unique deal dimension
- **DimCompany** – company and industry attributes
- **DimSalesRep** – sales representative details
- **DimDate** – time intelligence support

This structure enables cross-analysis of **sales performance and engagement activities**.

---

## Key Business Questions Answered

1. How does pipeline value change over time?
2. Which industries and regions generate the most revenue?
3. Where do deals slow down in the sales process?
4. How does engagement impact deal success?
5. Which sales representatives maintain the healthiest pipelines?
6. Which deals are at risk due to inactivity?
7. What seasonal patterns exist in deal closures?
8. How do SMB and Enterprise sales cycles differ?
9. How reliable is pipeline forecasting?
10. Which products drive the highest win rates?

---

## Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**
- **Data Modeling**
- **ZoomCharts Custom Visuals**

---

## Key Features

- Interactive drill-down visualizations
- Dynamic KPI indicators
- Engagement impact analysis
- Pipeline risk detection
- Forecast vs actual comparison

---

## Repository Contents
