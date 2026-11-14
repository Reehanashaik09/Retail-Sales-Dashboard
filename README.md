# Retail Sales Data Dashboard (Superstore Sales Analysis)

## 1. Business Objectives
Analyze retail transactional data from the Superstore Sales Dataset to track overall revenue, profitability, sales trends over time, product category/sub-category performance, and regional variations for management reporting.

## 2. Dataset & Tools
- **Dataset:** [Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) (Kaggle)
- **Tool:** Microsoft Power BI Desktop

## 3. Data Preparation & KPI Metrics
- Cleaned transactional records and verified data types and date hierarchies (`Year`, `Quarter`, `Month`, `Day`).
- Designed core KPI cards:
  - **Total Sales:** $2.30M
  - **Total Profit:** $286.40K
  - **Profit Margin %:** 12.47%

## 4. Dashboard Visuals & Interactivity
- **Total Sales by Year (Line Chart):** Tracks annual revenue growth across the reporting period.
- **Sum of Sales Over Time (Trend Chart):** Displays granular time-series performance across Year, Quarter, Month, and Day.
- **Total Sales by Category (Donut Chart):** Compares revenue contribution across Technology, Furniture, and Office Supplies.
- **Total Sales by Sub-Category (Clustered Bar Chart):** Ranks individual product lines to identify top revenue drivers.
- **Region Slicer:** Interactive filter (`Central`, `East`, `South`, `West`) enabling dynamic regional drill-down across all KPIs and charts.

## 5. Key Findings & Recommendations
- **Sustained Revenue Growth:** Annual sales show a strong upward trajectory, indicating steady customer demand. *Recommendation:* Align inventory forecasting with peak seasonal months visible in the time-series trend.
- **Sub-Category Concentration:** Top sub-categories (such as Phones and Chairs) drive a disproportionate share of total sales. *Recommendation:* Prioritize stock availability and targeted promotions for high-performing sub-categories while reviewing discounting on lower-margin lines.
- **Regional Performance Variance:** Regional filtering highlights distinct sales and profit margin differences across `Central`, `East`, `South`, and `West`. *Recommendation:* Replicate successful pricing and fulfillment strategies from higher-margin regions (such as West and East) in lower-margin territories.
