<h1 align="center">📊  Sales Dashboard</h1>

<p align="center">
An interactive Excel dashboard built to analyze <b>Sales</b>, <b>Profit</b>, <b>Customer Behavior</b>, and <b>Business Performance</b> using Pivot Tables, Pivot Charts, KPI Cards, and Slicers.
</p>

<p align="center">
<img src="Dashboard.png" width="100%">
</p>

---

## 🎯 Project Objective

The objective of this project is to transform raw sales data into an interactive business dashboard that helps stakeholders monitor KPIs, identify sales trends, evaluate profitability, and make data-driven decisions.

---

## ✨ Dashboard Highlights

<table>
<tr>
<td>💰 Total Sales</td>
<td>📈 Total Profit</td>
<td>🛒 Total Orders</td>
</tr>

<tr>
<td>📦 Quantity Sold</td>
<td>💵 Average Order Value</td>
<td>📊 Profit Margin</td>
</tr>
</table>

---

## 📊 Dashboard Features

✅ Interactive KPI Cards

✅ Monthly Sales & Profit Trend

✅ Sales by Region

✅ Profit by Category

✅ Sales by Segment

✅ Top 10 Products

✅ Top 10 Customers

✅ Salesperson Performance

✅ Discount vs Profit Analysis

✅ Pareto Analysis

✅ Dynamic Slicers

---

## 🛠 Tools Used

<div>

🔹 Microsoft Excel

🔹 Pivot Tables

🔹 Pivot Charts

🔹 Slicers

🔹 Conditional Formatting

🔹 GETPIVOTDATA

🔹 Running Total

🔹 Pareto Analysis

🔹 Combo Charts

🔹 Dashboard Design

</div>

---

## 📈 Key Performance Indicators

| KPI | Formula |
|------|---------|
| Total Sales | =SUM(Sales) |
| Total Profit | =SUM(Profit) |
| Total Orders | =COUNTA(Order ID) |
| Total Quantity | =SUM(Quantity) |
| Average Order Value | =SUM(Sales)/COUNTA(Order ID) |
| Profit Margin | =(SUM(Profit)/SUM(Sales))*100 |

---

## 📌 Excel Formulas Used

### Running Total

```excel
=SUM($B$2:B2)
```

### Cumulative %

```excel
=Running_total/SUM($C$2:$C$18)
```

### Profit Margin

```excel
=Profit/Sales
```

### Average Order Value

```excel
=SUM(Sales)/COUNTA(Order ID)
```

### GETPIVOTDATA

```excel
=GETPIVOTDATA("Sum of Sales",$A$3)
```

---

## 📈 Business Insights

✔ West Region generated the highest revenue.

✔ Technology category contributed the highest profit.

✔ A few products generated the majority of sales (Pareto Principle).

✔ Higher discounts reduced profitability.

✔ Sales performance varied across salespersons.

✔ Interactive filters allow instant business analysis.

---

## 📁 Dashboard Components

- KPI Cards
- Interactive Slicers
- Line Charts
- Bar Charts
- Donut Chart
- Scatter Plot
- Pareto Chart
- Dynamic Reports

---

## 📸 Dashboard Preview

<img src="Dashboard.png" width="100%">

---

<h3 align="center">⭐ If you found this project useful, don't forget to Star the repository!</h3>
