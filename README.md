**Sales Analytics Project**

![image](https://github.com/user-attachments/assets/e89605c4-e299-49aa-8daa-c97dcc83a573)


**Overview**

This project focuses on sales analytics for Atliq Mart, a growing FMCG manufacturer. The objective was to analyze various sales data across different dimensions (such as products, markets, and customers) to generate insightful reports that help the business make informed decisions.

![image](https://github.com/user-attachments/assets/0810895f-e0cc-4c77-bfb0-92fbf07b6157)


**Project Objectives**

The primary goals of this project were to:

Identify the top 10 products based on the percentage increase in net sales from 2020 to 2021.

Generate a "Division" report to present net sales data for 2020 and 2021, along with the growth percentage.

Rank products to determine the top 5 and bottom 5 in terms of quantity sold.

Identify new products that Atliq Mart began selling in 2021.

Determine the top 5 countries by net sales in 2021.

**Data Sources**

The analysis was conducted using the following tables:

dim_customer: Contains customer-related information.

dim_market: Contains market-related information.

dim_product: Contains product-related information.

fact_sales_monthly: Contains monthly sales data.

dim_date: A date dimension table created using Power Query.

dim_target: Contains target sales data for market performance analysis.

**Project Workflow**

**Data Preparation:**

Performed ETL (Extract, Transform, Load) operations to clean and structure the data.

Created a dim_date table using Power Query to facilitate time-based analysis.

Connected tables using data modeling techniques in Power Pivot.

![image](https://github.com/user-attachments/assets/310011fb-24e5-48cb-b9fb-46aca9880cee)


**Data Analysis:**

**Customer Performance Reports:**

Generated using data from dim_customer, dim_product, and fact_sales_monthly tables.

![image](https://github.com/user-attachments/assets/f7979f15-af1e-4176-980f-0900bf8fbf31)


**Market Performance vs. Target Reports:** Created using data from dim_market and dim_target tables.

Developed new measures in Power Query to calculate growth percentages, rankings, and identify new product entries.

![image](https://github.com/user-attachments/assets/dd80dcf1-01f2-443f-9adb-b8583199aeaf)


**Report Generation:**

Created detailed reports in Power BI that answer specific business inquiries, such as:

Top 10 products by percentage increase in net sales.

"Division" report showcasing net sales for 2020 and 2021.

Ranking of top 5 and bottom 5 products by quantity sold.

![image](https://github.com/user-attachments/assets/b1a4a9bd-5784-49af-933f-4dfba7760cff)


Identification of new products sold in 2021.

![image](https://github.com/user-attachments/assets/656053bf-e333-44f6-9004-9a70982b6d9d)


Top 5 countries by net sales in 2021.

![image](https://github.com/user-attachments/assets/519ffdaa-7c80-44a3-8d73-f9670a3bcdf7)


**Tools & Technologies**

Excel: For data cleaning, analysis, and report generation.

Power Pivot: For data modeling, analysis, and report generation.

Power Query: For data transformation and creation of the dim_date table.

**Results**

The reports generated from this project provide insights into product performance, market trends, and customer behavior, helping Atliq Mart optimize their sales strategy and drive growth.

**Conclusion**

This project demonstrates how Excel can be effectively used for data analysis and reporting to solve real-world business problems. The insights derived from this analysis enable data-driven decision-making.


