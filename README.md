# LITA-Capstone-Project-SD
This project was created to help businesses understand their sales performance, identify trends, and make data-driven decisions. By analyzing historical sales data, users can gain insights into customer behavior, seasonal trends, and revenue growth opportunities.

### Project Title : Sales Data Analysis
 [Project Overview](#project-overview)
 
 [Data Sources](#data-sources)
 
 [Tools Used](#tools-used)
  
 [Data Cleaning and Preparations](#data-cleaning-and-preparations)
   
 [Exploratory Data Analysis](#exploratory-data-analysis)
  
 [Data Analysis](#data-analysis)
   
 [Data Visualization](#data-visualization)

 ### Project Overview
---
Sales Analysis project is to understand and evaluate sales performance across products, regions, customer segments, and time periods

Key Goals:

1.Sales Performance Evaluation:
Assess sales data over a specific period to determine overall performance.
Identify high-performing products/services and underperformers.

2.Trend Identification:
Discover seasonal trends and purchasing patterns.
Evaluate the impact of marketing campaigns on sales.

3.Customer Satisfaction Analysis:
Gather customer feedback through surveys and reviews.
Analyze the correlation between satisfaction levels and sales.

4.Product and Market Insights:
Assess which products contribute most to revenue.
Identify market and seasonal trends.
Highlight underperforming products for potential optimization.

### Data Sources
---
The data source used an Excel worksheet by The Incubator Hub which consist of Customer data and Sales data. Other worksheet like this can be found on Kaggle or any other data site.

### Tools Used
---
- Microsoft Excel [Download Here] (http://www.microsoft.com)
  
     1.For Data Cleaning, MSExcel helps removes duplicates rows, which helps eliminate redundant data.
 
     2.For Analysing and using features like PivotTables, which allow users to filter, sort, and summarize large datasets for detailed analysis.
 
     3.For Visualising data trends and patterns

     4.For performing functions simplify tasks like summing, averaging, finding maximum or minimum values, and performing advanced calculations.
 
- SQL- Structured Query Language for Quering of Data, it also enable efficient data retrieval, manipulation, and management in relational databases, supporting applications from basic 
  data querying to complex analytics and transaction management.
  
- Microsoft PowerBi enables users to visualize and share insights from their data. Power BI provides a variety of tools and functions to help users import, transform, model, and 
  visualize data. [Download Here] (https://www.microsoft.com/en-us/download/details.aspx?id=58494)
  
- Github is a Web Based Portfolio Buliding Platform that hosts and manages code repositories, primarily focused on version control and collaboration for software development projects.

  ### Data Cleaning and Preparations
---
Data cleaning and preparation is a crucial first step in data analysis, ensuring that data is accurate, consistent, and ready for analysis;
1. Handling Missing Values
2. Removing Duplicates
3. Validation and Consistency Checks
4. Documenting Data Cleaning Process

### Exploratory Data Analysis
---
EDA involves the examination of data to uncover patterns, spot anomalies, and check assumption. It also involved the exploring of the Data to answer some questions 
  about the Data such as ;
- What is the size of the dataset (number of rows and columns)?
- What are the monthly, quarterly, and yearly sales trends? Is there an observable upward or downward trend over time?
- Are there any duplicate rows or records that need to be removed?
- Is there sufficient data to answer the key questions or support a model?
- Which products generate the highest sales, and what is their percentage contribution to overall sales?
- Which regions or cities have the highest sales, and how do they compare with other regions?
- Are certain product categories consistently performing well across all regions?
- Based on historical data, what are potential future sales trends?
  
### Data Analysis
  ---
  This is where we include some basic lines of codes or queries or even some of the DAX expressions used during your analysis

  ```SQL
  Select * from [dbo].[LITA SalesData]

 Select 
	Product, 
	SUM(Revenue) AS TotalRevenuePerProduct
FROM 
	[dbo].[LITA SalesData]
GROUP BY 
	Product
ORDER BY 
	TotalRevenuePerProduct DESC
  ```

EXCEL
TOTAL REVENUE PER REGION	
|REGION  |TOTAL REVENUE|
|------- |-------------|
|North 	 |387,000      |
|South	 |927,820      |
|East	 |485,925      |
|West	 |300,345      |
|TOTAL REVENUE| 2,101,090|

### Data Visualization

![sql](https://github.com/user-attachments/assets/e8d30078-435b-472a-b1b1-d8e443994557)


![Powerbi SD](https://github.com/user-attachments/assets/4c19cd06-e7ab-4c76-b1c6-a542b2f29fa7)


 ![Sales data](https://github.com/user-attachments/assets/b8c0aed6-84ef-4d05-b878-00feb563cf1d)
![SD 1](https://github.com/user-attachments/assets/d5320772-2f7a-475a-9dc2-05d759d7981e)
![SD 2](https://github.com/user-attachments/assets/b226df2f-ad23-494e-878d-2630fc92076b)
![SD 3](https://github.com/user-attachments/assets/ea434ea1-bc88-4e4a-be27-31c4cbcb2be2)
![SD 4](https://github.com/user-attachments/assets/53d1d708-7bee-40d9-a990-5c9852c552a0)
![SD 5](https://github.com/user-attachments/assets/d17fbe74-a8f4-44e9-a77e-6e14592a47ff)
![SD 6](https://github.com/user-attachments/assets/3c8118e6-f017-426a-87a7-fd8fadb99a00)
![SD 7](https://github.com/user-attachments/assets/a37d1ffa-dccf-45fa-b687-468051f26f7a)
![SD 8](https://github.com/user-attachments/assets/1577b438-c66c-44fc-8d9c-f718501c4e6b)



