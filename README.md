# Future DS Internship Task – Business Sales Dashboard

## 📌 Project Overview
This project is created as part of the **Future Intern (Future DS) Internship Task – future_ds-01**.  
The dashboard provides insights into business sales performance using **Power BI** and **DAX**.

---

## 🛠 Tools & Technologies Used
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Excel (Dataset)
- GitHub

---

## 📊 KPIs Implemented
- Total Sales
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin %
- Highest Sales
- Lowest Profit
- Running Total Sales

---

## 📈 Visualizations Used
- KPI Cards (Sales, Profit, Orders, AOV, Profit Margin)
- Bar Chart – Total Sales by Product
- Column Chart – Total Sales by Category
- Bar Chart – Total Profit by Region
- Line / Bar Chart – Running Total Sales by Year
- Donut Chart – Category Sales %
- Slicers – Region, Category, Date

---

## 🧮 DAX Measures Used
```DAX
Total Sales = SUM(Sales[Sales Amount])
Total Profit = SUM(Sales[Profit])
Total Orders = DISTINCTCOUNT(Sales[Order ID])
Average Order Value = DIVIDE([Total Sales], [Total Orders])
Profit Margin % = DIVIDE([Total Profit], [Total Sales])
