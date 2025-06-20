<p align="center">

*This repository contains my portfolio of Power BI projects, showcasing my end-to-end skills from data transformation in Power Query to building interactive dashboards*
  
## 🧭 Data Analytics Portfolio Projects
*Click on any skill to jump to the relevant projects section.*
<p align="left">
<a href="#power-bi-projects">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/></a>
&nbsp;&nbsp;
<a href="#tableau-projects">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau"/></a>
  
## 🚀 My Projects  
*Here are some of the projects I've worked on. Each project includes a link to a detailed breakdown of the process, from data sourcing to final insights.*

   ## Project 1: Online Sales Overview – Bemidji Crafts Co.
    This dynamic Power BI dashboard was developed to analyze and visualize online sales data for a local artisan shop. 
    The goal is to provide actionable insights into sales performance, product popularity, and customer behavior.

 ➡️ [**View Project Details & Breakdown**](https://github.com/antonjeeva5/power-bi-projects/blob/main/Project%201:%20Online%20Sales%20Overview%20%E2%80%93%20Bemidji%20Crafts%20Co./README.md)

 <details>
  <summary><strong>➡️ View Project Details & Breakdown</strong></summary>
  
  ---
  
  ### Project Breakdown: Retail Sales Performance
  
  ![Full Dashboard Screenshot](https://placehold.co/800x450/4F46E5/FFFFFF?text=Full+Retail+Dashboard)

  #### Problem Statement
  The primary goal was to create a dynamic dashboard for leadership to monitor sales and profitability. Key questions to answer included:
  - What are the top-selling products and regions?
  - How does profit margin change over time?
  - Are we meeting monthly sales targets?

  #### Data Transformation (Power Query)
  - Connected to a CSV file containing raw sales data.
  - Removed duplicate rows and handled missing values in the `Region` column.
  - Created a new conditional column for 'Profit Margin Category' (Low, Medium, High).
  - Unpivoted columns to transform the data from a wide to a long format for better analysis.

  #### Key DAX Measures
  - **Total Sales (YTD):** `Sales YTD = TOTALYTD(SUM(Sales[Revenue]), 'Date'[Date])`
  - **Profit Margin %:** `Profit Margin % = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Revenue]))`

  #### Insights & Recommendations
  1.  **Insight:** The 'Technology' category has the highest revenue but the lowest profit margin (12%).
      - **Recommendation:** Review pricing for high-cost tech items to improve profitability.
  2.  **Insight:** The West region consistently underperforms in Q4 compared to other regions.
       - **Recommendation:** Launch a targeted marketing campaign in the West region in Q3 to boost holiday sales.
  
  ---
</details>
