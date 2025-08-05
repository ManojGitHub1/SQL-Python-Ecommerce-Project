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
