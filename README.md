# Executive Sales Report Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiNzJkYTZhZWMtYzY0Mi00NmZhLWJhMTUtNDljM2Y4OGFiOTM4IiwidCI6ImJkMDNhNzM1LTJhYTMtNGNjYS05NzIyLTJhZTQ5MjlhYjNlYyIsImMiOjEwfQ%3D%3D

## Problem Statement

This dashboard provides a comprehensive view of the sales performance across different categories and regions. It helps the business understand revenue trends, identify top-performing products and regions, and analyze profit margins. By utilizing this dashboard, decision-makers can strategize to improve sales, expand into new markets, and optimize profit margins.


The Executive Sales Report Dashboard showcases key metrics such as total revenue, units sold, average selling price, total profit, and profit margin percentage. It also includes visualizations for revenue trends over the years, units sold by country, total revenue by country, and revenue breakdown by category.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Verified data quality and handled any missing or erroneous values.
- Step 5 : Designed a custom theme and layout to ensure a unique and visually appealing report.
- Step 6 : Key metrics such as Total Revenue, Total Units Sold, Average Selling Price, Total Profit, and Profit Margin % were displayed using card visuals.
- Step 7 : A bar chart was used to visualize revenue trends over the fiscal years (FY2018, FY2019, FY2020).
- Step 8 : A map visual was used to display units sold by country, providing a geographical overview of sales distribution.
- Step 9 : A pie chart represented total revenue by country, highlighting major markets.
- Step 10 : A table visual showcased revenue breakdown by category, including Accessories, Bikes, Clothing, and Components.
- Step 11 : Added a text box for key insights, summarizing the overall sales performance and identifying key trends.
- Step 12 : Implemented slicers for filtering data by country to allow users to analyze specific regions.
- Step 13 : Ensured a clean and intuitive layout for easy navigation and interpretation of data.
- Step 14 : Incorporated corporate branding elements such as logos and color schemes.
- Step 15 : The report was published to Power BI Service, making it accessible to stakeholders for real-time data analysis and decision-making.


 
 # DAX Expressions Used

- **Total Revenue**: 
  ```DAX
  Total Revenue = SUM(fSales_Data[Sales Amount])
  ```
  ![image](https://github.com/user-attachments/assets/dd1356a6-7912-4658-b1cb-c5599f6d9388)
- **Total Unit Sold**: 
  ```DAX
  Total Unit Sold = SUM(fSales_Data[Order Quantity])
  ```
  ![image](https://github.com/user-attachments/assets/4e1386a8-4878-4e63-b3e4-42877ff69810)
- **Avg. Selling Price**: 
  ```DAX
  Avg. Selling Price = [Total Revenue] / [Total Unit Sold]
  ```
  ![image](https://github.com/user-attachments/assets/771039f5-fa88-40eb-9424-def888a669f6)
- **Total Profit**: 
  ```DAX
  Total Profit = [Total Revenue] - [Total Cost]
  ```
  ![image](https://github.com/user-attachments/assets/ee77367b-5d78-464b-bd12-bb308b58d246)
- **Profit Margin %**: 
  ```DAX
  Profit Margin % = [Profit] / [Total Revenue]
  ```
  ![image](https://github.com/user-attachments/assets/37e57d0a-23e5-4c45-99ea-f1e84739c5ec)


# Insights

### Total Revenue and Profit

- Total Revenue: $109.81M
- Total Profit: $65.84M
- Profit Margin: 59.96%

### Revenue Trends

- Significant revenue growth observed from FY2018 to FY2020, with the highest revenue in FY2020.

### Top Markets

- The United States is the largest market, contributing 57.37% of total revenue.
- Other key markets include Germany (14.89%), Canada (9.7%), France (6.99%), and the United Kingdom (6.6%).

### Product Category Performance

- Bikes are the top-selling category with $66.3M in revenue.
- Components and Clothing also contribute significantly, with revenues of $11.8M and $1.78M, respectively.
- Accessories have the lowest revenue at $571K.

### Strategic Recommendations

- Focus on expanding in high-performing markets such as the United States and Germany.
- Explore growth opportunities in emerging markets like Australia and France.
- Enhance marketing and sales strategies for lower-performing categories like Accessories.

### Snapshot of the Dashboard

![ROJO_Dashboard PowerBI](https://github.com/user-attachments/assets/3262791a-4c37-4803-9855-fc14d8b49fc9)
