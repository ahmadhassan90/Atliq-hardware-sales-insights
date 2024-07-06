# Atliq-hardware-sales-insights
Atliq Hardware Sales Report uses Tableau &amp; MySQL to visualize sales data across Indian regions. The interactive dashboard showcases metrics like revenue, sales per region, top products, and customers, with filters for yearly insights. It enables informed decision-making to boost sales strategy and market performance.
# Atliq Hardware Sales Report Project

Welcome to the Atliq Hardware Sales Report Project! This project aims to provide insightful visualizations of sales data to identify regions with declining sales and analyze overall sales performance. Leveraging Tableau and MySQL, this project transforms raw data into meaningful insights.

## Project Overview

The dataset, provided by Atliq Hardware, has been meticulously cleaned and processed to ensure accurate and actionable visualizations. The Tableau dashboard showcases various sales metrics, offering a comprehensive view of the company’s sales landscape.

## Project Files

- `atliq_db.sql`: SQL script containing the cleaned data, including table creation and data insertion commands.
- `Atliq Hardware Sales Report.twbx`: Tableau workbook featuring interactive and insightful visualizations.

## Requirements

- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
- [Tableau Desktop](https://www.tableau.com/products/desktop)

## Setup Instructions

### Step 1: Setting Up the MySQL Database

1. **Open MySQL Workbench**: Launch MySQL Workbench on your machine.
2. **Create a New Database**: Create a new database to store Atliq Hardware’s sales data.
3. **Run SQL Script**: Execute the `atliq_db.sql` script to create the necessary tables and insert the cleaned data.
   - Open MySQL Workbench.
   - Navigate to the "File" menu and select "Open SQL Script".
   - Locate and open `atliq_db.sql`.
   - Execute the script to set up the database.

### Step 2: Setting Up Tableau

1. **Open Tableau Desktop**: Launch Tableau Desktop on your machine.
2. **Open the Tableau Workbook**: Open the `sales_report.twbx` file.
3. **Connect to MySQL Database**:
   - Go to the "Data" menu and select "Connect to Data".
   - Choose "MySQL" as the connection type.
   - Enter your MySQL server details and the database name you created earlier.
   - Click "Sign In" to establish the connection.

## Dashboard Features

The Tableau dashboard offers the following insights:

- **Total Revenue**: Overall revenue generated.
- **Total Sales**: Total number of sales transactions.
- **Revenue per Market (Area/Region)**: Revenue distribution across different markets.
- **Sales Quantity per Market**: Sales quantities categorized by market regions.
- **Top 5 Sale Products**: The five highest-selling products.
- **Top 5 Customers**: The five customers with the highest sales.
- **Yearly Filters**: Dynamic filters to view data for specific years.

## Insights and Analysis

This project provides a detailed analysis of sales performance, highlighting key areas such as top-performing products and customers, as well as regions with declining sales. The dashboard enables stakeholders to make data-driven decisions to optimize sales strategies and improve market performance.

---

We hope this project provides valuable insights and helps in driving informed decisions for Atliq Hardware. For any queries or further assistance, please feel free to reach out.
