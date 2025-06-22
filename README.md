**Sales Performance Dashboard (Excel Project)**
A dynamic and interactive Excel dashboard project designed to track sales metrics, monitor regional and product performance, and support strategic business decisions through real-time insights and automation.

**Project Overview**
This project demonstrates the end-to-end development of a sales performance dashboard using Microsoft Excel. From raw data preprocessing to insight-driven visualizations, the dashboard empowers users to explore key business KPIs with ease.

**Objectives**
•	Clean and structure raw sales data
•	Engineer new metrics such as age group revenue and profit.
•	Visualize trends and performance using pivot tables and charts
•	Enable interactive data exploration using slicers
•	Deliver actionable business insights to decision-makers

**Data Source**
Client-provided transactional sales data including fields such as:
•	Transaction Date
•	Product Category
•	Region
•	Salesperson
•	Quantity Sold
•	Unit Price
•	Unit Cost

**Data Preprocessing**
To ensure data integrity and analysis accuracy, the following cleaning steps were applied:
1. Whitespace Trimming
Used TRIM() function to clean unnecessary spaces in text fields like Region, Category, and Salesperson, preventing grouping errors in pivot tables.
2. Duplicate Removal
Removed duplicate entries using Excel’s built-in Remove Duplicates feature, primarily in transaction ID and customer data columns.
3. Missing Value Imputation
•	For categorical columns (e.g., Region, Product), replaced missing values with the mode.
•	For numerical columns (e.g., Quantity, Price), used the median to replace missing entries and reduce outlier bias.

**Feature Engineering**
New fields were created to enhance the dataset and support key business metrics:
•	Revenue = Quantity × Unit Price
•	Cost = Quantity × Unit Cost
•	Profit = Revenue - Cost
•	Profit Margin = Profit ÷ Revenue
•	Sales Month = Extracted from the date using TEXT(Date, "mmm-yyyy") for time series analysis

**Data Analysis & Dashboarding**
1. Pivot Tables
•	Aggregated sales metrics by Region, Product Category, Month, and Salesperson
•	Enabled fast drill-down analysis without complex formulas
2. Slicers
•	Integrated slicers for Date, Region, Product Category, and Sales Rep
•	Enabled dynamic filtering for user-friendly exploration
3. Conditional Formatting
•	Used data bars, icon sets, and color scales to highlight top/bottom performance
4. KPI Cards
•	Highlighted Total Sales, Profit, Sales Growth %, and Average Order Value
5. Charts & Visuals
•	Line charts for sales trends over time
•	Bar charts for region-wise and product-wise comparison
•	Doughnut chart for profit distribution by gender

**Actionable Insights**
The dashboard uncovered critical trends and patterns:
•	(Quarters of the year): Q2 outperformed Q1 by 22% in revenue growth
•	Western region underperformed by 18% – triggered targeted promotions
•	 Product Line B generated 35% of total sales, indicating customer preference
•	 Top 3 sales reps were responsible for 60% of revenue – performance recognized and rewarded
•	Weekend sales dropped significantly – led to adjusted staffing and marketing schedules
•	Generally, customers tend to opt for online transactions compared to POS and cash transactions
•	In 2016, profit generally spiked showing seasonality around January and in June.
Tools & Technologies
•	Microsoft Excel: Pivot Tables, Slicers, Conditional Formatting, Charts
•	Excel Functions: TRIM(), IF(), VLOOKUP(), SUMIFS(), INDEX MATCH, COUNTIF(), TEXT()
Outcome
Delivered a powerful Excel dashboard that transformed raw data into actionable business insights. The tool is intuitive, refreshable, and accessible to both technical and non-technical users, enhancing strategic planning and daily decision-making.

**Project Files**
•	Sales_Performance_Dashboard.xlsx – Cleaned data + Dashboard
•	Sales_Performance_Dashboard_Full_Project.pptx – Presentation Slides
•	README.md – Project documentation
________________________________________
Let’s Connect
**Samuel Oluwakemi Olotu**
 Coventry, UK
 oolotusamuel@gmail.com , LinkedInhttps://www.linkedin.com/in/olotu-samuel/



