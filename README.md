# Supply-Chain-Analysis-Project
In this project, I will find a dataset on Kaggle and clean data, analyze trends, create kpis, and make a dashboard to provide a deep analysis on said data.
Define business questions: 
- total revenue, total profit, profit margin?
- Which sales channel drives the most revenue?
- Which products sell the most units vs. generate the most revenue?
- Which products have the highest margin?
- Which warehouses handle the most volume?
- How long does it take from order -> ship -> delivery on average?
- Which regions outperform?

PROJECT SUMMARY:
Goal: clean a raw regional sales dataset and turn it into an Excel workbook that answers questions above, using dynamic formulas, summary tables, and charts.
Dataset: 7,991 orders from June 2018- December 2020, across 4 sales channels, 6 warehouses, and 47 products.
Approach: First I checked and cleaned the data for cost errors, fixed date logic issues, duplicates. Then I added calculated fields in the raw data: Revenue, Cost, Profit, Margin, Order->Ship days, Ship->Delivery Days, Order-> delivery days, and year/month/quarter labels. Then defined a set of busines metrics: order volume, discount impact, fullfillment speed for delivery. Then created dynamic summary tables by channel, product and warehouse. Which all comes to a single page dashboard shwoing top KPIs and key charts pulled live from each analysis tab.

KEY FINDINGS:
Total Revenue: $73.1M , Total Cost: $51.8M, Total Profit: $21.3M, Overall Margin:29.2%
7,991 orders, 36,162 units sold, 11.4% average discount applied

In-Store leads with $30.1M revenue (41% of total) and 14,878 units across 3,298 orders
Online is second at $21.7M (30%), Distributor at $13.2M (18%), Wholesale smallest at $8.2M (11%)
Margins are fairly consistent across channels (28–30%), so the revenue gap is driven by volume, not pricing strategy.

Product #23 tops both lists, highest revenue ($2.10M) and highest units sold (956)
Product #8 has the highest margin (31.4%), followed by #16 (31.3%) and #2 (31.2%)
Margins across the top 10 are tightly clustered (30.6–31.4%), suggesting no single product is a major outlier.

WARE-NMK1003 handles by far the most volume: 11,351 units across 2,505 orders (~31% of all units)
WARE-PUJ1005 is a distant second (6,572 units); WARE-NBV1002 handles the least (3,101 units)

AVERAGE ORDER->SHIP->DELIVERY TIME:
Order → Ship: 15.2 days
Ship → Delivery: 5.5 days
Order → Delivery (total): 20.7 days
