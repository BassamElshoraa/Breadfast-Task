# Breadfast Automated Discount Monitoring Dashboard

## Overview

Managing near-expiry inventory requires a balance between reducing waste and protecting profitability. Static reporting often makes it difficult to understand how discount rules affect sales volume, waste reduction, and product movement over time.

This project delivers an **interactive Power BI dashboard** for **Breadfast**, designed to monitor the performance of **automated discounts** applied to products approaching **OOV (Out of Validity)** dates.  
The dashboard focuses on tracking **discount spending**, **discounted sales volume**, **OOV inventory**, **waste after discount**, and **discount ending reasons** to evaluate how effective the automated discount strategy is in reducing inventory waste and driving sales.

[**Access the Live Dashboard here**](https://app.powerbi.com/view?r=eyJrIjoiNTEwNDM0ZmEtMWRhYi00MjE3LThkNzEtMmYwOGNhMTQ2YWNiIiwidCI6IjBkODkwMmEzLTE1OGYtNGM3MC04MTI4LTFlM2JiNGFiMzk3ZCIsImMiOjh9)

![Discount Monitoring Dashboard](https://raw.githubusercontent.com/BassamElshoraa/Breadfast-Task/main/Screenshot%202026-03-22%20231808.png)

---

## Tools & Technologies Used

- **Power BI Desktop**: For building the interactive dashboard
- **DAX (Data Analysis Expressions)**: For KPI calculations and custom analytical measures
- **Power Query**: For data cleaning and transformation
- **Interactive Visuals**: Including KPI cards, line charts, area charts, bar charts, and treemaps
- **Dashboard Navigation Buttons**: For moving between dashboard views

---

## Dashboard Pages Overview

### 1. **Discount Monitoring Dashboard**
**Purpose:** Tracks the direct impact of automated discounts on discounted sales and discount spending.

Includes:
- Total Discount Amount Applied
- Sum of Products Original Price with Discount
- Net Percentage After Discount
- Total Quantity Sold With Automated Discounts per Day
- Top 5 Discounted Products by Discount Applied Amount
- Total Discount Amount Applied per Day
- Discount Ending Reason

![Discount Monitoring Dashboard](https://raw.githubusercontent.com/BassamElshoraa/Breadfast-Task/main/Screenshot%202026-03-22%20231808.png)

---

### 2. **OOV & Waste Monitoring Dashboard**
**Purpose:** Focuses on OOV product movement, waste after discount, and the effectiveness of automated discounts in clearing near-expiry inventory.

Includes:
- Total OOV Products
- Total Quantity Sold With Automated Discounts
- Total Waste After Discount
- Percentage of OOV Products Remaining After Discounts
- Total Daily Automated Discounts
- Total OOV Products Per Day
- Total Quantity Sold With Automated Discounts by Date

![OOV & Waste Monitoring Dashboard](https://raw.githubusercontent.com/BassamElshoraa/Breadfast-Task/main/Screenshot%202026-03-22%20231828.png)

---

## Key Features

- Automated discount performance tracking
- OOV inventory monitoring
- Waste reduction analysis
- Daily discount activity analysis
- Discounted sales volume analysis
- Top discounted product identification
- Discount termination reason analysis
- Interactive navigation across dashboard views

---

## Key Insights

- Total discount amount applied reached **961.55K**
- Discounted products had an original price value of **4.08M**
- Net percentage after discount was **76.46%**
- A total of **104.39K** units were sold with automated discounts
- Total OOV products reached **251.55K**
- Total waste after discounts was **147.16K**
- **59%** of OOV products remained unsold after discounting
- Top 5 discounted products ranged from **15K** to **30K** in applied discounts
- Daily discount spending fluctuated between **80.52K** and **226.32K**
- Daily automated discounts ranged between **2.74K** and **7.56K**
- Daily OOV products ranged from **27.32K** to **33.54K**
- Discount ending reasons were mainly:
  - **Manually Cancelled:** 30.27K
  - **Discounted Batch Exhausted:** 1.20K

---

## Analytical Highlights

- The dashboard shows that automated discounts helped move a meaningful volume of near-expiry inventory, with strong daily sales peaks reaching **30.52K** units.
- Despite the positive sales impact, a large share of OOV products still remained unsold, indicating that current discount rules may not be aggressive enough in some cases.
- The gap between total OOV products and sold discounted units highlights an ongoing waste challenge.
- Discount termination analysis suggests that many discounts were manually cancelled, which may point to operational decisions affecting campaign continuity.
- The dashboard provides a clear foundation for improving discount strategy, inventory planning, and waste reduction initiatives.

---

## About This Project

This Power BI project provides an interactive analysis of Breadfast’s automated discount strategy, focusing on discount spending, OOV inventory, discounted sales, and waste reduction. It helps evaluate how effective automated discounts are in moving near-expiry products while supporting better operational and inventory decisions.

---

## Author

**Bassam Elshoraa**  
[GitHub Profile](https://github.com/BassamElshoraa)
