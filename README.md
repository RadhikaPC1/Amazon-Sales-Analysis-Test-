# 📊 Amazon Sales Analysis Dashboard (Power BI)

An interactive **Power BI dashboard** that analyses global sales performance across regions, countries, products, sales channels and order priorities. It turns raw transactional data (2010–2017) into clear KPIs and visuals so that revenue, cost, profit and product demand can be explored in a few clicks.

---

## 🎯 Project Overview

**Objective:** Build an interactive sales report that helps stakeholders answer questions such as:

- How much revenue, cost and profit did the business generate?
- Which regions and countries drive the most sales?
- Which product categories sell the most units and earn the most revenue?
- How are orders split across sales channels (Online / Offline) and order priorities (Low / Medium / High / Critical)?
- How do results change by country, year, month, order date or ship date?

**Scope:** 76 countries · 12 product categories · orders from **Feb 2010 to May 2017**

---

## 📈 Key Metrics

| KPI | Value |
|---|---|
| Total Revenue | **$137.35M** |
| Total Cost | **$93.18M** |
| Total Profit | **$44.17M** |
| Profit Margin (Profit ÷ Revenue) | **≈ 32.2%** |
| Countries Covered | **76** |
| Product Categories | **12** |

---

## ✨ Dashboard Features

- **3 report pages:** Cover page, Overall Insights, and Trends by Year and Month
- **KPI cards** for Sales, Total Cost, Total Profit, Total Revenue, Countries and Items
- **Slicers / filters** for Country, Year, Month, Ship Date and Order Date (date range sliders)
- **Cross-filtering:** clicking any chart updates every other visual
- **Dark theme** layout designed for readability
- **Mixed visuals:** combo chart, pie, donut, treemap, line and bar charts

---

## 🧩 Visuals Explained

| Visual | Chart Type | What It Shows |
|---|---|---|
| Total Sales and Profit by Region | Column + Line (combo) | Sales (columns) compared with profit (line) for each region |
| Sales Distribution by Item | Pie chart | Share of sales contributed by each product category |
| Top 10 Total Sales by Country | Treemap | The ten highest-selling countries, sized by sales |
| Total Revenue by Item | Donut chart | Revenue split across product categories |
| Total Units Sold by Item | Horizontal bar chart | Units sold per product category, ranked |
| Items Priority Distribution by Sales Channel | Donut chart | Order priority (C / H / L / M) split by sales channel |
| Total Revenue and Profit by Year | Line chart | Yearly revenue and profit trend |
| Total Sales and Item by Year | Line chart | Yearly sales for each item type |
| Total Units Sold by Year | Column chart | Yearly unit volume |

---

## 🔍 Key Insights

- **Healthy margins:** Profit is roughly one-third of revenue (≈ 32%), with costs making up about 68%.
- **Top countries:** The Gambia leads the Top 10 with about **$549.4M** in sales, followed by Switzerland and Turkmenistan at about **$274.7M** each. Syria, Tuvalu and the United Kingdom each show about **$137.35M**.
- **Most popular products by volume:** **Cosmetics (84K units)**, **Clothes (71K)** and **Beverages (57K)** sell the most units, while **Snacks (14K)** and **Vegetables (20K)** sell the least.
- **Revenue is concentrated:** The top three item categories generate roughly **$37M, $31M and $30M** respectively, far ahead of the smaller categories.
- **Balanced order priorities:** Orders are spread fairly evenly across Critical, High, Medium and Low priorities for both sales channels, with no single priority dominating.
- **Declining trend across regions:** Sales and profit fall steadily from the largest region to the smallest, showing a strong concentration in the top few regions.

> 📝 *Insights are based on the dashboard's default view (all countries, all dates). Values change when filters are applied.*

---

## 🗂 Dataset

| Column | Description |
|---|---|
| Region | Geographic region of the order |
| Country | Country of the order |
| Item Type | Product category (12 types, e.g. Cosmetics, Clothes, Beverages) |
| Sales Channel | Online / Offline |
| Order Priority | C (Critical), H (High), M (Medium), L (Low) |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Units Sold | Number of units sold |
| Unit Price | Selling price per unit |
| Unit Cost | Cost per unit |
| Total Revenue | Units Sold × Unit Price |
| Total Cost | Units Sold × Unit Cost |
| Total Profit | Total Revenue − Total Cost |

---

## 🛠 Tools & Technologies

- **Power BI Desktop**: data modelling, visuals and report design
- **Power Query**: data cleaning and transformation
- **DAX**: calculated measures (Total Revenue, Total Cost, Total Profit, etc.)
- **Excel / CSV**: source data

---

## 🔮 Future Improvements

- Add year-over-year and month-over-month growth indicators
- Add a profit-margin % card
- Add drill-through pages for country and product detail
- Include forecasting for future sales
- Publish to Power BI Service for easy sharing

---


