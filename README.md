# 📊FUTURE_DS_01

# Business Sales Dashboard (2011-2014)

## 🧠 Project Overview
This project analyzes e-commerce sales data from **2011-2014** to identify best-selling products, profit trends, and high-revenue categories using **Power BI**.  
The dashboard provides actionable insights for improving business decisions.

---

## 🎯 Task Description (Given by Future Interns)

-**Task** : Analyze e-commerce data to identify best-selling Products,Sales trends and high revenue categories using Power BI.

-**Skills Gained** : Data Cleaning,DAX, Trend Analysis, Business Storytelling.

-**Deliverable** : An Interactive Dashboard with visuals and insights for business decisions.

---

## ⚙️ Tools & Skills Used
- **Power BI** – Data visualization & dashboard creation  
- **DAX (Data Analysis Expressions)** – Calculated measures and KPIs  
- **Microsoft Excel** – Data cleaning and preprocessing  
- **Business Storytelling** – Presenting data insights effectively  

---

## 💡 Key Insights
- Identified top-performing product categories and regions  
- Analyzed sales and profitability trends over time  
- Created KPIs to monitor growth and margin performance  
- Designed a clean, interactive dashboard for management review  

---

## 🧮 DAX Measures Used

- Total Sales = SUM(Sales[Sales])
- Total Profit = SUM(Sales[Profit])
- Total Returned Orders = COUNTROWS(Returns)
- Total Orders = DISTINCTCOUNT('Orders'[Order ID])
- Profit Ratio = DIVIDE([Total Profit],[Total sales],0)
- Return Rate = DIVIDE([Total Returned Orders],[Total Orders],0)
