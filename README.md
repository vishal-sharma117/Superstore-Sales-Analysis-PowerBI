# Superstore-Sales-Analysis-PowerBI
“Super Store sales analysis dashboard using Power BI, CSV datasets, and forecasting.”
# Super-Store-Sales-Dashboard-PowerBI

## 📌 Project Overview
This project is a **Power BI Super Store Sales Dashboard** created using CSV data.  
The dashboard provides end-to-end insights into store performance, sales trends, customer behavior, and product categories.

It includes advanced analytics such as **time-series forecasting**, profit trends, and region-level sales distribution to help business leaders make data-driven decisions.

---

## 📁 Files Included
| File Name | Description |
|----------|-------------|
| `Super_Store_Sales.pbix` | Power BI Report File |
| `Orders.csv` | Main customer orders dataset |
| `Details.csv` | Order details dataset |
| `dashboard.png` | Dashboard preview image |
| `README.md` | Project documentation |

---

## 📊 Dashboard Preview
![Dashboard Preview](dashboard.png)

---

## 🚀 Key Insights From Dashboard
- Total Sales: **341K+**
- Total Quantity Sold: **5K**  
- Total Profit: **27K+**  
- Avg Delivery Time: **4 Days**
- Corporate segment contributes **highest profit**
- Phones, Storage, and Tables are **top contributing sub-categories**
- Central region contributes majority of the sales
- Standard and Second Class shipping modes are used most frequently
- Office Supplies is the top-selling category by revenue

---

## 🔮 Forecasting Insights (Time Series)
The dashboard includes **Sales Forecasting** using Power BI’s analytics:

- Forecast is applied on **Order Date** vs **Sum of Sales**
- Helps predict future demand trends
- Shows clear seasonal spikes and monthly variations
- Useful for inventory & planning

---

## 📦 Features of the Dashboard
- 📈 **Monthly & Yearly Sales Trend**
- 📉 **Profit Trend by Month**
- 🛒 **Sub-Category & Category Sales Analysis**
- 🗺 **State-wise Sales & Profit Map**
- 🧭 **Region-wise Sales Distribution**
- 💳 **Payment Mode Analysis**
- 🧾 **Segment-wise Profit Contribution**
- 📦 **Sales Forecasting (Analytics Line with Confidence Bands)**
- 🎯 **Interactive Slicers (Region Filter)**

---

## 🔧 Tools & Techniques Used
- **Power BI Desktop**
- **DAX Measures**
- **CSV Data Modeling**
- **Power Query**
- **Date Hierarchies**
- **Time-Series Forecasting**
- **Custom Visual Formatting**

---

## 📐 DAX Measures Used (Examples)
```DAX
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Total Quantity = SUM(Orders[Quantity])

Avg Delivery Time = AVERAGE(Orders[Ship_Days])

Profit % = DIVIDE([Total Profit], [Total Sales])

CY Sales = CALCULATE([Total Sales], YEAR(Orders[Order Date]) = 2020)
```

---

## 📥 How to Use This Project
1. Download the `.pbix` file  
2. Open in **Power BI Desktop**  
3. Load the `.csv` datasets if required  
4. Explore the dashboard using filters  
5. Review forecasting trends & region performance

---

## 📌 Folder Structure
```
📁 Super-Store-Sales-Dashboard-PowerBI
 ├── 📄 Super_Store_Sales.pbix
 ├── 📄 Orders.csv
 ├── 📄 Details.csv
 ├── 📄 dashboard.png
 └── 📄 README.md
```

---

## 🙋 Author
**Vishal Sharma**

---

## ⭐ Support
If you found this project helpful, consider ⭐ starring the repository!
