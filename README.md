Customer Churn and Returns Analysis using SQL
📖 Overview

This project focuses on analyzing customer churn and return transactions for an e-commerce company using MySQL.
The goal is to identify churn patterns, customer complaints, and refund trends to improve customer retention strategies.

⚙️ Key Features

Cleaned and joined multiple customer and returns tables.

Filtered churned customers who raised complaints.

Calculated refund amounts and identified high-churn categories.

Generated actionable insights for business improvement.

🗂️ Tools & Technologies

MySQL

SQL Joins & Aggregate Functions

Data Cleaning & Query Optimization

📊 Sample Query
SELECT 
  c.CustomerID, 
  c.CustomerName, 
  r.ReturnID, 
  r.RefundAmount
FROM customer_churn c
JOIN customer_returns r 
  ON c.CustomerID = r.CustomerID
WHERE c.ChurnStatus = 'Churned';

📈 Insights

Most churned customers had pending complaints or refund issues.

Electronics and Fashion categories showed higher churn rates.

👩‍💻 Author

Arul Jothi
(Data Enthusiast | SQL | Excel | Power BI)
