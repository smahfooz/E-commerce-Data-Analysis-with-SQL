<h2><b>Executive Summary</b></h2>
<p>
  This project involved analyzing an extensive e-commerce dataset on Olist (Brazilian website) from Kaggle using SQL queries to uncover valuable insights into customer behavior, payment methods, product sales, and seller performance. 
</p>

By performing a series of complex queries on the dataset, the key findings are listed below:
<ul>
  <li>Identified the <b>most popular payment methods</b> and their average transaction values. </li>
  <li>Analyzed installment <b>payment preferences</b> among customers.</li>
  <li>Calculated the <b>average basket size</b>.</li>
  <li>Identified <b>new and returning customers</b> and calculated their respective proportions.</li>
  <li>Conducted <b>RFM segmentation</b> to classify customers based on their purchasing behavior.</li>
  <li>Determined the <b>cities contributing the most to revenue (80%) and sales volume</b>.</li>
  <li>Listed <b>top product categories</b> in top cities in terms of sales revenue.</li>
  <li>Found <b>commonly bought-together products</b>.</li>
  <li>Evaluated <b>seller performance</b> in terms of order count, sales, and average ratings.</li>
</ul>
<p>The data source can be found here: https://www.kaggle.com/datasets/terencicp/e-commerce-dataset-by-olist-as-an-sqlite-database/data</p>  

<h2><b>Business Problem</b></h2>
<p>The goal of this project was to analyze an e-commerce dataset to understand customer preferences, sales trends, and overall business performance. 
By gaining insights into these areas, the business can optimize its marketing efforts, improve inventory management, enhance customer service, and ultimately increase revenue and customer retention.</p>

<h2><b>Methodology</b></h2>
<p>To achieve the business objectives, conducted a thorough analysis of the e-commerce dataset using SQLlite. The dataset comprised several tables, including orders, customers, products, payments, reviews, and geolocation information. </p>
<p>The following steps outline the methodology:</p>
<ol>
  <li><h4>Understanding the Database Schema:</h4></li>
Explored the database schema to comprehend the relationships between tables. This understanding was crucial for designing efficient queries and ensuring accurate data extraction.

  <li><h4>Query Design and Execution:</h4></li>
Designed and executed SQL queries to answer specific business questions. These queries involved:
<p>
  <ul>
      <li><b>Joins:</b> Combining data from multiple tables to get a comprehensive view of the dataset.</li>
      <li><b>Aggregations:</b> Summarizing data to calculate metrics such as total sales, average basket size, and average payment value.</li>
      <li><b>Subqueries and Common Table Expressions (CTEs):</b> Simplifying complex queries and improving readability.</li>
      <li><b>Window Functions:</b> Performing calculations across a set of table rows related to the current row, useful for tasks like ranking and segmentation.</li>
    </ul>
</p>
    
  <li><h4>Payment Methods Analysis:</h4></li>
    <ul>
      <li>Identified the most used payment methods and calculated their average payment values to understand customer payment preferences.</li>
      <li>Analyzed the number of customers opting for installment payments and their corresponding order value.</li>
    </ul>

  <li><h4>Basket Size Calculation:</h4></li>
Calculated the average number of items per order to determine the typical basket size over different years, helping to understand purchasing patterns.

  <li><h4>Customer Segmentation:</h4></li>
    <ul>
      <li>Distinguished between new and returning customers to understand customer retention and loyalty.</li>
      <li>Conducted RFM (Recency, Frequency, Monetary) analysis to identify key customer segments like Champions, Loyal Customers, and Lost Customers.</li>
    </ul>

  <li><h4>Revenue and Volume Analysis by Location:</h4></li>
Identified the cities contributing to 80% of sales revenue and highest sales volume to optimize regional marketing and inventory strategies.

  <li><h4>Top Product Categories Analysis:</h4></li>
Listed the top product categories by sales to help in inventory planning and targeted marketing.

  <li><h4>Co-purchased Products Analysis:</h4></li>
Identified products frequently bought together to inform product bundling strategies and increase average order value.

  <li><h4>Seller Performance Evaluation:</h4></li>
Evaluated sellers based on order count, total sales, and average review scores to identify top-performing sellers and areas for improvement.
</ol>

<h2><b>SQL Concepts Demonstrated</b></h2>
Joins | Aggregation | Window Functions | Date Functions | Case When | CTEs and Subqueries | Over/Partition By

<h2><b>Key Findings</b></h2>
<ul>
  <li>The data distribution is skewed and there could be presence of outliers which needs to be further investigated</li>
  <li> 76% of total customers used Credit Card as preferred payment method </li>
  <li>Single payment methods are the most common, especially for lower order values. Higher payment values are associated with more instalments</li>
  <li>Average basket price and size have not changed significantly over the years, though there is a slight decrease from 2016-2018 (needs to be further investigated)</li>
  <li>97* customers are new - need for customer retention and increase customer engagement strategies</li>
</ul>

<h2><b>To be further investigated</b></h2>
<ul>
  <li>The data distribution is skewed and there could be presence of outliers.</li>
  <li>Average basket price and size have not changed significantly over the years, but there is a slight decrease from 2016-2018 even though 2016 data is from September.
</ul>

<h2><b>Next Steps</b></h2>
<ol type="1">
  <li>Build a PowerBI dashboard to visually demonstrate the key insights, allowing business stakeholders with a more intuitive interface to monitor business performance.</li>
  <li>Perfroming in-depth analysis in Pyhton to gather insights on user purchasing behaviour such as hour of day and day of week with most sales, root cause analysis on lower review ratings.</li>
</ol>
