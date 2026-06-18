#  Sales Performance Analysis – Project Notes

##  Project Purpose
The purpose of this project is to analyze sales performance, profitability, and returns using Power BI and present insights through an executive-level dashboard.

This dashboard helps stakeholders quickly understand:
- Sales and profit trends
- Regional performance
- Return behavior
- Profitability patterns

---

##  Data Model Overview
The data model follows a **star schema** approach:
- Fact tables store transactional data (Sales, Returns)
- Dimension tables include Date, Region, Category, and Product

Relationships are created to ensure accurate filtering and aggregation.

---

##  KPIs & Measures
Key DAX measures used in this project include:
- Total Sales
- Total Profit
- Profit Margin %
- Return Rate %
- Total Returns

These measures are designed to support high-level decision-making.

---

##  Dashboard Design Decisions
- KPI cards placed at the top for instant insights
- Combination charts used for Sales vs Profit comparison
- Consistent color theme aligned with Power BI branding
- Slicers added for Year and Month filtering
- Layout optimized for executive readability

---

#  Business Use Case
This dashboard can be used by:
- Sales Managers
- Business Analysts
- Executives

To:
- Monitor performance across regions
- Identify areas with high returns
- Track profitability trends over time
- Support strategic planning decisions

---

## Future Enhancements
- Drill-through pages for region-level analysis
- Forecasting using time-series models
- Customer segmentation analysis
- Deployment to Power BI Service with scheduled refresh
