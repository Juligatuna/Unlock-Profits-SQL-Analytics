# Unlock Profits SQL Analytics

A project that cleans, analyzes, and visualizes e-commerce and finance data using **SQL + Python**.  
The aim is to unlock business insights from sales, expenses, stock, and international trade reports.

---
```bash

## 🧰 Repository Structure

Unlock-Profits-SQL-Analytics/
├── data/ # Raw CSV files
├── notebooks/ # Jupyter notebooks with SQL + pandas analysis
├── requirements.txt # Python dependencies
└── README.md # Project overview

```
---

## 🚀 What’s Inside

This project integrates multiple data sources:

- **amazon_sale_report** → Orders, fulfillment, courier status, promotions  
- **sale_report** → SKU-level stock & sales  
- **international_sale_report** → Global sales with amounts and rates  
- **may_2022** & **p_l_march_2021** → Product pricing across platforms (Amazon, Flipkart, Myntra, etc.)  
- **expense_iigf** → Expenses vs received amounts  
- **cloud_warehouse_compersion_chart** → Logistics/warehousing comparisons  

We join, query, and visualize these datasets to answer questions like:  

- Which categories and SKUs drive the most revenue?  
- How do international vs domestic sales compare month-to-month?  
- Which sales channels have the highest profitability?  
- How does stock availability affect order fulfillment?  
- Where are the hidden costs (expenses vs revenue)?  

---

## 🧪 How to Run It

1. Clone this repo:
   ```bash
   git clone https://github.com/Juligatuna/Unlock-Profits-SQL-Analytics.git
   cd Unlock-Profits-SQL-Analytics

Install Python dependencies:

pip install -r requirements.txt


Ensure MySQL is running, and create the database:

CREATE DATABASE unlock_profits;


Run the Jupyter notebooks:

Upload CSVs into MySQL using pandas.to_sql

Run provided SQL queries

Generate visualizations with pandas, matplotlib, seaborn

📊 Example Outputs

📈 Sales trends by month and category
🗺️ State-wise and country-wise order heatmaps

🏷️ SKU profitability analysis

🚚 Courier performance visualization

📦 Stock vs sold quantity comparisons

🔧 Dependencies

Python 3.x

MySQL

Libraries: pandas, sqlalchemy, pymysql, matplotlib, seaborn, jupyter

🙋 Author

Julius Irungu
🔗 www.linkedin.com/in/julius-irungu-344519a8