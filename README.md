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

  ---

## 🖥️ Project Workflow 

1.**Data Cleaning** – Removed duplicates, fixed inconsistent formats, and standardized fields.
2. **Data Modeling** – Established relationships between Orders and Details tables.
3. **Measure Creation** – Built calculated columns and DAX measures for analysis.
4. **Visualization Design** – Created KPIs, charts, map visuals, and slicers.
5. **Dashboard Formatting** – Used gradient themes, alignment grids, and business-friendly titles.
6. **Storytelling & Insights** – Highlighted actionable findings for strategic decisions.

---

## 🧠 Learnings

• Applying **data storytelling** to support business decisions.

• Building **interactive dashboards** that combine analytics with design.

• Enhancing **Power BI proficiency** with DAX, filters, and visualization best practices.
