# 📊 Superstore SQL Analysis 

## 📌 Project Overview 
This project analyzes the **Superstore Dataset** using **SQL Server**. 
The aim is to derive meaningful business insights with **advanced SQL queries** such as: 
- Total Sales & Profit trends 
- Top & second-highest performing products 
- Customer purchase behavior 
- Shipping performance 

---

## 🗂 Dataset 
Dataset Source: [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) 

---

## 🔑 Key SQL Concepts Used 
- **CTEs & Subqueries** – reusable query blocks 
- **Window Functions** – RANK, ROW_NUMBER, NTILE, LAG
- **Aggregations** – SUM, COUNT, AVG, GROUP BY 
- **Joins** – combining multiple tables 
- **Filtering & Sorting** – advanced WHERE + ORDER BY 

---

## 📂 Files 
- [Analysis.sql](Analysis.sql) → All queries used for analysis 

---

## 📷 Query Outputs 

**1️⃣ Total Sales & Profit by Category** ![Total Sales and Profit by Category](q1_sales_profit_by_category.png) 

**2️⃣ Top 5 Profitable Customers** ![Top 5 Profitable Products](q2_top5_customers_profit.png) 

**3️⃣ Monthly Sales Trend** ![Monthly Sales Trend](q3_monthly_sales_trend.png) 

**4️⃣ Profit by Region** ![Profit by Region](q4_profit_by_region.png) 

**5️⃣ Top 5 Products by Quantity Sold** ![Top 5 Products by Quantity Sold](q5_top5_products_quantity.png) 

**6️⃣ Top 5 Customers by Total Sales** ![Top 5 Customers by Total Sales](q6_top5_customers_sales.png) 

**7️⃣ Monthly Sales Trend** ![Monthly Sales Trend](q7_monthly_sales_trend.png) 

**8️⃣ Year-over-Year (YoY) Growth in Sales** ![Year-over-Year Growth in Sales](q8_yoy_sales_growth.png) 

**9️⃣ Top 5 Customers by Total Profit** ![Top 5 Customers by Total Profit](q9_top5_profitable_products.png) 

**🔟 Loss-Making Products** ![Loss-Making Products](q10_loss_making_products.png) 

**1️⃣1️⃣ Regional Performance with Ranking** ![Regional Performance with Ranking](q11_regional_performance_rank.png) 

**1️⃣2️⃣  Customer Segmentation** ![Customer Segmentation](q12_customer_segmentation.png) 

**1️⃣3️⃣  Shipping Speed Impact on Profit** ![Shipping Speed Impact on Profit](q13_shipping_speed_profit.png)  

**1️⃣4️⃣  Top 3 Customers in Each Region** ![Top 3 Customers in Each Region](q14_top3_customers_region.png) 

**1️⃣5️⃣  Second Highest Sales per Region** ![Second Highest Sales per Region](q15_second_highest_sales_region.png) 

**1️⃣6️⃣ Second Highest Product By Sales** ![Second Highest Product By Sales](q16_second_highest_product_sales.png) 

---

## 🛠️ Tech Stack 
- SQL Server 2019 
- Superstore Dataset 
- GitHub for version control 

---


## 🚀 How to Use
1. Clone this repository
    ```bash
    git clone [https://github.com/your-username/Superstore-SQL-Analysis.git](https://github.com/your-username/Superstore-SQL-Analysis.git)
    ```
2. Import the Superstore Dataset into a SQL Server database.
3. Run the queries from the `Analysis.sql` file to reproduce the results.
