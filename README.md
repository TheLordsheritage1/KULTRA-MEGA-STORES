# KULTRA-MEGA-STORES
# DSA- DATA DOCUMENTATION AND ANALYSIS USING SEQUENCE LANGUAGE QUERY(SQL).

I was able to attempt this project thanks to the foundational knowledge and skills I acquired through my data analysis training at DSA, combined with using tools such as SQL and Excel.

## TABLE OF CONTENTS 
- Project topic.
- Project overview.
- Data description.
- Tools used.
- Data cleaning and preparation. 
- Exploratory data analysis.
- Key insights and findings.
- Recommendations.
- Conclusion.

## PROJECT TOPIC: KULTRA MEAGA STORES INDUSTRY(KMS) ANALYSIS.

## PROJECT OVERVIEW:
The project was carried out as part of my data analysis learning journey. It aims to uncover insights from a sample dataset through data exploration, cleaning, and SQL-based analysis. Its aim is also to assist in business decision-making including identifying high- and low-performing products, customer trends, and revenue patterns.

Throughout this project journey, I was able to practice key analytical skills such as writing optimized SQL queries, drawing meaningful conclusions from raw data, and presenting findings in a clear and structured format. The project simulates real-world business analysis and reflects my enthusiasm to take on new challenges even as I continue developing my skills.

## DATA DESCRIPTION:
 The data set used for this analysis was provided as part of a structured project work. It was extracted from ms excel and queried in sql. It contains transactional data of kultra mega stores inventory, with its headquarters in Lagos and having one of its branches at abuja and it specializes in office supplies and furnitures. 
 The data set was collected at the abuja branch from the period of 2009-2012. It has a maximum of 8400 rows and 21 columns covering key variables such as:

a. Customer name: 
The full name of the customer who made the purchase. This helps identify which customer placed the order.

b. Order ID:
A unique identification code assigned to each order. This is used to track and differentiate one order from another.

c. Order Date:
The date when the order was placed. It helps in analyzing sales trends over time, like monthly or yearly performance.

d. Order Price:
The total cost of the items in the order before any discounts or additional charges (like shipping). This can also help in revenue tracking.

e. Sales:
The actual revenue generated from the order, which might include or exclude discounts depending on the dataset. Useful for profit and performance analysis.

f. Shipping Mode:
The method used to deliver the order to the customer (e.g., Standard Class, First Class, Same Day). It’s helpful for studying delivery efficincy.

g. Region:
The location or area where the order was delivered. This can be used to compare sales performance across different locations or markets

## TOOLS USED:
- MICROSOFT EXCEL:
   - For data exploration 
- SQL:
  - for data analysis
  - For dada querying
  - For extracting insights.

## DATA CLEANING AND PREPARATION.
In this project, the dataset was well-structured and required little additional cleaning. Most entries were complete, correctly formatted, and free from duplicates or inconsistencies. As a result, no extensive data cleaning was performed.
During the initial review of the dataset, some null values were observed. However, these missing entries were not significant enough to affect the overall analysis. As a result, they were retained, and no imputation or deletion was carried out.

The dataset was then prepared and checked to ensure consistency in data types and formatting before moving into the analysis phase.

## EXPLORATORY DATA ANALYSIS.
At this stage, I made use of both Ms excel and sql  to explore the dataset and draw meaning insights. I was able to examine trends, distributions, and relationships between variables to aid better understanding of the data. This process also helped me spot any unusual values or patterns that could affect further analysis. 

Some key focus in the exploratory data analysis are
1. _What are the top three and bottom three regions in terms of sales:_

To understand how different regions performed in terms of revenue generation, I analyzed the total sales across all regions. This helps identify which areas contributed most to the business and which ones lagged behind.

Visualization; top three regions with the highest total sales which indicating strong market presence or customer activity.
<img width="1020" height="695" alt="top three regions" src="https://github.com/user-attachments/assets/97223291-2fdb-482b-9b33-3692d04ee156" />


