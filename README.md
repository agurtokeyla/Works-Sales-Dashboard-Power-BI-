

# Adventure Works Sales Dashboard (Power BI)

### 📊 Project Overview
This Power BI dashboard analyzes sales performance for **Adventure Works**, a global product retailer.  
It provides insights into **total sales, order quantity, deal size, and profit margins** across multiple years and product lines.

The dashboard focuses on clarity and interactivity — helping stakeholders quickly identify sales trends, performance gaps, and order status patterns.

---

### 🎯 Key Insights
- **Total Sales:** $10.03M across 2003–2007  
- **Top Product Line:** Classic Cars (3.9M in sales)  
- **Main Order Status:** Shipped (over 92% of total quantity)  
- **Profit Margin:** Averaged 0.98%  
- **Seasonality:** Clear peaks around mid-year with forecasted decline in later quarters  

---

### 🧠 Features & Visuals
- **KPI Cards:** Total Sales, Quantity, Average Deal Size, Profit Margin  
- **Trend Analysis:** Line chart with sales forecast  
- **Category Breakdown:** Sales by Product Line  
- **Composition View:** Order Status via donut chart  
- **Interactive Date Slicer** for flexible time filtering  

---

### 🧰 Tools & Skills Used
- **Microsoft Power BI Desktop**
- Power Query for data cleaning and column renaming  
- DAX Measures:  
  - `Total Sales = SUM(SALES)`
  - `Total Profit = SUMX(...)`
  - `Profit Margin % = DIVIDE([Total Profit], [Total Sales])`
- Forecasting & Time Series Analysis
- Dashboard layout and data storytelling

---

### 📁 Dataset
File: `sales_data_sample.csv`  
Source: Public sample dataset used for Power BI learning projects.  
Columns include: `OrderDate`, `CustomerName`, `ProductLine`, `Territory`, `Sales`, `QuantityOrdered`, `DealSize`, `Status`, and more.

---

### 💡 Key Takeaways
This project demonstrates:
- Data cleaning and transformation in Power Query  
- KPI creation and DAX measure writing  
- Time series and categorical analysis  
- Dashboard layout best practices for business reporting  

---

### 🖼️ Dashboard Preview
![Dashboard Preview](images/dashboard_preview.png)

---

### 🚀 Author
**Keyla Agurto**  
Building a professional data analytics skillset through hands-on Power BI and SQL projects.  
📍 GitHub: [agurtokeyla](https://github.com/agurtokeyla)
