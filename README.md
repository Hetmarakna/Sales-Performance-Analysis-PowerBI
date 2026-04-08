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

# Key Insights – Sales Performance Dashboard

1. Overall Business Performance
   - The business has generated a total revenue of ₹129.49M, indicating strong overall sales performance.
   - With 7.1K total units sold and 3.5K total orders, the average order size is moderate, suggesting consistent customer demand.
   - The total cost (7.19M) is significantly lower than revenue, showing high profitability and efficient cost management.
- The company is operating with a strong profit margin and scalable sales model.

2. Sales Trend Analysis (Time-Based Performance)
   - Sales show fluctuating trends over time, with multiple peaks and drops.
   - The highest sales peak (~4.3M) occurs around 2023, indicating a strong performance period.
   - A major drop to near zero in 2024 suggests:
     - Incomplete data for 2024 OR
     - A sudden decline in sales (needs investigation).
   - Earlier dips (~1.1M in 2021) indicate temporary performance slowdowns.
- Sales are seasonal and volatile, requiring better forecasting and stability strategies.

3. Top Performing Products
   - Apple iPhone 14 (₹22M) is the top revenue-generating product.
   - Apple MacBook & Sony Bravia TV (~₹21M each) closely follow, showing strong demand for premium products.
   - Samsung Galaxy & HP Pavilion also contribute significantly.
- Premium electronics dominate revenue.
- The business relies heavily on high-value products rather than high volume.

4. Discount Strategy Analysis
   - High discounts (>20%) account for the majority (58 instances).
   - Medium (20) and Low (10) discounts are significantly lower.
   - No-discount sales are almost negligible (0).
- Sales are highly dependent on heavy discounting strategies.
- This may boost volume but can impact profit margins if not controlled.

5. City-Wise Sales Distribution
   - Sales are concentrated in major urban cities across India.
   - Larger bubbles indicate higher sales contribution from metro cities like:
     - Delhi
     - Mumbai
     - Bangalore
   - Smaller cities contribute less comparatively.
- Revenue is urban-centric, indicating strong presence in metro markets.
- There is an opportunity to expand in tier-2 and tier-3 cities.

6. Order-Level Insights (Detailed Table)
   - Repeated purchases by the same customers (e.g., Aarav Singh, Aman Verma) indicate customer loyalty.
   - Products like iPhone 14 are frequently purchased, reinforcing their popularity.
   - Discounts vary per transaction, showing dynamic pricing strategies.
   - Orders span multiple states like Maharashtra, Gujarat, and Madhya Pradesh.
- Strong repeat customer behavior supports business stability.
- Regional diversity shows wide market coverage.

7. Revenue vs Discount Relationship
   - High discount frequency aligns with strong sales performance.
   - However, excessive reliance on discounts suggests:
     - Customers may be price-sensitive
     - Sales may drop without offers
- The business should balance discounts with value-based selling to protect margins.

8. Operational Efficiency
   - High revenue with controlled cost indicates efficient operations.
   - Product mix is optimized toward high-margin items.
- The company has a profitable and efficient business model, but sustainability depends on reducing discount dependency.

# Conclusion 

- The business demonstrates strong revenue generation, high-performing premium products, and efficient cost control.
- However, it is heavily reliant on discounts and urban markets, which presents both opportunities and risks.
- Future growth can be achieved by:
  - Expanding into untapped regions
  - Reducing dependency on heavy discounts
  - Stabilizing sales trends