visualization; Bottom 3 regions with the lowest total sales which possibly highlights areas of weak performance or low customer activity 
<img width="1012" height="691" alt="BOTTOM THREE REGIONS" src="https://github.com/user-attachments/assets/678b5ec8-b386-425f-9a28-dfd1c46a0f71" />


2. _Which product category has the highest sales:_
   To ascertain this, i had to sum up the total sales and then group it by category to arrive at the answer. From the Visualization it is visible that technology has the higest sales.

 visualization: 
<img width="1016" height="708" alt="HIGHEST PRODUCT" src="https://github.com/user-attachments/assets/02bb73b4-892d-4f0f-8529-dbc15a5e58e9" />

3. _Which small business customer had the highest sales:_
The same process above is repeated here and from the analysis i was able to draw that Dennis kane has the highest sales which simply indicates high market presence.
visualization:
<img width="1020" height="713" alt="HIGHEST SMALL BUSINESS" src="https://github.com/user-attachments/assets/6d2e6dc8-0c13-4773-a193-05f0a4902172" />

4. _Which customer consumer was the most profitable one:_
   Most profitable customer consumer simply means the person that generates the most revenue, so i used the profit column, i summed up the profit column, grouped by customer name and was able to pinpoint that dave kipp was the most profitable customer 

visualization:
<img width="1366" height="768" alt="MOST PROFITALE CUSTOMER" src="https://github.com/user-attachments/assets/bc248aa9-43ae-491d-9396-456cea4ba6aa" />

5. _Kms incurred the most shipping cost by what shipping mode:_
The shipping mode that used the most shipping cost was the delivery van, possibly due to large order of goods that were in close proximity or orders that didn't require the need of water or air shipping mode.
visualization:
<img width="1012" height="695" alt="SHIPPING COST" src="https://github.com/user-attachments/assets/1aab7be0-6c58-4f68-9e5a-de7ae90e92f3" />

6. _Which corporate customer placed the most number of order in 2009-2012:_

visualization:
<img width="1016" height="689" alt="CORPORATE CUSTOMER ORDER" src="https://github.com/user-attachments/assets/56d176cd-e6b1-44a4-b332-0b3f85030a15" />

## KEY INSIGHTS.
- The analysis of the top and bottom 3 regions provides direction for strategic decisions such as where to invest more resources or investigate sales challenges.
- After analysis it was found that Technology category generated the highest revenue, indicating strong customer demand and high-value transactions in this segment.
- The analysis shows that Dennis kane, a small business segnent incurred the highest sales compared to other business segments.
- After analysis, Dave kipps was drawn out to be the most profitable consumer customer.
- Delivery truck incurred the most shipping cost
- Between 2009 and 2012, the corporate customer with the highest number of orders was Adam Hart, placing a total of 27 orders within the period. This indicates a strong and consistent engagement with the business during those years. The customer's loyalty and frequent purchases suggest they could be a key account for sales and relationship management strategies

## RECOMMENDATIONS.
1. The business should investigate on the regions that doesn't have high sales and come up with strategic way on how to increase consumer participation in those areas.
2. The business should also direct more resources to the segments and businesses that generate high revenue so as to futher increase the revenue generated by those places.
3. The business should ensure they maintain a good relationship with their most loyal customers to as to retain their loyalty as it also helps to bring goodwill to the business.
4. The organization should engage in corporate social responsibilitiy(CRS) especially in the areas with least sales or low market participation as this will as encourage consumers to purchase more of their products compared to their competitors.

## CONCLUSION.

In conclusion, this data analysis project provided a valuable opportunity to explore real-world business data using SQL queries. Through various stages ranging from data cleaning and preparation to exploration and insight generation I was able to extract meaningful patterns and trends that revealed critical business metrics such as customer behavior, sales performance, and regional distribution. SQL proved to be an effective tool for handling large datasets, filtering relevant information, and performing aggregate functions to support decision-making.

Although some challenges were encountered during the process, such as handling null values and structuring complex queries, they contributed to my learning experience and helped improve my analytical thinking. Overall, this project not only enhanced my technical skills in SQL but also deepened my understanding of how data can drive informed business strategies. Moving forward, I hope to continue building on this foundation by exploring more advanced data
