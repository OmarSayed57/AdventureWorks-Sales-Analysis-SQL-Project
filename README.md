# AdventureWorks Sales Performance & Trend Analysis

**Author:** Omar Mohsen Sayed Hanafi | SQL Server Data Analyst

## 📌 Project Overview
This project analyzes the Adventure Works Cycles OLTP database to define and calculate 5 core Sales Key Performance Indicators (KPIs). The goal is to assess financial health, customer behavior, and product performance using advanced T-SQL techniques, including window functions for year-over-year (YoY) trend analysis.

## 🛠️ Data Source & Tools
* **Data Source:** Microsoft SQL Server AdventureWorks2022 OLTP Sample Database.
* **Tools Used:** T-SQL, SQL Server Management Studio (SSMS).

## 🔑 Key Deliverables: 5 Sales KPIs
This project focuses on calculating the following five core KPIs to assess the health and performance of sales operations:

| KPI Name | Business Relevance |
| :--- | :--- |
| **1. Total Sales Revenue** | The **absolute measure of financial performance** and the overall scale of the business. A high value indicates strong market demand. |
| **2. Average Order Value (AOV)** | Measures the **average dollar amount spent per transaction**. It's key to evaluating customer buying habits and the success of upselling/cross-selling strategies. |
| **3. Revenue by Sales Territory** | Breaks down the total revenue contribution by each geographic market. It is vital for **assessing regional performance** and allocating sales resources effectively. |
| **4. Top 10 Bestselling Products** | Identifies the products that are purchased most frequently. This is **crucial for inventory management** and prioritizing production/marketing efforts. |
| **5. Year-over-Year (YoY) Revenue Trend** | Measures the percentage growth or decline of sales compared to the same month in the previous year. It provides a clean measure of **long-term business growth** by removing seasonal effects. |

## ⚙️ How to Run the Analysis
To execute the T-SQL script and reproduce the analysis, you need a running SQL Server instance with the AdventureWorks database restored.

### Step 1: Download the Database Backup
Obtain the official Microsoft SQL Server **AdventureWorks2022 OLTP** database backup file (`.bak`) from the official Microsoft SQL Server samples page.

### Step 2: Restore the Database in SQL Server
1. Move the downloaded `.bak` file to your default SQL Server backup directory.
2. Connect to your SQL Server instance using **SQL Server Management Studio (SSMS)**.
3. Right-click the **Databases** folder -> **Restore Database...** -> Select **Device** -> Add your downloaded `.bak` file.
4. Ensure the target database name is set to `AdventureWorks2022` and click **OK**.

### Step 3: Run the SQL Script
1. Open SSMS and connect to your server.
2. Open the `AdventureWorks_Sales_KPI_Script.sql` file provided in this repository.
3. Execute the entire script. The output will display the results of all five KPI queries in separate result sets.
