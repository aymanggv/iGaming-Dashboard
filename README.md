# iGaming Performance & Strategy Dashboard

**Dashboard Link**: [Click here to access the dashboard](https://public.tableau.com/app/profile/ayman.gundru/viz/Book1_17469997268340/PerformanceOverview?publish=yes)

## Overview

This Tableau dashboard presents an analysis of iGaming performance across multiple products and markets for the period of February–April 2023. It provides deep insights into revenue generation, user engagement, product trends, and strategic opportunities.

Each page in the dashboard includes navigation buttons to guide users through the analysis flow.

---

## Contents

This analysis is based on the supporting report **"iGaming Performance & Strategy Report"**, and includes:

- **Performance Overview**  
- **Product Breakdown**  
- **Market-Level Insights**  
- **User Behavior & Engagement**  
- **Bonus Strategy Evaluation**  
- **Strategic Recommendations**

---

## Data Preparation Summary

The dataset was restructured and cleaned using the following steps:

- **Unpivoted Data**: Transformed wide-format metrics into long format for better Tableau handling.
- **Attribute Splitting**: Separated product-specific metrics (e.g., `sports_ngr_eur`) into two fields: `attribute` and `product`.
- **Type Adjustments**: Year and month converted to string types for flexible date handling.
- **Aggregation Handling**: Where inconsistencies were found (e.g., bonus totals), pre-aggregated fields were used to maintain data integrity.
- **Metric Calculations**: 
  - FTD Conversion = `FTDs / Registrations`
  - Revenue Per User = `Revenue / Total Users`
  - Withdrawal Rate = `Withdrawn / Total Amount`
  - Click Conversion = `Clicks / Views`

---

## Key Insights

### 📈 Performance Growth
- Net Revenue: **€1.28M → €3.89M**
- Active Players: **8.1K → 25.9K**
- Casino was the top revenue driver, followed by Sports and Live Casino.

### 🌍 Market Highlights
- **Sweden (SE)**: Top performer with €1.83M in revenue.
- **Brazil (BR)**: Poor FTD conversion (3.9%) despite high registrations.
- **Malta (MT)**: Reported negative ROI and revenue—possible fraud risk.
- **New Zealand (NZ)**: Best bonus ROI (32.74%).

### 🎯 Strategic Recommendations
- Address FTD issues in BR.
- Tighter bonus controls in IE, CA, PE.
- Reallocate bonuses to high-ROI markets like NZ and SE.
- Invest further in Sports & Live Casino for SE and FI.

---

## Technical Design

### Tableau Optimization Techniques Used:
- **Extract filters** and **Context filters** for faster performance.
- **Window functions** for rolling and comparative metrics.

### Filter Usage:
- Product toggles allow for the inclusion/exclusion of "overall" non-product metrics.
- Custom date and market filters included for dynamic slicing.

---

## Notes

- Analysis limited to 3 months of data (Feb–Apr 2023).
- Navigation buttons embedded on each dashboard page for guided analysis.
- Metrics are calculated based on cleaned and validated data to ensure report integrity.

