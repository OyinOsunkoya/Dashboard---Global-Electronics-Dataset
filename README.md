Table of Content
# Project Background
GE Electronics, established in 2016, is an international retailer offering electronic products online and in-store across eight countries. The company collects data on its sales, product offerings, customers and operational efficiency. This project analyzes this data to uncover key insights that will improve GE Electronics' performance across its business.
Insights and recommendations are provided on the following key areas of business:
- **Sales:** The analysis includes sales, quantity, profit, and cost volumes compared to the previous year, along with monthly sales trends and a breakdown by category, brand, and online versus in-store sales.
- **Customer:** An analysis on the number of customers, spend per customer, order volumes and customer distribution. The top ten customers are highlighted to illustrate their impact on the company's KPIs.
- **Store:** The analysis provides an overview of the stores and their operations, including sales volume, the number of customers and order volumes. KPIs can be viewed at the store level to enhance understanding of individual store performance.
- **Executive Summary:** This shows global KPI trends in the above three key business areas to the management executives. The KPI trends are available since the establishment of GE Electronics in 2016 till February 2021.

The interactive Tableau report can be viewed [here](https://public.tableau.com/app/profile/oyinkansola.osunkoya/viz/GlobalElectronics_17454403238890/ExecutiveSummary).<br>
The Sales, Customer and Store dashboards will be used by the business teams in each country, so country selection in the dashboard filter should be used to view the dashboards for the respective countries. KPIs in the dashboards can be viewed in either United States dollars (USD) or the local currency (LOC) of the respective countries.

# Data Structure Overview
GE Electronics database structure as seen below consists of five tables: sales, products, customers, stores and exchange rate with a total row count of 62,885 records.
![alt text](<Entity Relationship Diagram.png>)

# Insights Deep Dive
The insights presented in the sales, customer and store dashboards are for the year 2020 in comparison to 2019 for all countries. Detailed insights by country are available [here](<Insights by country.md>).<br>

# Executive Summary
![alt text](<Executive Summary.png>)
-  Sales, Quantity, Profit and Cost increased from 2016 to 2019 and then decreased in 2020. This was due to the Covid-19 virus. Data for 2021 is only available until February 2021, hence the sharp decrease in 2021.
- Gross profit margin has remained steady over the years, despite the changes in sales and profit over the years. This signifies that sales and costs increased and decreased on similar levels over the years.
- The number of customers, who purchased from GE Electronics steadily increased from 2016 till 2019 and then decreased in both 2020 and 2021. Customers who purchased products both online and in-store has increased over the years. The percentage of customers who bought online only increased slightly over the years, while the customers who bought only in-store decreased over the years. 
- The percentage of in-store sales in total sales has decreased over the years, while the percentage of online sales in total sales has increased over the years. The trend of increasing online sales over the years was firstly due to the increased convenience of online shopping, and intensified during the Covid-19 pandemic and the lockdowns during this time. <br>

## Sales Dashboard:
![alt text](<Sales Dashboard.png>)
- In most countries, sales in 2020 declined by approximately 50% in comparison to 2019, with the Covid-19 pandemic identified as the primary driver of this decrease. France experienced the lowest decrease of 32%, while Italy suffered the highest decline of 57%.
- Quantity sold decreased by a similar magnitude as sales in all markets; except in France, where sales decreased by 32% and quantity sold by 43% implying an increase in the average selling price.
- Every product category experienced a decrease in sales in all markets, except TV and Video in France, which increased by 78%. 
- The decrease in sales in-store was larger than the decrease in sales online except in Italy, where in-store sales decreased by 54% while online sales decreased by 68%, as well as in the US where online sales experienced a decrease of 51% while in-store sales decreased by 47% in comparison to 2019.
- In the months of November and December, there was a spike in sales in all countries, which was driven by seasonal Christmas shopping.<br>

## Customer Dashboard:
![alt text](<Customer Dashboard.png>)
- More than 70% of customers in the countries, shop exclusively in-store, and less than 10 percent of the customers shop both in-store and online. France has the largest share of customers only shopping in-store with 77%, Australia and Germany have the largest share of customers only shoppping online with 25%, while the US has the largest share of customers shopping both online and in-store.
- In 2020, all countries experienced a decline of over 30% in both the number of customers and total orders compared to 2019. Italy was most affected, with a 53% decrease in customer count and a 62% drop in order volume. The sales per customer also decreased but to a much lesser degree in all countries.
- Majority of customers were repeat customers, who purchased three or less orders from GE Electronics in 2020. In the UK and US, the highest share of customers purchased two or three orders.
- Although there are a lot of repeat customers, the majority of top customers contributing to the profit made by GE Electronics in 2020 made only a single purchase during the year.<br>

## Store Dashboard:
![alt text](<Store Dashboard.png>)
- No new store was opened in any of the countries. On the contrary, one store was closed both in Germany and in the US in 2020. This is because these stores underperformed by more than 20% in sales and profit compared to other stores in the country.
- Sales per store, Customer per store and Order per store declined by more than 35% in all countries, with Italy experiencing the highest decrease - sales per store fell by 54%, customers per store by 59%, and rder per store by 62%.
- In France, the UK and the US, the top 3 stores display comparable performance in teerms of Sales and Profit per square meter. In contrast, Australia, Germany and Italy, experienced large differences in their top 3 stores, for example, the top store made almost two times the sales of the second top store.<br>

# Recommendations
- Marketing and promotional efforts should be strategically intensified during the months of November and December to capitalize on seasonal demand and further drive sales. Initiatives may include the development of holiday gift guides featuring GE Electronics products, the provision of complimentary gift-wrapping services, and the introduction of exclusive holiday discounts and loyalty rewards to enhance customer engagement and conversion.
- Introduce a time-bound discount incentive for customers whose purchases exceed a specified threshold (e.g., USD 15,000 in the U.S. or AUD 5,000 in Australia), to encourage repeat purchases from GE Electronics. While there is a strong base of repeat customers overall, data shows that the majority of top-tier customers in each market tend to make only a single purchase annually. This initiative aims to increase purchase frequency among this high-value segment.
- An analysis of sales per square meter indicates that many larger stores are generating comparable or lower sales than smaller-format locations. To enhance overall store performance and space utilization, it is recommended to evaluate opportunities to reduce store footprints where appropriate. Additionally, underutilized areas can be repurposed for alternative functions—such as incorporating a compact bakery or convenience section to drive foot traffic, or designating space for online order fulfillment to support online sales growth.
