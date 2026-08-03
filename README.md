# 🌸 FNP Sales Analysis Dashboard

An end-to-end **Data Analytics project** built in **Microsoft Excel** to analyze sales performance for **Ferns and Petals (FNP)**. This project follows a real-world analytics workflow—from **data extraction and transformation** to **data modeling, business analysis, and dashboard creation**—using **Power Query, Power Pivot, DAX, PivotTables, and interactive Excel dashboards**.

---
<img width="1410" height="560" alt="Screenshot 2026-08-03 at 6 43 54 AM" src="https://github.com/user-attachments/assets/14be281b-9535-4f50-b195-91b1b25bfbed" />

---
## 📖 Project Overview

Ferns and Petals (FNP) is a gifting company that specializes in delivering gifts for occasions such as **Anniversaries, Birthdays, Valentine's Day, Diwali, Holi, and Raksha Bandhan**.

The goal of this project is to transform raw sales data into meaningful business insights that help stakeholders understand:

- Revenue performance
- Customer purchasing behavior
- Product performance
- Seasonal sales trends
- Delivery efficiency
- Regional sales distribution

The final outcome is an **interactive Excel dashboard** that enables users to explore sales data using slicers and timelines.

---

## 🎯 Business Problem

The analysis addresses the following business questions:

- What is the total revenue generated?
- What is the average order-to-delivery time?
- How do monthly sales fluctuate throughout the year?
- Which products generate the highest revenue?
- How much does an average customer spend?
- Which product categories perform the best?
- Which cities place the highest number of orders?
- Does order quantity impact delivery time?
- Which occasions generate the highest revenue?
- Which products are most popular during different occasions?

---

# 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query (ETL)
- Power Pivot
- DAX (Data Analysis Expressions)
- Pivot Tables
- Pivot Charts
- Excel Data Model
- Slicers & Timelines
- CORREL Function (Statistical Analysis)

---

# 🔄 Project Workflow

## 1️⃣ Business Understanding

- Reviewed the project problem statement.
- Explored the Customers, Orders, and Products datasets.
- Identified key business objectives and performance metrics.

---

## 2️⃣ Data Extraction (ETL)

Using **Power Query**:

- Imported multiple CSV files using **From Folder**.
- Loaded Customers, Orders, and Products as separate queries.

---

## 3️⃣ Data Cleaning

Performed data quality checks by:

- Profiling columns
- Checking missing values
- Detecting duplicate records
- Identifying errors
- Correcting data types

---

## 4️⃣ Data Transformation

Created new business-friendly features such as:

- Month Name
- Order Hour
- Delivery Hour
- Delivery Days (Delivery Date − Order Date)

Merged the **Products** table with **Orders** using **Product ID** to include product prices.

---

## 5️⃣ Data Modeling

Built a **Star Schema** using **Power Pivot**.

### Fact Table

- Orders

### Dimension Tables

- Customers
- Products

Established relationships using primary and foreign keys.

---

## 6️⃣ DAX Calculations

Created calculated columns using DAX:

- Revenue = Price × Quantity
- Day Name using `FORMAT()`

---

## 7️⃣ Data Analysis

Developed Pivot Tables to analyze:

- Total Revenue
- Average Delivery Time
- Monthly Sales Performance
- Revenue by Category
- Revenue by Occasion
- Top Products by Revenue
- Top Cities by Number of Orders
- Average Customer Spending

Performed statistical analysis using the **CORREL** function to study the relationship between:

- Order Quantity
- Delivery Time

---

## 8️⃣ Interactive Dashboard

Designed an interactive Excel dashboard featuring:

### KPI Cards

- Total Revenue
- Total Orders
- Average Delivery Time
- Average Customer Spend

### Visualizations

- Revenue by Occasion
- Revenue by Category
- Revenue by Month
- Top Products by Revenue
- Top Cities by Orders
- Revenue by Order Hour

### Interactive Filters

- Order Date Timeline
- Delivery Date Timeline
- Occasion Slicer

---

## 9️⃣ Dashboard Design

Applied professional dashboard design principles:

- Consistent color theme
- FNP branding
- KPI cards
- Interactive slicers
- Clean layout
- Professional formatting

---

## 🔟 Documentation & Portfolio

Prepared supporting project assets:

- Executive Summary
- Dashboard Screenshot
- GitHub Repository
- Project Documentation

---

# 📈 Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| 💰 Total Revenue | Overall sales generated |
| 📦 Total Orders | Number of customer orders |
| 🚚 Average Delivery Time | Average delivery duration |
| 👤 Average Customer Spend | Average revenue per customer |

---

# 📁 Repository Structure

```text
FNP-Sales-Analysis/
│
├── Dataset/
│   ├── customers.csv
│   ├── orders.csv
│   └── products.csv
│
├── sales_dashboard.png
├── FNP_Analysis.xlsx
├── Ferns and Petals Sales Analysis.pdf
├── Executive Summary.pdf
└── README.md
```

---

# 💼 Skills Demonstrated

- Data Cleaning
- Data Transformation
- ETL using Power Query
- Data Modeling
- Star Schema Design
- Power Pivot
- DAX
- Pivot Tables
- Pivot Charts
- Dashboard Design
- KPI Development
- Data Visualization
- Business Analysis
- Statistical Analysis
- Interactive Reporting
- Documentation

---

# 📂 Project Deliverables

- ✅ Raw Datasets
- ✅ Excel Workbook
- ✅ Interactive Dashboard
- ✅ Dashboard Screenshot
- ✅ Problem Statement
- ✅ Executive Summary
- ✅ README Documentation

---

# 🎓 Learning Outcomes

This project provided hands-on experience in:

- Performing ETL using Power Query.
- Cleaning and transforming raw business data.
- Designing a Star Schema with Power Pivot.
- Writing DAX calculations for business metrics.
- Building interactive dashboards using Pivot Tables, Charts, Slicers, and Timelines.
- Performing statistical analysis using Excel functions.
- Communicating insights through executive summaries and portfolio-ready documentation.

---

# 👤 Author

**Suyog Yadav**

---

## ⭐ If you found this project helpful, consider giving this repository a star!
