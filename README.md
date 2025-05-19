# 🌸 FNP Sales Analysis Dashboard – Excel Project

This project is an interactive sales dashboard built using **Microsoft Excel**, designed to analyze and visualize sales data for **Ferns N Petals (FNP)**. It highlights key performance indicators like total revenue, average customer spend, product performance, and regional sales trends.

---

## 📈 Dashboard Highlights

- **Total Revenue**: ₹5,86,176  
- **Average Customer Spend**: ₹4,652  
- **Total Orders**: 126  
- **Average Delivery Time**: ~5.7 days  

### 📊 Key Visualizations:
- Revenue by **Occasion** (e.g., Birthday, Raksha Bandhan, Valentine's Day)
- Revenue by **Product Category** (e.g., Soft Toys, Sweets, Mugs)
- Revenue by **Month**
- Revenue by **Hour of the Day**
- **Top 5 Products** by Revenue
- **Top 10 Cities** by Order Volume

---

## 🛠️ What I Did

### 1. 🔄 Data Cleaning & Transformation (Excel)
- Removed blank rows and irrelevant columns
- Parsed `Order_Date` and `Delivery_Date` into proper Excel date formats
- Extracted **Month** and **Hour** from date/time fields
- Standardized inconsistent text entries (e.g., product names, categories)

### 2. 📐 Data Modeling (Excel)
- Created a structured dataset using **Excel Tables**
- Used helper columns to derive:
  - Month Names from `Order_Date`
  - Order Hour from `Order_Time`
- Linked data using consistent headers for use in PivotTables and Charts

### 3. 📊 Visualization
- Used **Pivot Tables** and **Pivot Charts** for dynamic aggregation
- Added **Slicers** to filter data by:
  - Occasion
  - Category
  - Month
- Designed charts for visual storytelling:
  - Bar and column charts for revenue comparisons
  - Card-style metrics for KPIs

---

## 💡 Business Insights

- 🎉 Peak sales occurred during **Valentine’s Day** and **Raksha Bandhan**
- 🕕 Most orders were placed in the **evening hours**
- 🧸 Categories like **Soft Toys** and **Mugs** were strong performers
- 📍 Major sales came from metro cities like **Delhi**, **Mumbai**, and **Bangalore**

---

## 🧰 Tools Used

- **Microsoft Excel**
  - Pivot Tables
  - Pivot Charts
  - Slicers
  - Date/Time Functions (e.g., `TEXT`, `MONTH`, `HOUR`)
  - Data Cleaning Techniques

---

## 📁 Dataset Overview

| Column Name      | Description                       |
|------------------|-----------------------------------|
| Order_ID         | Unique order number               |
| Product_Name     | Name of the product ordered       |
| Category         | Product category (e.g., Mug, Sweets) |
| Occasion         | Occasion associated with the order|
| Order_Date       | Date when the order was placed    |
| Delivery_Date    | Delivery date                     |
| Order_Time       | Time the order was placed         |
| Revenue          | Revenue from the order            |
| Location         | Customer city                     |

---

## 👤 Author

**Abhishek Kashyap**  
Fresher | Aspiring Data Analyst  
Skilled in **Excel**, **Data Cleaning**, **PivotTables**, and **Dashboard Design**

---

![Screenshot 2025-05-18 000424](https://github.com/user-attachments/assets/24a84b94-707c-42a3-a652-eb91ed644e60)
