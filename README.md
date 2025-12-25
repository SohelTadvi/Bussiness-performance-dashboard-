Business Performance Dashboard
Overview
This project demonstrates an end-to-end data analytics workflow to analyze business performance using a consolidated master dataset. The goal is to derive insights on revenue, profit, growth trends, category performance, regional sales, and top customers, and visualize them through an interactive dashboard.
Project Objective
Analyze overall revenue and profit trends
Identify top-performing categories and regions
Understand customer contribution and growth
Build a dashboard for business decision support
Dataset
The project uses a master CSV file created by combining multiple datasets:
Monthly sales data
Category-wise revenue data
Region-wise revenue data
Top customer performance data
Each record contains:
Month, Category, Region, Customer, Revenue_USD, Profit_USD, Customer_Growth_Percent
Tools and Technologies
Python (Pandas) for data preparation
CSV files for data storage
Power BI / Excel for dashboard visualization
Project Structure
master_dashboard_data.csv – consolidated dataset
notebooks/ – data preparation and analysis scripts
dashboard/ – Power BI or Excel dashboard file
README.md – project documentation
Steps Followed
Collected and created raw datasets for sales, categories, regions, and customers
Cleaned and transformed data using Python
Merged datasets into a master CSV file
Performed exploratory data analysis
Built an interactive dashboard to visualize KPIs and trends
Key Insights
Revenue and profit trends across months
Category-wise contribution to total sales
Regional performance comparison
Top customers driving business growth
Results
The final output is an interactive dashboard showing KPIs such as total revenue, total profit, growth percentage, and detailed breakdowns by month, category, region, and customer.
