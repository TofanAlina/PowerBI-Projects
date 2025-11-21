# Sales Data Analysis Project

This Power BI dashboard structured in 3 pages analyzes sales data, while helping users track revenue growth, product performance and customer buying patterns over time through interactive visualizations.

### 1. Sources/Tutorials/Data

This project was created following these tutorials: [Codebasics Playlist](https://youtube.com/playlist?list=PLeo1K3hjS3uva8pk1FI3iK9kCOKQdz1I9&si=_hUiMtjbXMgH6Uvi) as a starting point, with additional dashboards, analyses & visualizations implemented by me as personal contributions. The sample dataset used can be found here: [Sales Insights Dataset](https://codebasics.io/resources/sales-insights-data-analysis-project) , it was provided by the tutorial author and simulates the activity of a computer hardware business in India interested in sales insights. 
No sensitive or real company data is included.

### 2. Technologies Used

- MySQL Server & MySQL Workbench – used to store the dataset, for initial analysis/exploring the raw data and cross-check results from Power BI
- Power Query – for data cleaning, transformation and data modeling
- DAX – for calculated measures and KPIs
- Power BI Desktop – for building interactive dashboards and visual analytics

### 3. Base Components (from Tutorial) + Personal Contributions
       
The structure of the Main Dashboard and the core visualizations were built following the tutorial. This dashboard provides an **overall view of business performance** across the analyzed time period (June 2017 – June 2020), highlighting:
-	Total revenue,
-	Total sales quantity
-	Total number of orders

Additionally, it helps users understand how the sales revenue evolved over time, or for any selected time period, through rankings of the top-performing products, customers and sales regions that collectively generated the highest revenue. This dashboard can help business stakeholders **answer questions** such as:
- Which products and regions generate the highest revenue?
- Which clients contribute the most to total revenue?
- In which months does the business generate the strongest revenue, and are there any recurring patterns?
- How has business performance evolved over time (2020 vs. 2017 or year-over-year comparisons)?
  
#### Insights Example
One particularly interesting observation is that the Ahmedabad market generated the 3rd highest revenue (130M INR) while ranking only 5th in sales quantity. This suggests that higher-value products are selling more successfully in that region. The business could test a similar pricing or product-mix strategy  in the Nagpur market, where the quantity sold is ~30% higher than in Ahmedabad, yet revenue is less than 50%.

### Personal Contributions
To practice and build upon the insights gained from the tutorials, I created two additional secondary dashboards for a more in-depth analysis:
1. *Sales Insights* - this report can help the users with two different perspectives:
   1. For a selected product, users can see when it sold best, to which customers, and where.
   2. For a specific month(year) in the analyzed period, the treemap will show where the most products were sold, to which customers and whether the **Monthly Sales Quantity Target (KPI)** was achieved or exceeded. (Example available in the pdf)
>Note: I calculated the Monthly Sales Quantity Target KPI as an average of the sales quantity in 2019 (71.000) approximated to 75.000 to highlight **growth potential**.

2. *Consumer Insights* - this dashboard serves the users with a detailed **buying profile** of a selected customer through a Customer Purchase Mix Analysis and their average monthly number of orders, while also highlighting any notable shopping behavior patterns observed over the three-year analyzed period.

### 4. Conclusions & Business Recommendations (Fictive)
Conclusions:
- Revenue growth peaked in the summer months (July/August) for 2018 and 2019.
- Overall revenue trend is declining; in January 2020, revenue dropped by ~40% compared to January 2018.
- The Delhi NCR region is the top market by both revenue and sales quantity.
- The Electricalsara Stores customer consistently contributed the most to total revenue.
- December appears to have the lowest number of products sold.
- In 2019, the Monthly Sales KPI was exceeded in 25% of the months, compared to ~75% in 2018, reflecting a decline in demand.
- Most customers had a diverse Customer Purchase Mix.

Recommendations:
- Focus marketing and sales efforts on high-value products in regions with high revenue per unit, such as Ahmedabad.
- Communicate with clients in the brick-and-mortar sector to understand low sales performance (25% of consumers are in this segment).
- Adjust inventory and promotion strategies to align with seasonal demand patterns.
- Investigate customers with decreasing purchase trends to identify reasons (e.g., switching suppliers, product dissatisfaction).
  
### Personal Reflection

My most important takeaways from this project were understanding the process of building a data analysis project — from performing ETL on raw data to creating clear and insightful visualizations — and learning about the AIMS Grid, which is helpful for clarifying tasks and defining project goals. Moreover, I strengthened my SQL skills and developed the ability to design visualizations and analyses that answer specific business questions and extract valuable insights from raw data.
