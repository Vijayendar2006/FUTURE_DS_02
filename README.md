# 🌍 Marketing Data Dashboard
## 📊 Project Overview

This interactive Power BI dashboard explores customer demographics, spending patterns, and income distribution across different countries and education levels.
It helps identify how customer profiles and background factors (like age, education, and marital status) influence total income and purchasing behavior.

---

## 🎯 Objective

To analyze customer data and provide key marketing insights through visual storytelling — enabling better targeting, segmentation, and campaign decisions.

---

## 🧾 Dataset Information

Source: CustomerMarketing.csv
Rows: 2,240  Columns: 28

Key Columns:

Demographics: Year_Birth, Education, Marital_Status, Country

Financial: Income, Total Spending, Average Income

Campaigns: AcceptedCmp1–5, Response, Complain

Purchases: NumWebPurchases, NumStorePurchases, NumCatalogPurchases

----

# 📐 Dashboard Layout
## 🧱 Page 1 – Overview

Filters: Marital Status, Country, Education, Year of Birth

KPI Cards:

🧍 Total Customers

💰 Total Spendings

💵 Sum of Income

📅 Average Income

🎯 Total Purchases

Charts & Visuals:

Line chart: Sum of Year_Birth vs Sum of Income by Country

Gauge: Count of Marital_Status

Donut chart: Marital Status Distribution by Country

## 🧱 Page 2 – Income Analysis

Bar Chart: Sum of Income by Country

Pie Chart: Sum of Income by Education

Bar Chart: Count of Education by Country

Line Chart: Sum of Income by Education and Year_Birth

---

## 🧮 Key Measures Used
Measure	Description
Total Customers	DISTINCTCOUNT(ID)
Total Spendings	Sum of all product spending columns
Sum of Income	SUM(Income)
Average Income	AVERAGE(Income)
Total Purchases	Combined total of web, store, and catalog purchases
Response Rate	DIVIDE(SUM(Response), [Total Customers])

---

## 🎨 Design & Theme
Element	Style
Background	Dark Blue
Visual Cards	Charcoal Gray
Accent Colors	Orange, Yellow, Green
Font	Segoe UI (Professional Power BI Default)
Visual Type Mix	Cards, Donuts, Gauges, Line & Bar Charts

🎨 All visuals and layout were designed by Shiva Kumar Keesari

---

## 💡 Key Insights

Spain (SP) contributes the highest income share among all countries.

Customers with Graduation and Master’s degrees dominate total income.

Majority of the customer base lies between ages 35–55.

Married customers and mid-aged graduates represent the strongest segment.

---

## 🧰 Tools & Technologies

Power BI Desktop – Data modeling and dashboard design

DAX – Measure creation

Excel / CSV – Data cleaning and preprocessing

---

## 📸 Dashboard Preview
<img width="1320" height="740" alt="Screenshot 2025-11-13 225639" src="https://github.com/user-attachments/assets/f004174b-f5e9-4fad-88c6-e374e2bd4d3d" />
<img width="1320" height="740" alt="Screenshot 2025-11-13 225639" src="https://github.com/user-attachments/assets/2b3a508e-4821-460c-9aa1-041d89a0faa0" />
<img width="1324" height="741" alt="Screenshot 2025-11-13 225621" src="https://github.com/user-attachments/assets/1c07a168-a9b0-45df-9606-7be63ece648e" />
<img width="1322" height="742" alt="Screenshot 2025-11-13 225604" src="https://github.com/user-attachments/assets/6cf42bad-d265-4d8a-a0d9-b4cb1efd92ff" />

