# Global Superstore Sales - Analysis
## **I.INTRODUCTION**
In this project, a **_strategic dashboard_** was developed using _**Design Thinking**_ approach and _**Power BI**_ tools (**_DAX_**, **_Power Query_**, and **_Visualization_** tools) to analyze **_global sales performance_** over 4 years. The dashboard aimed to assist senior managers in **_understanding business performance by region, product, and sales personnel,_** which led to **_decisions_** in **_Market expansion_**, **_Market optimization_**, and **_Product selection_**.

### **1. BUSINESS QUESTIONS**
Superstore is a global retail enterprise with operations spanning multiple regions. Senior management of Superstore requires a ***detailed understanding*** of the company’s ***business performance*** to inform ***strategic decisions*** regarding:
  - Market Expansion
  - Selection of Key Products for Growth

### **2. DATASET**
The dataset (as attachment) contains global sales information of Superstore, including 3 tables:
- Orders: a table storing transaction information
- People: a table containing information about sales representatives in each region
- Returns: a table recording transactions that were returned

## **II. DASHBOARD**
### **Data Modeling**
![Relationship](https://github.com/user-attachments/assets/8c5302d8-5cc5-4ad3-886e-7218551831c1)

### **View 1: Product Analysis**
**REVENUE**
![RevenueProductAnalysis](https://github.com/user-attachments/assets/a8e62dd6-d536-4588-b69a-104b53ed900f)


**PROFIT**
![ProfitProductAnalysis](https://github.com/user-attachments/assets/d22c278a-0c34-4fb0-97be-0cbc7e640534)




➡️ Insights:

* **Phones, Copiers, and Chairs** are the top revenue-generating subcategories, suggesting strong demand.
* **Labels, Fasteners, and Envelopes** generate the lowest revenue, possibly indicating low sales volume or pricing issues.
* **Machines** are mid-tier performers but might have potential for expansion.
* **Tables** are also mid-tier but has negative profit.

Despite $12.64M in revenue, the total profit is only $51.29K, indicating **very low profit margins**.
Some high-revenue subcategories might have high costs or low pricing strategies, impacting profitability.


### **View 2: Market Analysis**
![MarketAnalysis](https://github.com/user-attachments/assets/81b0875c-267a-4e5a-afa5-f1bc1d25d8e0)

➡️ Insights:
* APAC, EU, LATAM, US, EMEA, Africa, and Canada are the key markets.
* US and EMEA have high profit margins, suggesting strong demand or better pricing strategies.
* Africa shows an increasing Year-over-Year (YoY) growth rate, indicating a potential emerging market opportunity.
* APAC has high customer volume but a lower profit margin, possibly due to competitive pricing or high operational costs.


### **View 3: Sales Agent Analysis**
![SalesAgentAnalysis](https://github.com/user-attachments/assets/3e3b04c1-6caa-4880-bfc2-8c026c5c557f)

➡️ Insights:
* Anna Andreaddi is the top-performing agent in both revenue and profit.
* Chuck Magee and Jack Lebron also contribute significantly, with high YoY growth rates (~48%).
* Jack Lebron has the highest growth rate at 48.79%, indicating strong sales expansion.

## **IV. INSIGHTS & RECOMMENDATIONS**
### 1. Market Overview
Identify High-Growth Regions:

Strong Existing Markets (Further Penetration)

EU & APAC → High revenue & profit, strong demand.
US & Canada → Stable growth, large customer base.
Emerging Markets (New Expansion)

LATAM & Africa → High YoY growth potential but lower market share.
EMEA → Mixed demand; expansion in profitable areas (Germany, France).
📌 Strategy: Prioritize EU & APAC for deeper penetration, while expanding carefully into LATAM & Africa.

![marketexpansion](https://github.com/user-attachments/assets/6084a287-a46e-47a9-aa37-c6321de48cb7)



### 2. Product Performance: 
  - **_Tables_** have shown **_poor performance_** with negative profit margins over the past four years, resulting in losses with each sale <br>--> **_Discontinue_** this product or **_adjust its pricing_**.

Double down on best sellers (Phones, Copiers, Chairs).

Optimize pricing for high-margin items.

Eliminate or reposition weak products.

Train & align sales teams for category-specific performance boosts.
