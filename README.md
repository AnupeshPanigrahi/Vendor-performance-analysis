# 📊 Vendor Performance Analysis


# 📌 Project Overview

Vendor Performance Analysis is an end-to-end data analytics project that transforms raw purchasing and sales data into meaningful business insights.

The project demonstrates the complete analytics workflow—from data ingestion and database creation to SQL-based analysis, exploratory data analysis (EDA), KPI generation, and Power BI dashboard development.

This project is designed to help organizations identify high-performing vendors, optimize procurement strategies, improve profitability, and reduce operational costs.

---

## ✨ Features

-  Automated Data Ingestion
-  SQLite Database Creation
-  SQL-Based Data Analysis
-  Data Cleaning & Transformation
-  Exploratory Data Analysis (EDA)
-  KPI Calculation
-  Vendor Profitability Analysis
-  Interactive Power BI Dashboard
-  Business Report Generation
---

## 🛠️ Tech Stack

1. **Programming Language:** Python
2. **Database:** SQLite
3. **Libraries:**
   - Pandas
   - SQLAlchemy
   - SQLite3
   - Logging
4. **Visualization:** Power BI
5. **Notebook:** Jupyter Notebook

---

# 📂 Project Structure

```text
Vendor-Performance-Analysis/
│
├── 📁 Data/
│   ├── Purchases.csv
│   ├── Sales.csv
│   ├── VendorInvoice.csv
│   └── ...
│
├── 📓 Vendor Performance Analysis.ipynb
├── 📓 Exploratory Data Analysis.ipynb
├── 🐍 ingestion_db.py
├── 🐍 get_vendor_summary.py
├── 🗄 inventory.db
├── 📄 vendor_sales_summary.csv
├── 📊 vendor_performance.pbix
├── 📑 Vendor Performance Report.pdf
└── README.md
```

---

# 🔄 Project Workflow

1.Load raw CSV files.
2.Store datasets in a SQLite database.
3.Merge purchase, sales, invoice, and pricing data using SQL queries.
4.Clean missing values and standardize the data.
5.Calculate business KPIs.
6.Export the vendor summary.
7.Visualize insights in Power BI.
```

---

# 📊 Dashboard Preview

- Power BI Dashboard shows:
  - Vendor-wise Sales and Margins
  - Inventory Turnover
  - Bulk Purchase Savings
  - Performance Heatmaps

![Vendor Performance Dashboard](./Image/dashboard.png)

---

# 📈 Key Performance Indicators (KPIs)

* 💰 Total Purchase Amount
* 📦 Purchase Quantity
* 🛒 Total Sales Revenue
* 📈 Gross Profit
* 💵 Profit Margin (%)
* 🚚 Freight Cost
* 📊 Sales vs Purchases
* 📦 Inventory Turnover
* ⭐ Top Vendors
* 📉 Low Performing Vendors

---

---

# ▶️ How to Run

1. Clone the repository
git clone https://github.com/AnupeshPanigrahi/Vendor-performance-analysis
2. Install dependencies
pip install pandas sqlalchemy
3. Load data into SQLite
python ingestion_db.py
4. Generate vendor summary
python get_vendor_summary.py
5. Open the dashboard
Open the vendor_performance.pbix file using Microsoft Power BI Desktop.

# 📊 Analytics Pipeline

```text
CSV Files
   │
   ▼
Python ETL
   │
   ▼
SQLite Database
   │
   ▼
SQL Queries
   │
   ▼
Pandas Analysis
   │
   ▼
EDA Notebook
   │
   ▼
Power BI Dashboard
```

---

# 📷 Sample Output

```
✔ Database Created

✔ Data Loaded Successfully

✔ Vendor Summary Generated

✔ CSV Exported Successfully

✔ Dashboard Ready
```

---

# 🚀 Future Improvements

* Cloud Database Integration
* Streamlit Dashboard
* Machine Learning Vendor Prediction
* Automated ETL Pipeline
* Scheduled Reports
* Power BI Service Deployment
* REST API Integration
* Docker Containerization

---

# 💼 Skills Demonstrated

* Python Programming
* SQL
* SQLite
* Data Cleaning
* Exploratory Data Analysis
* Business Intelligence
* Data Visualization
* ETL Pipeline Development
* KPI Design
* Power BI
* Problem Solving

---

# 🎯 Resume Impact

This project demonstrates practical experience in:

* End-to-End Data Analytics
* Business Intelligence Reporting
* Database Management
* SQL Query Optimization
* Python Automation
* Data Visualization
* Business KPI Development

---

# 👨‍💻 Author

**Anupesh Panigrahi**

🎓 B.Tech (Computer Science & Engineering)

📊 Aspiring Data Analyst | Business Intelligence | Python | SQL | Power BI

🔗 GitHub: https://github.com/YOUR_USERNAME

🔗 LinkedIn: https://linkedin.com/in/anupeshpanirahi

---


---

# 📄 License

This project is licensed under the MIT License.

---

<div align="center">

### ⭐ Thank you for visiting this repository!

**Happy Learning! 🚀**

</div>
