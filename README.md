# PowerBI_AdventureWorks_Insights


## 1. Introduction
This project focuses on performing a detailed analysis of the **sales** and **returns** data from the **Adventure Works** dataset, using **Power BI** as the primary tool for analysis. The aim is to gain deeper insights into **customer purchasing behavior**, evaluate **product performance**, and understand **regional sales trends** over a period of three years (2020 to 2022). Through this analysis, the insights will aid in making better, data-driven decisions regarding **inventory management**, **marketing strategies**, and improving **customer satisfaction**.

## 2. Data Collection
- **Data Sources**: The dataset was sourced from the **Sales**, **Returns**, and **Customer** tables available in the Adventure Works database.

![image](https://github.com/user-attachments/assets/f7dadbfd-7d53-43d4-812f-00cc54d21549)
![image](https://github.com/user-attachments/assets/7bae73ed-1054-4b3f-8340-85e5be18f52c)
- **Number of Records**: The dataset consists of over **84,174 sales** records and around **1828 returns** records, making it a comprehensive source for understanding the overall business performance.

![image](https://github.com/user-attachments/assets/67b1115e-fea1-4acb-9649-f167b9abffa2)



- **Time Span**: The data collected covers a total of **3 years**, from **2020** to **2022**, which gives a detailed picture of sales trends and allows for year-on-year comparisons.

## 3. Data Cleaning
- **Handling Missing Values**: Any missing values were addressed by either removing the incomplete records, or where possible, filling them with average values. This step was essential to avoid gaps that might skew the analysis results.



- **Duplicate Removal**: Around **500 duplicate rows** were identified and removed from the dataset to ensure that the analysis remains accurate and no inflated or misleading data points impact the conclusions.
- **Formatting**: Dates and numeric values were standardized across all tables to ensure consistency. This includes setting a uniform date format (DD-MM-YYYY) and applying appropriate number formats for currencies and quantities.

![image](https://github.com/user-attachments/assets/89ea04cd-30d6-4820-9b30-dfb7419fa3cf)


![Screenshot 2024-09-18 120354](https://github.com/user-attachments/assets/161664a6-b790-49ce-8311-639e46c606dc)

## 4. Data Transformation
- **Calculated Columns**: Several new columns were created to enrich the data. For example, columns for **total sales** were added to help easily compute the overall performance metrics.

![image](https://github.com/user-attachments/assets/e5eceafb-cdb6-425c-9e00-ac533f9b10f7)

- **Data Grouping**: The data was grouped by **region**, **product categories**, and **customer segments** to allow for deeper, more focused analysis across multiple dimensions.
- **Data Types**: Each column was carefully reviewed to ensure that the data types were correctly assigned, such as **currency** for sales figures, **dates** for time-related data, and **text** for categorical variables like product names.

## 5. Creating Relationships
- **Establishing Relationships**: All possible relationships between the tables were created to ensure seamless integration of the data. The relationships were established based on the primary and foreign keys available in the dataset. 
  - **SalesTerritoryKey** was linked to the **SalesTerritory** table to allow regional analysis.
  - **ProductKey** was connected to the **Products** and **Categories** tables to enable detailed product performance analysis.
  - **CustomerKey** was linked to the **Customers** table to allow customer segmentation.
  - **DateKey** was connected to the **Date** table, which enabled time-based analysis for identifying trends from 2020 to 2022.
  
![image](https://github.com/user-attachments/assets/80024ed1-2d30-43cb-9824-4588a429e2e6)
![image](https://github.com/user-attachments/assets/f0ed0b96-0416-48eb-bf77-044d78d72cba)


  Establishing these relationships was crucial to unlock the full potential of the data, ensuring all tables could interact effectively for comprehensive analysis.

## 6. Data Analysis and Visualization
After preparing the data, the next step was to conduct the actual analysis and create visualizations to represent key insights:
- **Order Quantity by Marital Status**: The data revealed that about **60%** of total purchases were made by **married customers**, while **single customers** accounted for the remaining **40%**.
![image](https://github.com/user-attachments/assets/e091da1a-e00b-4559-b09a-4583edf930c2)

- **Order Quantity by Occupation**: It was found that **professionals** made up **45%** of the total orders, followed by **skilled manual laborers** at **30%**, and **management** at **20%**.

![image](https://github.com/user-attachments/assets/d0b6fd66-8ed1-4b22-ac7a-6ff51ae87358)

- **Sales by Country**: The majority of sales were concentrated in the **USA** (35%), followed by **Germany** (25%) and **Australia** (5%), indicating a strong focus on the American and European markets.

![image](https://github.com/user-attachments/assets/315c3ad4-af8a-4608-b92d-3c6613c74e89)

- **Return Rates by Product**: The highest return rate was observed in the **Accessories** category, which accounted for **60%** of all returns, followed by **Bikes** at **25%**.
- **Sales and Profit**: The analysis showed that total sales amounted to **$14.45 million**, and profits reached **$3.97 million** by the year **2021**, maintaining a steady profit margin of **37%** over the years.

![image](https://github.com/user-attachments/assets/67bade65-c2b1-4a03-9de1-f9678b03b077)

- **Revenue by Month**: The months of **November** and **December** generated peak revenues, reflecting strong year-end demand, while **June** recorded the lowest revenue, potentially indicating a seasonal dip in sales.



## 7. Dashboard Creation
- **Comprehensive Dashboard**: A single, all-in-one dashboard was built to display key data such as total sales, profits, and returns. It includes visuals for yearly performance, product categories, and regional sales, making it easy to track top-performing products and trends. The dashboard also highlights order quantities and return rates for different categories like Bikes, Accessories, and Clothing, giving a clear overview of the business's overall performance.

![image](https://github.com/user-attachments/assets/1ed89f78-2b16-4b3b-bb94-d8569cdb11c9)

## 8. Conclusion
The analysis of Adventure Works' sales and returns data provided several important insights. We discovered that **bikes** were the most popular product category, making up **45%** of sales but also having the highest return rate at **60%**. The **USA** and **Germany** were the top markets, together accounting for **50%** of total sales. The strongest sales growth occurred in **2021**, reflecting a particularly successful year for the company. The results of this analysis will help guide future decisions on **inventory management**, **marketing efforts**, and **customer targeting**. Further analysis could explore how different customer demographics influence purchase behavior and evaluate the effectiveness of various marketing campaigns.
