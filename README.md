# B&J-Biscuits-Excel-Dashboard-Analysis
## Introduction 
This project seek to identify valuable insights from an interactive dashboard that provides insights into various aspects of our business, including revenue distribution, customer demographics, geographic performance, andprofitability. 

## Project Overview:
This project consists of two dashboards, both having different details and giving different insights.
#### Dashboard 1
We need a dashboard that includes the following key metrics and 
visualizations:
1. Revenue Distribution:
 - By product price category (high-priced vs. low-priced). (Low >=10, 
High<10)
 - By age group and gender.
 - By payment method.
2. Profitability Analysis:
 - Most profitable brand, location, customer, and salesperson.
 - Overall profit margin.
3. Customer Insights:
 - Top 5 customers by revenue contribution.
 - Total number of customers acquired.
4. Geographic Revenue Distribution:
 - Revenue share across key geographic locations.
5. Sales Performance:
 - Metrics such as quantity sold, total revenue, total cost of goods sold 
(COGS), and total profit.
Specific Requirements:
- preferred tool or platform: Excel
- Design Preferences: We would like the dashboard to be user-friendly, 
visually appealing, and interactive, with filters for location, payment 
method, and age group.
#### Goals of the Dashboard:
- Enable quick and informed decision-making by providing key business
- Identify profitable segments and customer demographics to optimize 
marketing and sales strategies.
- Monitor sales performance and track customer acquisition.

#### Dashboard 2
The dashboard should include the following components:
1. Revenue Analysis:
 - Revenue by Values: Display total revenue in absolute terms across 
different categories, such as by product, location, and customer segment.
 - Revenue by Percentage: Include percentage contributions to total 
revenue from various segments, such as product lines, age groups, and 
geographic regions.
2. Change Analysis:
 - Quarter-over-Quarter (QoQ) Change: Visualize quarterly revenue 
changes, highlighting percentage increases or decreases to identify 
trends.
 - Month-over-Month (MoM) Change: Present monthly revenue changes, 
with annotations to explain significant fluctuations (e.g., promotional 
campaigns, market shifts).
 - Week-over-Week (WoW) Change: Provide weekly revenue changes, 
with specific attention to the performance of different weekdays and 
weekends.
3. Key Performance Indicators (KPIs):
 - High-Level Metrics: Display key financial KPIs such as Quantity Sold, 
Total COGS, Total Revenue, Total Profit, and Profit Margin.
 - Profitability Insights: Highlight the most profitable brand, location, 
customer, and age group.
4. Interactive Features:
 - Toggle Between Revenue Views: Allow users to switch between 
viewing data by revenue values and by percentage contributions easily.
 - Dynamic Filters: Implement filters for locations and payment methods 
(e.g., Cash, Credit Card, Debit Card, Mobile Payment) to enable 
customized views of the data.
5. Additional Insights:
 - Annotations for Significant Changes: Include the ability to annotate 
data points in the MoM and WoW change charts to explain key events 
or anomalies in the data.
 - Comparison Between Weekdays and Weekends: Analyze and 
compare revenue contributions from weekdays versus weekends.
#### Goals for the Dashboard:
- Comprehensive Analysis: Provide a holistic view of our revenue 
performance, both in absolute terms and as a percentage of the total.
- Trend Identification: Quickly identify trends and anomalies in revenue 
changes, enabling swift business responses.
- Performance Monitoring: Regularly track key metrics to monitor business 
health and identify areas for strategic focus.
### Datasource 
The project consists of two dataset namely, Transaction dataset and products dataset. The transaction sheet contains 12000 rows and 10 columns whereas the product sheet contains 4 columns and 10 rows. <br>
This gives you access to the raw data used for the project .  [B&J Buscuit Practice Dataset.xlsx](https://github.com/user-attachments/files/18069115/B.J.Buscuit.Practice.Dataset.xlsx)
Microsoft Excel was the only software package used for this project.
## Data Cleaning
Addition of new of columns was one of the key assignment inorder to prepare the data for proper analysis.
- The raw data was quite neat from the onset. Firstly, the date columns was formatted to from number to date format.
- Xlookup was used to get data from the product dataset to the transaction dataset with product code as lookup value for the biscuits brand, unit price and cost.
#### New Columns.
- Revenue: Quantity sold * Unit Price
- COGS: Quantity sold * Cost Price
- Profit: Revenue - COGS
- Product Type:Less expensive product [If unit price < 10 Euros] and Expensive if otherwise
- Age: The date_diff function was utilized here, making use of the buyer's date of birth and transaction date inorder to get the age of the buyer during time of transaction.
- Age group: The floor excel function was used here for grouping the age into interval of 14 years apart.
- Full Name: This is gotten by using the Text Join function to combine first and last name.
- Weekdays: With the use of the text function, I was able to format the transaction date into days format.
- Weektype: This divides the weekdays into weekends and weekdays. <br>
In addition, excel pivot table came in handy in summarizing of data and also for grouping the date data into months,Quarters and others.

## Insights from Analysis.
From the first dashboard analysis, I was able to conclude that
- Generally, mobile payment was the most used payment platform for goods purchase.
- Debit card generates more revenue and profit in the sense that expensive goods are mostly bought via debit card.
- The male gender has the highest purchasing power in all age group and in turn generates most revenue and profit.
- In general, expensive product generates the most revenue.
- The purchase of Ginger snap is very low among the 15-29 age group.
- The most profitable age group is the 60-70 group.
While from the second dashboard,
- Weekdays contribute more sales and profit
- The half of the year generates the most profit and revenue.

## Recommendation and Proposal.
- Less expensive products should be placed in the market inorder to boost sales amongst the 15-29 age group.
- Inorder to get more profit from the 15-29 group, San Antonio should be focused on more and cash should be the major payment platform.
- Since Houston are selling more goods and generating more profit and revenue from the 60-74 age group, product brands that are of health benefit should be 
  constantly sold. Ginger snaps being made from ginger which is spice is of health benefit to eldery people.

## Conclusion.
The 
  
  
