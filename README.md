# E-Commerce-Sales-Inventory-Insights
Designed and developed an interactive E-Commerce Sales &amp; Inventory Dashboard in Power BI to provide actionable insights for business growth. The dashboard consolidates sales and inventory data, enabling stakeholders to monitor revenue trends, analyze top-performing products, track stock levels, and identify reorder needs in real time.


## Dataset used
- <a href = "https://github.com/msameerhanif/-E-Commerce-Sales-Inventory-Insights/blob/main/E-Commerce%20Store_Data.xlsx">Dataset</a>

## Questions (KPIs) This Dashboard Answers
### Sales Dashboard :
- What is the total shipped revenue, shipped COGS, and profit?
- How many units were shipped, and what is the revenue per unit?
- What is the gross profit margin %?
- How do monthly shipped revenue, COGS, and profit trend over time?
- Which brands contribute most to revenue and profit?
- Which brands face the highest customer returns?
### Inventory Dashboard:
- What is the total net received inventory value and units?
- What is the total sellable on-hand inventory value and units?
- What is the unsellable on-hand inventory value and units?
- How does inventory trend monthly (received vs. sellable vs. unsellable)?
- Which brands hold the highest sellable inventory?
- Which brands face the largest unsellable inventory losses?

- Dashboard Interaction <a href ="https://github.com/msameerhanif/-E-Commerce-Sales-Inventory-Insights/blob/main/Screenshots%20(2).JPG">Sales Dashboard</a> <a href ="https://github.com/msameerhanif/-E-Commerce-Sales-Inventory-Insights/blob/main/Screenshots%20(3).JPG">Inventory Dashboard</a>

## Process
- Collected sales and inventory data from Amazon Seller Central/warehouse systems.
- Used Power Query for cleaning, data transformations, and building calculated columns.
- Created DAX measures for revenue, profit, COGS, gross margin %, returns, and inventory KPIs.
- Designed line charts for monthly trends of revenue, COGS, and inventory.
- Built bar charts for brand-level performance (shipped revenue, profit, customer returns, inventory levels).
- Designed cards for high-level KPIs to give an instant summary.
- Integrated navigation (Home, Sales, and Inventory dashboards) for better user experience.

## Dashboard
![2 Amazon Sales Dashboard](https://github.com/user-attachments/assets/13e69fa3-d3c2-4954-a1c5-cd2567b9b762)
![3 Amazon Sales Dashboard](https://github.com/user-attachments/assets/4145238f-f248-44c9-b85e-90eb1c285af6)


## Built visualizations:
- Monthly revenue comparison chart (current vs. PY).
- Card visual for total revenue vs. PY.
- Car images with sales quantities for top-selling models.
- Country-wise sales table with revenue details.
- Donut chart for channel-wise sales distribution.
- Bar chart for year-over-year quantity sold.

## Project Insights:
### Sales Dashboard:
- Shipped Revenue: 1,114K with Profit of 165K → Profit margin 14.8%.
- Revenue per Unit: 16 AED shows healthy average selling price.
- Top Brand by Revenue: SNH Packing (758.1K revenue, 26.83K profit).
- Customer Returns: SNH Packing (561), UNKNOWN (112), and SherrifDrink (100) face highest returns → impacts profit.
- Monthly Trend: Revenue peaked in Feb (171K) but declined after May (167K → 155K in Jul).
### Inventory Dashboard:
- Net Received Inventory: AED 845K (61K units).
- Sellable On Hand Inventory: AED 1,084K (94K units).
- Unsellable On Hand Inventory: AED 4K (192 units).
- Top Inventory Holder: SNH Packing (Sellable = AED 789K).
- Inventory Risk: UNKNOWN brand shows the highest unsellable stock (AED 2,741).
- Trend: Inventory received fluctuates (peak in Feb at AED 189K, lowest in May at AED 103K).

## Final Conclusion:

The Amazon Power BI dashboards provide a holistic view of sales and inventory performance for SNH Packing and associated brands.

- Sales Performance: Strong overall revenue (1.11M) with positive profit margins (14.8%), though returns from key brands (SNH Packing, UNKNOWN) remain a challenge that reduces net profitability.
- Inventory Management: Sellable inventory remains strong at AED 1.08M, but unsellable stock, though small (AED 4K), highlights inefficiencies in quality or warehousing.
- Strategic Insight: Focusing on reducing returns and controlling unsellable inventory can improve overall profitability. SNH Packing dominates both revenue and inventory, meaning business reliance is high on one brand — diversification could reduce risk.
