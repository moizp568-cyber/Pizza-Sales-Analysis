roject Overview
The goal of this project is to analyze the sales data of a pizza shop to understand customer preferences, peak hours, and revenue drivers. It covers:

KPI Tracking: Revenue, Average Order Value, Total Pizzas Sold.

Sales Trends: Daily and Monthly order patterns.

Category Analysis: Performance of different pizza categories and sizes.

Best/Worst Sellers: Top 5 and Bottom 5 pizzas based on revenue and quantity.

🛠️ Tech Stack
SQL: Used for data extraction and calculating KPIs.

Visualization: Power BI / Tableau (as seen in the dashboard screenshot).

Database: SQL Server / MySQL.

📊 Key Insights (KPIs)
Based on the SQL queries, the following metrics were calculated:

Total Revenue: The sum of the total price of all orders.

Average Order Value: The average amount spent per order.

Total Pizzas Sold: Total quantity of all pizzas sold.

Average Pizzas Per Order: Average number of pizzas included in a single order.

🔍 SQL Queries Included
The project includes several SQL scripts to answer business questions:

Daily & Monthly Trends: Identifying peak days (e.g., weekends) and months for orders.

Percentage of Sales: Breakdown of revenue by pizza category and size.

Inventory Performance: Top 5 and Bottom 5 selling pizzas to help in inventory management.

Example Query (Total Revenue):

SQL

SELECT SUM(total_price) AS Total_Revenue FROM pizza_sales;
📈 Dashboard Preview
Note: Add your dashboard image to the repository and update the link above.

📂 Project Structure
Pizza_Sales_Queries.sql: Contains all the SQL scripts for data analysis.

Pizza_Sales_Report.pdf: (Optional) If you have a PDF export of your dashboard.

Data/: Folder containing the raw dataset (if available).

🚀 How to Use
Clone this repository.

Import the dataset into your SQL Server/Database.

Run the queries provided in the .sql file to see the results.

Open the visualization file (Power BI/Tableau) to view the interactive dashboard.
