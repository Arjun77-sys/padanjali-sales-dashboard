# 📊 Padanjali Analysis Dashboard

## 📌 Project Overview

This project presents three dashboards built with **Microsoft Power BI** to analyse Padanjali sales data. The first covers overall sales performance: revenue, orders, products and payment methods. The second looks at sales by location, comparing countries, states and cities to find high- and low-performing regions. The third looks at product performance: revenue, quantity sold and revenue share by product, and how revenue has moved from year to year.

The aim is to turn sales data into clear visuals that show sales patterns and support data-driven decisions.

> The dataset is confidential and is not included in this repository.

---

## 🎯 Objectives

* Analyse overall sales performance.
* Track monthly revenue and order trends.
* Analyse average order value across years.
* Identify top-performing products.
* Compare revenue across payment methods.
* Analyse sales by country, state and city to identify high- and low-performing locations.
* Compare products on revenue, quantity sold and revenue share to find top- and low-performing products.
* Track product revenue across years and show how price and volume relate for each product.
* Present key performance indicators (KPIs) using Power BI.

---

## 🛠️ Tools & Technologies

* Microsoft Power BI
* Microsoft Excel
* Power Query
* DAX (Data Analysis Expressions)
* Data Cleaning and Transformation
* Data Visualisation

---

## 🧹 Data Preparation

Before building the dashboards, the dataset (690 orders) was cleaned:

* Converted order values to INR so revenue is comparable across countries.
* Checked for and removed duplicates.
* Standardised text fields.

For the product analysis, a few extra steps were needed:

* Each order holds up to four product item slots, so the four item queries were appended into a single product table.
* Empty item slots were removed, and product names were standardised so each product appears under one spelling.
* Line totals were converted to INR using the exchange rate table. The final product table has 822 product lines.

---

### Key Performance Indicators (KPIs)

* Total Revenue
* Total Orders
* Average Order Value
* Guest Order Percentage
* Total Revenue in INR
* Total Revenue in USD

### Visualisations

* Total Revenue and Total Orders
* Average Order Value by Year
* Total Revenue by Payment Method
* Top Products by Revenue
* Revenue by Billing Country

---

### Key Performance Indicators (KPIs)

* Total Countries (24)
* Total Revenue (2.52M)
* Total Cities (352)
* Total Shipping States (73)
* Total Orders (690)

---

### Key Performance Indicators (KPIs)

* Total Products (11)
* Total Quantity Sold (1.08K)
* Average Selling Price (2.34K)
* Top Revenue Product (Agnijith 90 gms)

### Visualisations

* Total Revenue Earned by Product
* Total Quantity Sold by Product
* Total Revenue by Year
* Quantity Sold vs Revenue by Product

---

## 💡 Key Insights

### Sales Overview

* Monthly revenue fluctuates throughout the year, with noticeable peaks in May and October.
* Average order value shows a decline in 2026 compared with previous years.
* Razorpay accounts for approximately 99.48% of recorded revenue.
* Agnijith 90 gms is the leading revenue-generating product in the dashboard.
* Billing and shipping city match in almost every order. 98.84% of orders are shipped to the same city as the billing address; so gifting to other cities is rare.

### Geographical Analysis

* India dominates revenue. It brings in over half of the ₹2.52M, with the US, Singapore and the UK far behind.
* Kerala leads on both measures: about 235 orders (roughly a third of all 690) and about ₹0.36M in revenue, double any other state.
* Tamil Nadu, Maharashtra, Telangana and Karnataka are almost level, each bringing in ₹0.15M to ₹0.17M.
* Revenue drops sharply after the top five states. Gujarat and every state below it earn under ₹0.06M.
* Overseas adds about 30%. The US, Singapore and the UK together contribute roughly ₹0.7M.
* About 15 of the 24 countries contribute almost nothing, which points to occasional orders rather than established markets.

### Product Performance

* Agnijith 90 gms brings in ₹1.24M, about half of total revenue, and sells the most units (508).
* The Agnijith range as a whole makes up over 85% of revenue, so one product line carries most of the business.
* Agnihari 90gms sold 252 units but earned only about ₹0.15M, around ₹600 per unit against roughly ₹2,400 for Agnijith 90 gms. Demand is there, but the revenue per unit is low.
* The Agnijith multi-packs earn a lot per sale on small volumes. The 5 pack sold only 21 units and still brought in ₹0.32M, the second-highest revenue of any product.
* Kasmeerini 10ml, Kadambini 100ml and the Agnihari packs each earn ₹0.04M or less, so they add little to revenue.
* Revenue rose from ₹0.30M in 2023 to ₹0.97M in 2025. 2026 shows ₹0.65M, but it is a partial year.

---

## 📈 Business Value

This project helps to:

* Monitor overall sales performance.
* Identify revenue-generating products.
* Understand monthly sales fluctuations.
* Analyse payment method distribution.
* Compare sales performance across countries and states.
* Spot high- and low-performing locations.
* See which products carry the business and which add little, so stock and promotion can follow demand.
* Flag products where pricing may need a review, such as high volume with low revenue per unit.
* Support sales planning and business decision-making.

---

## ⚠️ Limitations

* Geographical figures are read from the charts, so they are approximate.
* The map uses billing country and the country bar chart uses shipping country, so the two can differ slightly.
* The order-volume chart uses billing state and the revenue chart uses shipping state.
* The dataset has no product cost field, so profitability is judged through revenue, quantity and revenue per unit, not true profit margin.
* Product percentages and per-unit values are worked out from rounded chart labels, so they are approximate.
* Pack sizes are counted as separate products, which understates how much the Agnijith range matters as a whole.
* Several products sold only 1 to 5 units, so a single order moves their revenue noticeably.
* 2026 is a partial year, so its revenue is not directly comparable with earlier years.

---

## 🚀 Future Improvements

* Add average order value by location to see whether low-revenue states are low on volume, order size, or both.
* Analyse profit and profit margins, if cost data is available.
* Investigate monthly and yearly sales trends in greater detail.
* Compare customer purchasing behaviour across markets.
* Add further product performance metrics.
* Group pack sizes into product families (Agnijith, Agnihari, Kadambini, Kasmeerini) to show revenue share by product line.
* Show which products sell in which countries and states, and which are often bought together.
* Improve sales forecasting using historical data.

---

## 👨‍💻 Author

**G Arjun**

Data Analytics Enthusiast
Power BI | Excel | SQL | Python
