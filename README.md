# Heart-Disease-Analysis- Power BI
## Project Objective
The Supply Chain Analytics Dashboard is designed to provide comprehensive visibility into critical supply chain operations, enabling stakeholders—including logistics managers, procurement teams, and executives—to make data-driven decisions. The dashboard tracks key performance indicators (KPIs) such as Order Fulfilment Rate, Inventory Turnover, Delivery Lead Time, and Supplier Performance, along with advanced analytics like Demand Forecasting, Cost-to-Serve Analysis, and Warehouse Efficiency Metrics.The dashboard helps stakeholders track sales performance, understand customer engagement, and identify growth opportunities through clear visualizations.
## Objectives
This dashboard provides a comprehensive view of key inventory and sales metrics across multiple dimensions. It combines summary KPIs, visual charts, and interactive slicers to help track performance and improve decision-making.

## KPI"S Performances:
1. Order & Sales KPIs
Total Orders → COUNT(Order_ID)
Total Sales Revenue → SUM(Unit_Price * Quantity)
Average Order Value (AOV) → SUM(Unit_Price * Quantity) / COUNT(Order_ID)
Orders by Region/Country/City (geographic insights)
2. Inventory & Stock KPIs
Stock on Hand → SUM(Stock_On_Hand)
Reorder Status → % of products where Stock_On_Hand < Reorder_Level
Average Lead Time → AVG(Lead_Time_Days)
Inventory Turnover Ratio → Total_Cost / Stock_On_Hand
3. Procurement & Cost KPIs
Procurement Cost → SUM(Procurement_Cost)
Transportation Cost → SUM(Transportation_Cost)
Total Supply Chain Cost → SUM(Total_Cost)
Cost per Unit → Total_Cost / SUM(Quantity)
4. Logistics & Delivery KPIs
On-Time Delivery % → % of orders where Delivery_Status = "On-Time"
Average Delay (days) → AVG(Delay_Days)
Orders by Ship Mode → Breakdown of Standard, Express, etc.
Transport Mode Utilization → Orders per Transport_Mode
5. Demand & Fulfillment KPIs
Forecast Accuracy → 1 - (ABS(Forecast_Demand - Actual_Demand) / Forecast_Demand)
Fill Rate → AVG(Fill_Rate) (or fulfilled quantity ÷ demand)
Backorder Rate → % of orders delayed due to insufficient stock
Demand vs Actual Sales Trend → Forecast vs Actual Demand chart

## Dashboards
### Excel Dashboard
  ![Excel](https://github.com/deepuhacker26/Supply-Chain-Analytics/blob/main/E1.png)
  ![Excel](https://github.com/deepuhacker26/Supply-Chain-Analytics/blob/main/E2.png)
### Tableau dashboard
  ![Tableau](https://github.com/deepuhacker26/Supply-Chain-Analytics/blob/main/T1.png)
  ![Tableau](https://github.com/deepuhacker26/Supply-Chain-Analytics/blob/main/T2.png)
### Power BI Dashboard
  ![Power BI](https://github.com/deepuhacker26/Supply-Chain-Analytics/blob/main/P1.png)
  ![Power BI](https://github.com/deepuhacker26/Supply-Chain-Analytics/blob/main/P2.png)
  ![Power BI](https://github.com/deepuhacker26/Supply-Chain-Analytics/blob/main/P3.png)
  ![Power BI](https://github.com/deepuhacker26/Supply-Chain-Analytics/blob/main/P4.png)
## Insights:
1. Financial Performance
Total Revenue: The supply chain generated a total of $12.48 million in sales revenue.
Profitability: With total costs (procurement + transportation) amounting to $1.28 million, the business maintains a very healthy profit of $11.20 million.
Regional Leaders: Revenue is distributed across multiple regions, with specific focus on Asia and North America as high-performing zones.
2. Logistics & Delivery Efficiency
Delivery Status: Approximately 76.5% of orders are delivered on-time, while 23.5% experience delays.
Shipping Paradox: Interestingly, "Same-day" shipping has the highest average delay (1.20 days), compared to "Standard" shipping (0.72 days). This suggests that the internal processes for expedited orders may be experiencing bottlenecks.
Transport Costs: As expected, Air is the most expensive transport mode (avg. $274.16), while Sea remains the most cost-effective (avg. $247.96).
3. Supplier Performance
Top Reliability: Gamma Inc is the most reliable supplier with the lowest average delay of 0.44 days.
Volume Leader: Delta Traders contributes the highest revenue (~$2.79M) but also has the highest average delay among suppliers (1.10 days), indicating a need for process improvement or diversified sourcing for their high-volume items.
Fill Rate: All major suppliers maintain a consistent fill rate of around 84-85%, showing stable stock fulfillment capabilities.
4. Inventory & Demand Management
Forecast Accuracy: The overall forecast accuracy is high at 87.66%, indicating that the demand planning team is effectively predicting market needs.
Stock Risk: There are 68 instances where the Stock on Hand has fallen below the Reorder Level. These items are at high risk of stockouts and should be prioritized for replenishment.
Inventory Turnover: The average Inventory Turnover Ratio is 1.73, suggesting a moderate rate of stock clearance.
5. Product Category Insights
Electronics and Food are among the top-performing categories by revenue.
The scatter plot of Forecast vs. Actual Demand shows a tight correlation, though some categories like "Apparel" occasionally see higher volatility between predicted and actual sales.
## Recommendations:
- Data-Driven Insights: Hospitality analytics helps track and improve hotel performance through data from Excel,
SQL, Power BI, and Tableau.
- Expedited Shipping Audit: Investigate why "Same-day" shipments are delayed more frequently than "Standard" shipments.
- Inventory Replenishment: Address the 68 items currently below reorder levels to prevent lost sales.
- Supplier Optimization: Work with Delta Traders to reduce their average delay days, as they handle the highest volume of sales revenue.
## Critical Takeways:
- Financial Strength: High profitability with $12.48M in revenue against $1.28M in total costs.
- Logistics Bottleneck: "Same-day" shipping is underperforming, averaging the highest delays (1.2 days) compared to standard shipping.
- Inventory Risk: 68 products are currently below their reorder levels and require immediate replenishment to avoid stockouts.
- Supplier Reliability: Gamma Inc is the most reliable (lowest delays), while Delta Traders handles the most volume but needs improvement on speed.
- Planning Accuracy: Demand forecasting is highly effective at 87.7% accuracy, minimizing the risk of excess dead stock.
## Author
Name: Makala Deepak
📧 Contact: [Makala Deepak](https://www.linkedin.com/in/makala-deepak-63471425a/)
