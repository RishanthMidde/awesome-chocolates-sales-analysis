# 🍫 Awesome Chocolates – Sales Analysis (Excel)

An end-to-end sales analysis of a chocolate company's transaction data, built entirely in **Microsoft Excel** using formulas, pivot tables, conditional formatting, slicers and a dynamic dashboard.

The project answers 10 business questions about sales, profit, salespeople and product performance across 6 countries.

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `Awesome_Chacolates_Analysis.xlsx` | Main workbook: raw data + one sheet per analysis question |

---

## 📊 Dataset Overview

| Item | Value |
|------|-------|
| Transactions | 300 |
| Salespeople | 10 |
| Countries | 6 (India, Canada, New Zealand, USA, UK, Australia) |
| Products | 22 |
| Total Sales | $1,240,869 |
| Total Units Sold | 45,660 |
| Total Profit | $801,165 (≈ 64.6% margin) |

**Columns:** Sales Person, Geography, Product, Amount, Units, Cost per unit, Cost (a separate product table holds cost per unit per product).

> Profit = Amount − (Units × Cost per unit)

---

## ❓ Questions Answered

| # | Analysis | Techniques Used |
|---|----------|-----------------|
| 1 | Quick statistics (mean, median, min, max, range, quartiles, distinct products) | `AVERAGE`, `MEDIAN`, `MIN`, `MAX`, `QUARTILE` |
| 2 | Exploratory Data Analysis | Conditional formatting |
| 3 | Sales by country | `SUMIF` formulas |
| 4 | Sales by country | Pivot tables |
| 5 | Top 5 products by sales per unit | Pivot table + Top 5 filter |
| 6 | Anomalies in the data | Conditional formatting, charts |
| 7 | Best salesperson by country | Pivot tables |
| 8 | Profit by product | Lookup against products table, pivot |
| 9 | Dynamic country-level sales report | Dropdown, formulas, dynamic ranges |
| 10 | Which products to discontinue? | Profit % analysis, pivot table |

---

## 🔍 Key Insights

- **India is the top market by sales** ($252,469), followed by Canada ($237,944) and New Zealand ($218,813). **USA** has the highest unit volume (10,158) but lower revenue, suggesting lower-priced products or heavier discounting.
- **Highest total profit:** Baker's Choco Chips ($58,278), Eclairs ($56,472) and Raspberry Choco ($50,989).
- **Highest profit margin:** Eclairs (~88.6%), 85% Dark Bars (~85.3%) and Baker's Choco Chips (~82.9%).
- **Lowest profit margin:** Organic Choco Syrup (~28.2%), despite strong sales, because its cost per unit is the highest ($16.73). Other weak margins: 70% Dark Bites (~38.9%) and Almond Choco (~44.5%).
- **Product discontinuation candidates:** Organic Choco Syrup, 70% Dark Bites, Almond Choco and 50% Dark Bites are the weakest on margin and should be reviewed first.
- **Best salesperson by country:** Gigi Bohling leads in Australia, Canada and India; Ches Bonnell in New Zealand; Barr Faughny in the UK; Ram Mahesh in the USA.
- **Data quality:** the dataset contains outliers and suspicious records (e.g., very high amounts with very few units, and the reverse), which were flagged during the anomaly check.

---

## 🛠️ Excel Skills Demonstrated

- Statistical functions and descriptive statistics
- `SUMIF` / `SUMIFS`, `COUNTIF`, `VLOOKUP` / `XLOOKUP`
- Pivot tables, calculated fields and Top-N filters
- Slicers for interactive filtering
- Conditional formatting for EDA and anomaly detection
- Data validation dropdowns for a dynamic country report
- Charts and basic dashboard design

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Awesome_Chacolates_Analysis.xlsx` in Microsoft Excel (desktop version recommended, since slicers and some conditional formatting need it).
3. Go through the sheets in order (`1` to `10`). Each sheet is titled with its question.
4. On sheet `9`, use the dropdown to switch the country and watch the report update.

---

## 👤 Author

**Rishanth Midde**
- GitHub: [RishanthMidde](https://github.com/RishanthMidde)
- LinkedIn: [rishanth-midde](https://linkedin.com/in/rishanth-midde)
- Email: midderishanth@gmail.com

---

⭐ If you found this useful, consider starring the repo!
