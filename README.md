# Blink it Sales Analysis

Dataset: - <a href="https://docs.google.com/spreadsheets/d/1tdF_beuexr4n46cuZY8P-b8JCCYN-SNZ/edit?gid=1156682977#gid=1156682977">Dataset</a>

Report Link: - <a href="https://app.powerbi.com/groups/me/reports/6e0bead9-4254-4609-b9e3-d8c8555a360d/b8e4b5a7ee8ba792606c?experience=power-bi">Report</a>

## Problem Statement

This dashboard provides insights into Blinkit's sales performance, helping stakeholders understand key sales trends, product demand, and revenue generation. The report aids in identifying high-performing products, peak sales periods, and customer purchasing patterns. These insights allow for strategic decision-making to optimize inventory, marketing campaigns, and operational efficiency.

### Steps followed:

Step 1: Loaded sales data into Power BI Desktop. The dataset is a CSV file.

Step 2: Opened Power Query Editor and enabled "Column Distribution," "Column Quality," and "Column Profile" to assess data quality.


Step 3: Checked for missing values and inconsistencies, performed necessary data cleaning and transformations.

Step 4: Created calculated columns for total sale, average sales, number of items and average rating using DAX.

Step 5: Applied necessary data filters to segment sales by product category, outlet location and fat content.

Step 6: Added key performance indicators (KPIs) such as total sales, average sales, average rating and number of items.

Step 7: Created interactive visuals including:

    Sales performance by fat content using Donut chart.
	Category-wise sales via stacked bar chart.
	Outlet type wise sales using matrix table.
	Sales by outlet establishment year with line chart.
	Sales performance by out location type using funnel chart.
    Card visulas for KPIs.
    Slicers to filter the data.

Step 8: Added slicers for filtering data by Outlet location type, item type and outlet size.

Step 9: Published the report to Power BI Service for easy accessibility and sharing.

### Insights

#### 1. Sales Performance Overview

Total sales: $1.20M

Card visual used to represent this total sales


![Image](https://github.com/user-attachments/assets/d6dc933e-c31d-4409-a560-eed20d52c284)


Average sales: $141

Card visual used to represent this average sales


![Image](https://github.com/user-attachments/assets/80754cf0-bbe9-47c2-86d4-9b5d0312910a)


Highest sale's revenue by item establishment year: $2,04,522 in 2018.
Highest sales are from Supermarket type 1.
#### 2. Product PerformanceTop 3 best-selling products:
	
    Fruits and Vegetables
    Snack foods
    Household

Fat wise sales distribution: Highest sales for "Low fat products".


![Image](https://github.com/user-attachments/assets/3bfac63a-b193-43a3-a457-e63e8b7f28b4)


#### 3. Regional Sales Trends

	Highest sales in: Tier 3 locations 4,72,133
	Lowest sales in: Tier 1 locations
![Image](https://github.com/user-attachments/assets/39ae7a55-e81d-433e-b33b-71a00e4dbc97)

### Snapshot of Dashboard (Power BI Services):
![Image](https://github.com/user-attachments/assets/7ca4bd19-bea6-442b-960b-f443b2d639bc)

### Conclusion:
This Blinkit Sales Report provides valuable insights into sales trends, product attributes, outlet performance,The key takeaways include:
#### Outlet Factors: 
Larger and older outlets in urban areas perform better, suggesting a focus on expansion strategies in high-demand areas.
#### Product Optimization: 
Low-fat items and grocery products drive sales, emphasizing the need for strategic inventory management.

By leveraging these insights, Blinkit can refine its inventory strategies, optimize outlet performance, and enhance customer satisfaction, ultimately driving higher revenue and sustainable business growth.


