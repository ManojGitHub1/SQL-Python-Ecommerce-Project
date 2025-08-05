# 📊 E-Commerce Sales Analysis using MySQL Connector and Python

This project presents an end-to-end data analysis workflow that integrates **MySQL Connector with Python** in a **Jupyter Notebook environment**, enabling direct interaction with a live SQL database to perform complex business analytics. The project focuses on uncovering key sales, customer, and product insights for a fictional e-commerce platform.

---

## 🚀 Project Overview

- Connected Jupyter Notebook to a **MySQL database** using `mysql-connector-python`, allowing dynamic querying and real-time data retrieval.
- Extracted and analyzed raw transactional data to derive meaningful business insights.
- Visualized findings using **Pandas**, **Seaborn**, and **Matplotlib** to support strategic decision-making in product, sales, and customer domains.

---

## 💡 Business Questions Answered

The following business questions were explored and answered with the help of SQL + Python:

- 🏆 Who are the top customers by yearly revenue?
- 📅 What are the monthly sales patterns throughout the year?
- 🛍️ How is sales revenue distributed across different product categories?
- 🎯 Which sellers are leading in revenue generation?
- 📈 What’s the trend in customer orders over time?
- 🔁 How loyal are customers (retention rate within 6 months)?
- 🧠 How has revenue grown year-over-year?

---

## 🛠️ Tools & Technologies Used

| Category             | Tools/Tech                          |
|----------------------|--------------------------------------|
| Database             | MySQL                               |
| Language             | Python 3.x                           |
| IDE                  | Jupyter Notebook                    |
| DB Connector         | mysql-connector-python              |
| Data Handling        | Pandas                              |
| Data Visualization   | Seaborn, Matplotlib                 |
| Version Control      | Git, GitHub                         |

---

## 📂 Project Structure

```bash
E-commerce Sales/
│
├── E-commerce Sales.ipynb      # Main Jupyter Notebook with all code
├── dataset_link.txt            # Dataset link (kaggle)
├── Questions.txt               # Questions for analysis
├── csv_to_sql.py               # CSV to Sql logic
└── README.md                   # Project documentation
```

---

## 🔍 Query Breakdown
### 🧾 Basic SQL Queries
1. List all unique cities where customers are located
2. Count the number of orders placed in 2017
3. Find the total sales per product category
4. Calculate the percentage of orders paid in installments
5. Count the number of customers from each state

### 📊 Intermediate SQL Queries
1. Orders per month in 2018
2. Avg. number of products per order by customer city
3. % Revenue by product category
4. Correlation between product price and frequency of purchase
5. Seller-wise revenue with ranking

### 📈 Advanced SQL Queries
1. Moving average of order values per customer over time
2. Cumulative monthly sales
3. YoY growth rate of total revenue
4. Customer retention within 6 months
5. Top 3 high-spending customers per year

## 📸 Visualizations Created
1. Revenue vs. Time Line Chart
2. Category-wise Sales Bar Charts
3. Top Sellers and Top Customers Ranking
4. Installment vs. Full-Payment Order Breakdown
5. Cumulative Revenue Heatmaps
6. Retention Funnels and Year-over-Year Growth Trends

## 📌 Key Learnings
- Seamlessly integrated SQL querying within Python using MySQL Connector.
- Combined SQL logic with Python-based analytics for better flexibility and scalability.
- Strengthened business storytelling using data visualization tools in Python.
- Gained deeper understanding of customer retention, sales behavior, and revenue patterns.

## 🙌 Acknowledgements
Special thanks to WsCube Tech and Ayushi Jain for providing high-quality tutorials and learning content that helped structure and guide this project.
