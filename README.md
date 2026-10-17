 **Superstore Sales Analysis Dashboard

 **Project Overview
 An interactive sales dashboard built using Power BI and PostgreSQL to analyze sales, profit, orders, customers, and product performance.

 #Tools & Technologies
- Power BI
- PostgreSQL
- SQL
- DAX

# Dashboard Features
- KPI cards for Total Sales, Total Profit, Total Orders, Total Customers, and Profit Margin
- Monthly Sales Trend
- Sales and Profit by Category
- Regional and Segment Analysis
- Product and Sub-Category Profitability
- Interactive Category, Sub-Category, and Region slicers

# Business Objectives
- Monitor sales and profitability
- Compare product categories and regions
- Identify loss-making products
- Support data-driven business decisions

# Project Files
- `Superstore_Sales_Analysis.pbix` — Interactive Power BI report
- `screenshots/` — Dashboard screenshots

# Key Insights
Business insights will be added after validating the SQL query results.

** How to Use
Open the `.pbix` file using Power BI Desktop and interact with the slicers to explore the report.




# Dashboard Preview
# Executive Overview
![Executive Overview](Executive%20Overview.png)
# Products and Profit Analysis
![Products and Profit Analysis](Products%20And%20Profit%20Analysis.png)



# 1. Overall Business Performance
- The business generated total sales of 2,297,201.07 and total profit of 286,397.02.
- A total of 5,009 unique orders were recorded from 793 unique customers.
- The business sold 37,958 units across its product range.
- The overall profit margin was approximately 12.46%.
**Recommendation:** Monitor sales, profit margins, and customer purchasing patterns to identify opportunities for improving profitability.


**Business Recommendation:** Review Furniture's profitability and investigate the factors contributing to the difference in profit across categories. Verify the Office Supplies sales figure before drawing further conclusions.



# Key Insights
1. **Overall Performance:** Generated $2.30M in total sales and $286.4K in profit across 5,009 orders and 793 customers, with an overall profit margin of approximately 12.47%.

2. **Category Performance:** Technology was the leading category in both sales ($836.15K) and profit ($145.45K). Furniture generated $742K in sales but only $18.45K in profit, indicating an opportunity to review its pricing and discount strategy.

3. **Loss-Making Products:** Tables recorded the largest sub-category loss at $17.73K, followed by Bookcases ($3.47K) and Supplies ($1.19K). These areas need further investigation into discounts and profitability.



Region-wise Performance
- **West Region:** Generated the highest sales ($725,457.93) and profit ($108,418.45), making it the strongest-performing region.
- **East Region:** Ranked second in profitability, generating $91,522.78 in profit.
- **Central vs South:** Central generated higher sales ($501,239.88) than South ($390,764.32), but its profit was lower ($39,706.36 vs. $47,132.46). This suggests an opportunity to investigate discounting and product mix in the Central region.
- **Data Quality:** Records with a missing region showed $957.58 in sales and a loss of $383.03. These records should be reviewed during data cleaning.


 Monthly Sales Performance
- **Peak Sales Month:** November 2017 recorded the highest monthly sales among the top five months, reaching $118,447.81 with $9,690.10 in profit.
- **Strong Profit Month:** December 2016 generated $17,885.31 in profit on sales of $96,999.07, showing stronger profitability than November 2017 despite lower sales.
- **Business Recommendation:** Analyze seasonal demand and product performance during peak months to plan inventory and promotions more effectively.




















