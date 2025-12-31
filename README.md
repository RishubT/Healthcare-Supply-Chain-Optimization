# Healthcare-Supply-Chain-Optimization
Python supply chain analysis optimizing inventory &amp; logistics. Strategic insights from raw data.

# Supply Chain Optimization & Strategic Analytics

This project transforms a raw supply chain dataset into actionable business frameworks using **Python**. It demonstrates the ability to move from unstructured data to prescriptive insights across inventory, quality, and logistics modules.

**Executive Summary: Supply Chain Optimization Analysis**

Project Overview
This analysis evaluates a supply chain dataset containing 100 product records across 24 variables. The goal was to transform unstructured data into actionable strategic frameworks for inventory management, quality control, and logistics efficiency.

**1. Inventory Rationalization (ABC Analysis)**
* To optimize working capital, products were classified using the Pareto Principle based on their "Usage Value" (Cost  Products Sold).
* High Value (Class A): Represents 35% of the inventory. These are the most critical items requiring tight control.
* Medium Value (Class B): Represents 26% of the inventory.
* Low Value (Class C): Represents 39% of the inventory. These items are numerous but contribute the least value.
* **Strategic Insight:** The team should evaluate retiring or reducing stock for Class C items, as they consume resources without producing significant revenue.

**2. Manufacturing Quality & Cost Analysis**
* A correlation study was conducted to determine if higher manufacturing spends resulted in superior product quality.
* Findings: Statistical analysis and linear regression revealed no significant correlation between manufacturing costs and defect rates.
* **Strategic Insight:** Increasing the budget for manufacturing is not a viable solution for reducing defects. Quality improvements must instead focus on process optimization and specific supplier performance metrics.


**3. Logistics & Shipping Reliability**
* Shipping performance was analyzed across carriers, routes, and transportation modes to identify the "Efficiency Frontier".
* Cost vs. Speed: Using Air transportation costs approximately 68.47% more per day than shipping by Sea.
* Reliability Scoring: Carriers and routes were tiered into Gold, Silver, and Avoid categories based on a Reliability Score (Coefficient of Variation).
* Critical Alerts: Specific combinations, such as Carrier B on Route B and Carrier C on Route C, were flagged as "Avoid" due to high variance or poor mean shipping times.

**4. Strategic Recommendations**

1.  Reallocate Capital: Shift focus and budget from the 39% of "Low Value" SKUs toward "Class A" items to improve profitability.
2.  Supplier Performance: Implement a weighted scorecard for suppliers, specifically targeting Supplier 3, who is currently performing significantly worse than peers.
3.  Logistics Shift: Investigate moving more operations to Sea routes where time-sensitivity is lower, as the cost-per-day savings are substantial (68% reduction) with minimal impact on overall efficiency.

** Tech Stack **
* Analysis: Pandas, NumPy.
* Statistics: SciPy.
* Visualization: Matplotlib, Seaborn.

** How to Run **
1. Clone this repository.
2. Ensure you have the `supply_chain_data.csv` in the root directory.
3. Run the Jupyter Notebook: `jupyter notebook learning.ipynb`.

