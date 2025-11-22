# Retail-Sales-and-Customer-Insights-Dashboard
Retail Sales, Customer Insights and Product Insights (Power BI)
## Key features
- MoM growth cards and trends
- Top products and regions
- Customer metrics: AOV, repeat customers

## How to view
Open `retail_dashboard.pbix` in Power BI Desktop or view the published report (link).

## DAX highlights
- Total Sales = SUM(Sales[SalesAmount])
- Total Quantity = SUM( Sales[Quantity] )
- Total Cost = SUM( Sales[Cost] )
- Profit = [Total Sales] - [Total Cost]
- Profit Margin % = DIVIDE( [Profit], [Total Sales], 0 ) and much more!

  Do take a look!!
