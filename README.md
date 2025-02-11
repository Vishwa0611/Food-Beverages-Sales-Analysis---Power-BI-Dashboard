# Food-Beverages-Sales-Analysis---Power-BI-Dashboard

Overview

This Power BI dashboard provides insights into sales performance, revenue trends, and business metrics for a Food & Beverages company. It includes key visualizations such as revenue by year, channel, salesperson, manager, and product category, helping stakeholders make data-driven decisions.

Objective

--To analyze sales data and track business growth over time.
--To identify top-performing sales channels, managers, and products.
--To visualize order trends and revenue contributions.
--To improve decision-making through data insights.

Features

✅ Revenue Analysis: Calculates total revenue using Revenue = SUM(Sales[Sales]).
✅ Total Quantity Sold: Tracked using Total Quantity = SUM(Sales[Quantity]).
✅ Total Orders: Counted using Total Order = DISTINCTCOUNT(Sales[OrderNumber]).
✅ Trend Analysis: Yearly and category-wise revenue breakdown.
✅ Key Visuals: Bar charts, pie charts, and tree maps for insights.
✅ Filters & Slicers: Interactive controls for better exploration.

Dataset Used-

Sales Data: Includes OrderDate, Quantity, UnitPrice, Salesperson, Manager, and Channel.
Product Data: Contains ProductCategory, ProductName, and ProductGroup.
Power BI Measures Used
--Sales = Sales[Quantity] * Sales[UnitPrice]
--Revenue = SUM(Sales[Sales])
--Total Quantity = SUM(Sales[Quantity])
--Total Order = DISTINCTCOUNT(Sales[OrderNumber])

Dashboard Customization

Background Color: Changed from the Format pane under Canvas Background.
Themes: Customized under the View tab.
Interactivity: Added slicers for ProductCategory, Channel, and Year.

	Future Enhancements
🔹 Implement forecasting for revenue trends.
🔹 Add AI insights for deeper business recommendations.
🔹 Automate data refresh for real-time reporting.
