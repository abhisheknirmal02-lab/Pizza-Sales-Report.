# Pizza-Sales-Report.
# 🍕 Pizza Sales Report — Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Sales%20Analytics-orange)

An end-to-end **pizza restaurant sales analytics dashboard** built in Power BI, covering a full year of transactional data (Jan–Dec 2015). The report surfaces revenue trends, customer ordering patterns, and product performance across two interactive pages — giving decision-makers clear visibility into what's selling, what's not, and when the restaurant is busiest.

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | $817.86K |
| Total Orders | 21,350 |
| Total Pizzas Sold | 49,574 |
| Average Order Value | $38.31 |
| Average Pizzas per Order | 2.32 |

---

## 📁 Report Pages

### 1 — Pizza Sales Report
Overview of daily and monthly order trends, % of sales by pizza category (Classic, Supreme, Chicken, Veggie) and size (Large, Medium, Regular, XL), plus a ranked bar chart of total pizzas sold per category.

### 2 — Best / Worst Sellers
Side-by-side analysis of the top 5 and bottom 5 pizzas ranked by Revenue, Quantity, and Total Orders — enabling quick identification of star performers and underperformers across the menu.

---

## 💡 Key Insights

- **Friday and Saturday evenings** are the busiest periods — highest order volumes of the week
- **July and January** are peak months; September–November shows a notable dip
- **Classic category** leads all segments with 14,888 pizzas sold and the highest revenue share (26.91%)
- **Large size** pizzas drive maximum sales at 45.89% of all size-based revenue
- **Thai Chicken Pizza** tops revenue at $43K; Classic Deluxe leads in quantity and orders
- **Brie Carre Pizza** is the worst performer across all three metrics — revenue, quantity, and orders

---

## 🛠 Tools & Skills

- **Power BI Desktop** — data modelling, DAX measures, interactive report design
- **DAX** — KPI calculations, time-based aggregations, ranking measures
- **SQL** — data extraction, cleaning, and validation from source database
- **Data Visualisation** — bar charts, donut charts, line graphs, stacked visuals
- **Interactive slicers** — filter by Pizza Category and custom date range
- **Storytelling** — narrative callouts for busiest days and sales performance summaries

---

## 📂 Files

```
├── pizza_sales_report.pbix   # Power BI report file
├── data/
│   └── pizza_sales.csv       # Raw transactional dataset
├── sql/
│   └── queries.sql           # SQL validation queries
└── screenshots/              # Dashboard page previews
```

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `pizza_sales_report.pbix` in Power BI Desktop
3. Connect to your data source or point to the included CSV
4. Use the Pizza Category slicer and date pickers to explore specific segments
5. Toggle between the two report pages using the navigation panel

---

*Built as a portfolio project demonstrating real-world restaurant sales analytics — from raw transaction data to an interactive multi-page Power BI report. ⭐ Star this repo if you find it useful!*
