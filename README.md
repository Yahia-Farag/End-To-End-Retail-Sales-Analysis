# 🛒 Retail Store Sales Data Cleaning & Business Analytics

A comprehensive, end-to-end retail store data auditing, cleaning, and multi-dimensional business intelligence project using **T-SQL (SQL Server)** and **Power BI**.

---

## 📂 Repository Structure & Project Files

This repository contains all necessary resources to run, review, and interact with the project:

* 📊 **Interactive Power BI Report:** [`Retail Stores Sales Analytics.pbix`](./Retail%20Stores%20Sales%20Analytics.pbix) *(Download & open in Power BI Desktop for full interactivity)*
* 📜 **SQL Cleaning Script:** [`retail_store_sales_cleaning.sql`](./retail_store_sales_cleaning.sql) *(T-SQL script for data auditing, cleaning, and transformation)*
* 🖼️ **Executive Dashboards:** High-resolution preview screenshots included below.

---

## 📌 Project Overview
Retail operations handle diverse product categories, customer interactions, and payment methods that require strict data cleaning and deep performance tracking. This project executes a robust T-SQL cleaning pipeline (`retail_store_sales_cleaning.sql`), followed by a rich, multi-page Power BI analytical dashboard suite to monitor revenue streams, category performance, payment preferences, and top customers.

---

## 📊 Dashboard Preview

Below are high-resolution snapshots of the interactive **Power BI** dashboard pages:

### 1️⃣ Sales & Category Performance
- **Core KPIs:** Total Revenue ($1.55M), Avg Total Spent (129.65), and Highest Order Value (410).
- **Category Breakdown:** Comprehensive ranking led by Butchers (208.12K), Electric household essentials (203.81K), Beverages (197.05K), and Furniture (195.31K).
- **Temporal & Discount Analysis:** Monthly revenue distributions and spending behaviors categorized by discount status (Applied, Not Applied, Not Recorded).

![Retail Store Dashboard 1](./Retail%20Store%20Dashboard%201.png)

---

### 2️⃣ Payment Methods & Operations
- **Operational Metrics:** 8 Categories, 66.28K Total Quantity, and 12.58K Number of Orders.
- **Payment Breakdown:** Revenue distribution across Cash (537.71K), Digital Wallet (507.28K), and Credit Card (507.08K), alongside order counts and average order values per payment method.

![Retail Store Dashboard 2](./Retail%20Store%20Dashboard%202.png)

---

### 3️⃣ Customer Demographics & Trends
- **Customer Base:** 25 Total Customers.
- **Top Performers:** Detailed ranking of top 5 customers by revenue (led by CUST_08 at 7.26K) and multi-year revenue trends from 2022 to 2024.

![Retail Store Dashboard 3](./Retail%20Store%20Dashboard%203.png)

---

## 🛠️ Technologies Used
- **SQL Server (T-SQL):** Database scripts, data cleaning, and data integrity validation via `retail_store_sales_cleaning.sql`.
- **Power BI Desktop:** Multi-page interactive dashboarding, dynamic slicers (Year, Month, Quarter), and retail performance modeling.
- **Git & GitHub:** Version control, structured repository organization, and professional documentation.

---

## 🚀 How to Run & Use
1. **Clone or Download:** Clone this repository to your local machine.
2. **Database Setup:** Import the underlying raw retail dataset into your SQL Server database.
3. **Execute Cleaning Pipeline:** Run the [`retail_store_sales_cleaning.sql`](./retail_store_sales_cleaning.sql) script sequentially to audit and clean the data.
4. **Interactive Dashboard:** Download and open the [`Retail Stores Sales Analytics.pbix`](./Retail%20Stores%20Sales%20Analytics.pbix) file in **Power BI Desktop** to explore the visualizations and interact with dynamic slicers.
