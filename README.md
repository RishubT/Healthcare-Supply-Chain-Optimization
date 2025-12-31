# Healthcare-Supply-Chain-Optimization
Python supply chain analysis optimizing inventory &amp; logistics. Strategic insights from raw data.

# Supply Chain Optimization & Strategic Analytics

This project transforms a raw supply chain dataset into actionable business frameworks using **Python**. It demonstrates the ability to move from unstructured data to prescriptive insights across inventory, quality, and logistics modules.

## Project Highlights

### **1. Inventory Rationalization (ABC Analysis)**

Using the **Pareto Principle**, I classified 100 SKUs based on their "Usage Value" (Cost  Products Sold).

* 
**High Value (Class A):** 35% of inventory.


* 
**Low Value (Class C):** **39% of inventory**.


* 
**Insight:** Identified opportunities to retire low-moving "Class C" items to free up working capital.



### **2. Quality & Cost Correlation**

I performed a statistical interrogation to see if higher manufacturing spends reduced defects.

* 
**Method:** Pearson correlation and linear regression.


* 
**Finding:** Proved **no statistically significant correlation** exists between cost and quality in this dataset.


* **Insight:** Quality issues require process-driven solutions rather than simple budget increases.

### **3. Logistics Efficiency Frontier**

Developed a **Reliability Score** (Coefficient of Variation) to tier shipping performance.

* 
**Cost Analysis:** Air transport costs **68.47% more per day** than Sea.


* 
**Provider Tiers:** Classified [Carrier + Route] combinations into **Gold, Silver, and Avoid** categories.


* 
**Insight:** Flagged high-variance routes as "broken processes" needing immediate intervention.



## 🛠️ Tech Stack

* 
**Analysis:** Pandas, NumPy.


* 
**Statistics:** SciPy.


*
**Visualization:** Matplotlib, Seaborn.

## How to Run

1. Clone this repository.
2. Ensure you have the `supply_chain_data.csv` in the root directory.
3. Run the Jupyter Notebook: `jupyter notebook learning.ipynb`.
