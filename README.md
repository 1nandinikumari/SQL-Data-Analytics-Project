# 📊 Data Analytics Project – SQL | Data Exploration | Business Insights

---

## 📘 Project Overview

This project focuses on performing **end-to-end data analytics and business exploration** using SQL.  
Starting from database creation, data insertion, and exploration, the objective of this project is to derive meaningful insights into **customer behavior, product performance, and sales trends** through a structured analytical workflow.

---

## 🎯 Project Objectives

- To design and build a **relational database** for sales and customer analysis.  
- To perform **comprehensive data exploration** — covering database, dimension, measure, and performance analytics.  
- To identify **key business metrics (KPIs)** and uncover insights related to sales growth, customer segmentation, and product performance.  
- To generate a **final analytical report** consolidating customer and product metrics.

---

## 🧩 Steps Followed

### **1. Database Creation**
- Created a new database schema for the project.  
- Defined and inserted data into multiple tables (e.g., Customers, Orders, Products, Transactions).  
- Established relationships between tables using primary and foreign keys.

---

### **2. Database Exploration**
- Analyzed database structure using the **INFORMATION_SCHEMA** views.  
- Identified:
  - Total number of **tables** in the database.  
  - Total number of **columns** in each table.  
- Ensured data integrity and checked for missing relationships or anomalies.

---

### **3. Dimension Exploration**
- Analyzed categorical and dimension-based data to understand data distribution.  
- Identified **unique/distinct values** within categorical columns (e.g., distinct `Country`, `Region`, `Product Category`).  
- Explored **data segmentation** — grouping customers or products by categories or regions to identify trends and patterns.

---

### **4. Data Exploration**
- Investigated temporal and demographic patterns to understand data range and variety.  
- Identified:
  - **Earliest and latest order dates** (first and last order).  
  - **Youngest and oldest customers** based on the age column.  
  - Overall data consistency across timelines and customer demographics.

---

### **5. Measure Exploration**
- Defined and calculated **key business metrics (measures)** such as:
  - 🛒 **Total Sales**
  - 📦 **Total Products Available**
  - 🧾 **Total Products Sold**
  - 👥 **Total Number of Customers**
  - 🔢 **Total Items Sold**
- Derived core performance indicators to assess business health and sales growth.

---

### **6. Magnitude Analysis**
- Performed magnitude-based comparison to understand scale and volume:
  - **Total Customers by Country**
  - **Customer Distribution by Gender**
  - **Sales Magnitude by Product Category**
- Helped identify high-performing regions and customer segments.

---

### **7. Ranking Analysis**
- Ranked key dimensions based on business measures:
  - **Top 5 Products** generating the highest revenue.
  - **Top 5 Customers** contributing the most sales.
  - **Top Performing Countries** by total sales volume.
- Used SQL ranking functions like `RANK()` and `DENSE_RANK()` for precise ordering.

---

### **8. Change Over Time Analysis**
- Examined how sales and transactions changed over time (monthly, yearly).  
- Identified growth trends and declining periods using date-based aggregations.  
- Used SQL window functions to compute **period-over-period comparisons**.

---

### **9. Cumulative Analysis**
- Calculated **cumulative totals** for key metrics such as sales and order count.  
- Enabled visualization of progressive growth across time intervals.  
- Implemented using SQL window functions like `SUM() OVER(ORDER BY Date)`.

---

### **10. Performance Analysis**
- Assessed business performance by comparing actual sales to expected values.  
- Evaluated performance across product categories, countries, and customer groups.  
- Highlighted underperforming areas and potential opportunities for improvement.

---

### **11. Part-to-Whole Analysis**
- Analyzed contribution of each segment to overall totals:
  - Product Category contribution to total sales.
  - Regional contribution to overall customer base.
- Helped in understanding **which segments drive the majority of business revenue**.

---

### **12. Report Generation**
- Consolidated insights into a final **analytical report**, summarizing:
  - **Key Customer Metrics** (e.g., customer distribution, demographics, retention behavior).  
  - **Key Product Metrics** (e.g., sales performance, revenue by category).  
- Delivered a data-driven summary for decision-makers to support business strategy.

---

## 💡 Key Insights Derived

- Identified **top-performing products and categories** contributing the majority of sales.  
- Discovered **seasonal trends** and time-based performance fluctuations.  
- Found that **specific customer segments (by country, gender, or age)** drive higher order frequency.  
- Pinpointed **top customers and regions** for targeted marketing and retention.  
- Quantified cumulative sales growth and performance over time.

---

## 🛠️ Tools & Technologies Used

- **SQL** – Database creation, data insertion, queries, and analytical operations.  
- **INFORMATION_SCHEMA** – For metadata and structural exploration.  
- **Aggregate & Window Functions** – For cumulative, ranking, and performance analysis.   

---

✨ This project demonstrates how a **structured SQL-driven data analytics workflow** can transform raw database information into **strategic business insights** — helping organizations understand **customer behavior**, **product performance**, and **sales dynamics** effectively.
