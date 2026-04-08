# Sales-Performance-Analysis-PowerBI

# Overview
This dashboard focuses on analyzing sales data across multiple dimensions such as **product lines, regions, customer segments, and time periods.** It enables users to monitor overall performance, evaluate profitability, and uncover hidden opportunities for growth.

# Objective
The primary goal of this project is to transform raw insurance data into meaningful insights through interactive visualizations. The dashboard aims to help stakeholders:
- Understand customer segmentation
- Analyze product line and sales
- Identify profit, revenue and net sales
- Improve decision-making through data-driven insights

# Key Areas of Focus
- Customer Demographics: Analysis of age, gender, and region-wise distribution of policyholders.
- Product Analysis: Analysis of all the product categories
- Financial Insights: Revenue trends, total claims paid, and profitability metrics.
- Interactive Filters: Dynamic slicers for users to drill down into specific data points.

# Tools and Technologies Used
- **Power BI:** All data visualizations, including interactive dashboards and analytical reports, are built in Power BI to present insights effectively.

- **Excel/CSV:** For data storage and processing.

- **Power Query:** Applied for data transformation, cleaning, and structuring before analysis.

- **ETL:** Data was extracted, transformed, and loaded into Power BI for analysis.

- **Git & GitHub:** Used for version control, project tracking, and sharing SQL queries. Git LFS is implemented to handle large CSV files in the dataset.

- **DAX & Time Intelligence:** Used DAX functions and calendar tables for advanced analytics.

# Skills Demonstrated
- Data cleaning and transformation
- Dashboard design and visualization
- Interactive reporting using Power BI
- Data-driven decision-making

# Dataset

The Insurance dataset contains the following information :
1. Dim Customers :- CustomerID, Customer Name, City, State, Pincode, EmailID, Phone Number.
2. Dim Product :- ProductID, Product Name, Product Line, Price (INR).
3. Dim Promotion :- PromotionID, Promotion Name, Ad type, Coupon Code, Price Reduction Type.
4. Main Dataset :- Date, CustomerID, PromotionID, ProductID, Units Sold, Price Per Unit, Total Sales, Discount Percentage, Discount Value, Net Sales.

# Key Features 

1. Key Mertics :-
   - Total Revenue
   - Total Profit
   - Total Expenses
   - Profit Margin (%)
2. Interactive Visulizations :-
   - Sales vs Profit Analysis (Scatter Chart)
   - Discount Analysis (Bar Chart)
   - Region-wise / City-wise Sales Map
   - Category & Product Line Performance
3. Dynamic Filters (Slicers) :-
   - Product Line
   - Region / State
   - Time (Month / Year)
  
# ETL Process :- 

An ETL (Extract, Transform, Load) process was implemented to prepare the data for analysis:

  - Extract: Data was extracted from the Csv file and it's customer information, product information and order records.
  - Transform: The data was cleaned, transformed, handle missing values, and format it for business intelligence analysis. Key transformations included:
      - Calculate all the values in Main dataset like price per unit, net sales, discount value
  - Load: The cleaned and transformed data was loaded into Power BI for building the dashboards and creating visual insights.

# Interactive PowerBI Dashboard

<img width="1269" height="752" alt="Part-1" src="https://github.com/user-attachments/assets/7c302a3c-d462-4842-9124-869484af1a25" />
<img width="1263" height="750" alt="Part-2" src="https://github.com/user-attachments/assets/a18e399b-e4d4-4658-a95a-713f826a9d93" />

