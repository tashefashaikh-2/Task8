Task Objective
Create a clean and interactive dashboard using Power BI or Tableau that visualizes sales performance by:
Month
Region
Category

The dashboard must include:
✔ Line chart – Sales over months
✔ Bar chart – Sales by region
✔ Donut chart – Sales by category
✔ Slicer for region or category
✔ 3–4 written insights

Tools Used
Power BI Desktop (data visualization & dashboard)

Dataset Used
Sample - Superstore.csv
Contains:
Order Date, Ship Date
Region, State, City
Category, Sub-Category
Sales, Profit, Quantity, Discount
Customer Details

Steps Performed
1. Data Import
Loaded the Superstore dataset into Power BI.

2. Data Cleaning
Converted Order Date to proper date format
Created a new calculated column for Month-Year:
MonthYear = FORMAT([Order Date], "MMM YYYY")

3. Dashboard Visuals
Line Chart: Sales by Month-Year
Bar Chart: Sales by Region
Donut Chart: Sales by Category
Slicer: Added category/region filter

4. Formatting
Applied consistent theme
Added titles and labels
Adjusted layout for clear readability

Key Insights from Dashboard
West Region leads in sales, contributing over $725K, making it the strongest-performing region.
Technology is the top-selling category, generating more than $836K in revenue.
November shows the highest sales, especially in 2017, indicating a strong holiday season trend.
Year-end months (Sep–Dec) consistently show high sales, confirming seasonal demand spikes.

Files Inclued:
This GitHub repository contains:
PDF of the Dashboard
Power Bi file
Insights text file
Dataset used
README.md (this file)
