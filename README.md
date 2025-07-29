# 📊 Amazon Sales Dashboard (Power BI)

Welcome to the Amazon Sales Dashboard project! This dashboard was created to analyze and visualize sales data for an e-commerce platform (simulated Amazon data). It provides clear insights into revenue trends, product performance, regional sales, and customer behavior — all in a clean, interactive Power BI report.

## 📁 About the Project

The main goal of this project was to explore raw sales data and convert it into a meaningful, visual story. The dashboard helps answer key business questions like:

- What are the total sales and profit over time?
- Which products are performing best?
- How are different regions contributing to overall revenue?
- What is the customer order trend across months?

This dashboard is designed for business users, analysts, or management who want to track performance and take data-driven decisions.

---

## 🔧 Tools & Technologies Used

- **Power BI Desktop**
- Power Query for data transformation
- DAX (Data Analysis Expressions) for measures
- Excel (.xlsx) as a data source

---

## 🧹 Data Cleaning Steps

Performed in **Power Query**:

- Removed null or empty rows
- Split full name column into First & Last name
- Changed data types (e.g., Date, Currency, Whole Number)
- Trimmed whitespaces and renamed headers
- Handled missing values using transformations and conditional replacements

---

## 📐 Key DAX Measures

- `Total Sales = SUM(Sales[Amount])`
- `Total Profit = SUM(Sales[Profit])`
- `Profit Margin = DIVIDE([Total Profit], [Total Sales])`
- `Sales Growth = [This Year Sales] - [Last Year Sales]`

---

## 📊 Dashboard Features

- **Interactive filters** for Category, Region, and Month
- **KPI cards** for Total Sales, Profit, Orders
- **Trend charts** to show monthly sales
- **Top 10 Products** based on revenue
- **Geo map** to display region-wise sales
- Clean layout with consistent colors and responsive visuals

---

## 📂 Files Included

- `AmazonSalesDashboard.pbix` – Power BI report file
- `SalesData_PowerBI.xlsx` – Original Excel dataset
- `README.md` – This file

---

## 🚀 How to Use

1. Open the `.pbix` file using Power BI Desktop.
2. Refresh data if needed (Excel path may need to be updated).
3. Interact with filters and visuals to explore insights.

---

## 🙋‍♂️ Author

**Saksham Lanjewar**  
📧 sakshamlanjewar01@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sakshamlanjewar/)  
🌐 GitHub: [sakshamlanjewar01](https://github.com/sakshamlanjewar01)

---

## 📌 Note

This is a self-initiated project built for learning, showcasing skills in Power BI, DAX, and data visualization. The dataset used is fictional/simulated for practice purposes only.

