# 📊 Padanjali Analysis Dashboard

## 📌 Project Overview

This project presents two sales dashboards built with **Microsoft Power BI** to analyse Padanjali sales data. The first covers overall sales performance: revenue, orders, products and payment methods. The second looks at sales by location, comparing countries, states and cities to find high- and low-performing regions.

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

---

## 📈 Business Value

This project helps to:

* Monitor overall sales performance.
* Identify revenue-generating products.
* Understand monthly sales fluctuations.
* Analyse payment method distribution.
* Compare sales performance across countries and states.
* Spot high- and low-performing locations.
* Support sales planning and business decision-making.

---

## ⚠️ Limitations

* Geographical figures are read from the charts, so they are approximate.
* The map uses billing country and the country bar chart uses shipping country, so the two can differ slightly.
* The order-volume chart uses billing state and the revenue chart uses shipping state.

---

## 🚀 Future Improvements

* Add average order value by location to see whether low-revenue states are low on volume, order size, or both.
* Analyse profit and profit margins, if cost data is available.
* Investigate monthly and yearly sales trends in greater detail.
* Compare customer purchasing behaviour across markets.
* Add further product performance metrics.
* Improve sales forecasting using historical data.

---

## 👨‍💻 Author

**G Arjun**

Data Analytics Enthusiast
Power BI | Excel | SQL | Python

---

## ⭐ Acknowledgements

This project was developed for educational and learning purposes. Dataset ownership and source details should be acknowledged where applicable.
