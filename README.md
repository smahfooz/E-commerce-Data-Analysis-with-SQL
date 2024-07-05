<h2><b>Executive Summary</b></h2>
<p>
  This project involved analyzing an extensive e-commerce dataset on Olist (Brazilian website) from Kaggle using SQL queries to uncover valuable insights into customer behavior, payment methods, product sales, and seller performance. 
</p>

By performing a series of complex queries on the dataset, the key findings are listed below:
<ul>
  <li>Identified the **most popular payment methods** and their average transaction values. </li>
  <li>Analyzed installment** payment preferences** among customers.</li>
  <li>Calculated the **average basket**.</li>
  <li>Identified **new and returning customers** and calculated their respective proportions.</li>
  <li>Conducted **RFM segmentation** to classify customers based on their purchasing behavior.</li>
  <li>Determined the **cities contributing the most to revenue (80%) and sales volume**.</li>
  <li>Listed top product categories sales in top 5 cities.</li>
  <li>Found commonly bought-together products.</li>
  <li>Evaluated seller performance in terms of order count, sales, and average ratings.</li>
  
The data source can be found here: https://www.kaggle.com/datasets/terencicp/e-commerce-dataset-by-olist-as-an-sqlite-database/data

**Business Problem**
The goal of this project was to analyze an e-commerce dataset to understand customer preferences, sales trends, and overall business performance. 
By gaining insights into these areas, the business can optimize its marketing efforts, improve inventory management, enhance customer service, and ultimately increase revenue and customer retention.

**Methodology**
To achieve the business objectives, conducted a thorough analysis of the e-commerce dataset using SQLlite. The dataset comprised several tables, including orders, customers, products, payments, reviews, and geolocation information. 

The following steps outline the methodology:

<ol>
  <li>**Understanding the Database Schema:**</li>
Explored the database schema to comprehend the relationships between tables. This understanding was crucial for designing efficient queries and ensuring accurate data extraction.

  <li>**Query Design and Execution:**</li>
Designed and executed SQL queries to answer specific business questions. These queries involved:
    <ul>
      <li>**Joins:** Combining data from multiple tables to get a comprehensive view of the dataset.</li>
      <li>**Aggregations:** Summarizing data to calculate metrics such as total sales, average basket size, and average payment value.</li>
      <li>**Subqueries and Common Table Expressions (CTEs):** Simplifying complex queries and improving readability.</li>
      <li>**Window Functions:** Performing calculations across a set of table rows related to the current row, useful for tasks like ranking and segmentation.</li>
    </ul>

  <li>**Payment Methods Analysis:**</li>
    <ul>
      <li>Identified the most used payment methods and calculated their average payment values to understand customer payment preferences.</li>
      <li>Analyzed the number of customers opting for installment payments and their corresponding order value.</li>
    </ul>

  <li>**Basket Size Calculation:** </li>
Calculated the average number of items per order to determine the typical basket size over different years, helping to understand purchasing patterns.

  <li>**Customer Segmentation:** </li>
    <ul>
      <li>Distinguished between new and returning customers to understand customer retention and loyalty.</li>
      <li>Conducted RFM (Recency, Frequency, Monetary) analysis to identify key customer segments like Champions, Loyal Customers, and Lost Customers.</li>
    </ul>

  <li>**Revenue and Volume Analysis by Location:** </li>
Identified the cities contributing to 80% of sales revenue and highest sales volume to optimize regional marketing and inventory strategies.

  <li>**Top Product Categories Analysis:**</li>
Listed the top product categories by sales to help in inventory planning and targeted marketing.

  <li>**Co-purchased Products Analysis:**</li>
Identified products frequently bought together to inform product bundling strategies and increase average order value.

  <li>**Seller Performance Evaluation:**</li>
Evaluated sellers based on order count, total sales, and average review scores to identify top-performing sellers and areas for improvement.

**SQL Concepts Demonstrated**
Joins | Aggregation | Window Functions | Date Functions | Case When | CTEs and Subqueries | Over/Partition By

**Next Steps**
<ol>
  <li>Build a PowerBI dashboard to visually demonstrate the key insights, allowing business stakeholders with a more intuitive interface to monitor business performance.</li>
  <li>Perfroming in-depth analysis in Pyhton to gather insights on user purchasing behaviour such as hour of day and day of week with most sales, root cause analysis on lower review ratings</li>
</ol>
