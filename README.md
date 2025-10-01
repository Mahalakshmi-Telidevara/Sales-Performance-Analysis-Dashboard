# Sales Performance Analysis Dashboard

This project was done as part of my internship at **Besant Technologies**.  
The goal was to analyze **5000 sales records** using **ETL (Extract, Transform, Load)** and create an interactive dashboard in **Power BI**.

---

## 📊 Project Overview
- **Dataset**: 5000 Sales Records
- **Process**: 
  1. **Extract** – Imported sales data from CSV file.
  2. **Transform** – Cleaned and processed the dataset:
     - Removed duplicates & missing values
     - Converted data types (dates, currencies)
     - Created calculated columns (Profit, Revenue, Units Sold)
  3. **Load** – Loaded cleaned data into **Power BI** for visualization.

---

## 🔑 Key Features of Dashboard
- **Total Revenue, Total Profit & Units Sold**
- **Sales Breakdown by Region, Product Category, and Item Type**
- **Profit Comparison by Sales Channel (Online vs Offline)**
- **Time Series Analysis of Revenue**
- **Geographic Sales Map by Country**

---

## 🛠 Tools & Technologies
- **Power BI** – Dashboard creation
- **Excel / CSV** – Raw dataset
- **ETL Process** – Data cleaning & transformation
- **DAX (Data Analysis Expressions)** – Measures & calculated fields

---

## 📷 Screenshots
### Dashboard 1 – Basic Sales Metrics
![Dashboard 1](screenshots/dashboard1.png)

### Dashboard 2 – Sales Across Time & Product Categories
![Dashboard 2](screenshots/dashboard2.png)

---
## 🚀 How to Use

1. **Clone this repository and move into the project folder:**
   ```bash
   git clone https://github.com/your-username/sales-performance-dashboard.git
   cd sales-performance-dashboard
2. **Download the dataset (already included in dataset/ folder)**
   - If you want the original source, you can also get it from Kaggle: 5000 Sales Records Dataset.
3. **Perform ETL in Power BI:**
   - Open the dataset (SalesData.xlsx or SalesData.csv) in Power BI.
4. **Clean and transform data:**
   - Remove duplicates
   - Handle null values
   - Fix incorrect data types
5. **Add calculated columns:**
   - Total Revenue = Unit Price × Units Sold
   - Total Profit = Total Revenue – Total Cost
   Load the cleaned data model.
6. **Open the dashboard in Power BI Desktop:**
   - Open the file SalesDashboard.pbix
     
   
