 E-Commerce Business Intelligence Dashboard
📖 Project Overview
This project focuses on providing actionable insights for a CEO to monitor global sales performance. By transforming raw transactional data into interactive visualizations, the dashboard highlights revenue trends, market penetration, and high-value customer segments for the year 2011.


🎯 Problem Statement
The objective was to design a reporting suite that answers four critical business questions:


Revenue Seasonality: What does the monthly revenue trend look like for 2011? 



Market Comparison: Which top 10 countries (excluding the UK) are leading in both revenue and volume? 


Customer Performance: Who are the top 10 customers contributing to the company's bottom line? 


Geographic Distribution: Where are the highest concentrations of units sold globally (outside the UK)? 

🛠️ Data Processing & Visualization Logic
To ensure accuracy, the following data transformations were applied:


Metric Creation: Revenue was calculated by multiplying Quantity by Unit Price.


Temporal Filtering: The analysis was restricted to data from the year 2011 and aggregated by month to show granularity.


Customer Validation: Filtered the data to include only valid CustomerIDs, removing entries where IDs were missing.


Regional Focus: Excluded the United Kingdom from specific visuals to better analyze international market expansion.


<img width="1920" height="1020" alt="Screenshot 2026-02-07 204225" src="https://github.com/user-attachments/assets/bf93a7ee-751f-4bba-ad0f-535a8f927fee" />



Instructions: Use a Line Chart for trends , a Side-by-Side Bar Chart for country comparisons , a Column Chart for customer rankings , and a Map Chart for global sales.
+3

🔍 Key Insights & Recommendations
Insights

Trend Analysis: The monthly line chart identifies peak sales periods, allowing the business to prepare for seasonal demand.


Top Markets: By analyzing the top 10 countries by revenue, the business can see which regions have the highest purchase volume relative to their quantity.


Customer Concentration: A small group of top 10 customers represents a significant portion of total revenue, sorted in descending order for clarity.

Recommendations

Market Diversification: Since the UK is the primary market, focus the next marketing budget on the top 3 countries identified in the map visual to reduce regional dependency.


VIP Retention: Implement a loyalty program specifically for the top 10 identified CustomerIDs to ensure long-term revenue stability.


Inventory Planning: Use the monthly revenue granularity to optimize supply chain operations for the high-performing months identified in the 2011 dat
