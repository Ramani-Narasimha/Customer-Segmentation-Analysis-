# Customer Segmentation Analysis for a Retail Store

**Tools & Technologies:** Python (Pandas, Matplotlib, Seaborn, K-Means Clustering), Power BI, MySQL  

## Project Overview
This project analyzes a retail store’s customer data to identify customer segments and visualize insights. All data is **synthetic**, generated from Mockaroo.

## Dataset
- 1000 rows of customer data  
- Contains missing values  
- Missing value analysis performed per column  

## Python 
- Data cleaning and preprocessing  
- Missing value handling using pandas  
- Feature engineering (profit metrics, age groups, etc.)  
- K-Means clustering for customer segmentation  
- Data analysis using groupby and aggregations  
- Visualizations using Matplotlib & Seaborn  

## Power BI 
- Created 2–3 new DAX measures and used Power Query for data transformation  
- Developed an interactive dashboard with:  
  - Column charts and pie charts  
  - Gauge visuals  
  - KPIs  
  - Top 5 category filters with visual-level filtering  
  - Button slicer visual  
  - Added tooltips and slicer grouping (year, month, day, quarter)

## SQL
- Imported cleaned CSV data into MySQL using Table Data Import Wizard  
- Created a structured table (`customer_data`) with proper datatypes  
- Performed SQL-based analysis for metric validation and business insights  
- Major SQL operations performed:  
  - Data summarization using `count`, `sum`, `avg`  
  - Category-wise purchase and profit analysis using `group by`  
  - Customer segmentation analysis using `case when` (age grouping logic)  
  - Identified top-spending customers based on aggregated purchase amount  
  - Location-wise profitability comparison  

