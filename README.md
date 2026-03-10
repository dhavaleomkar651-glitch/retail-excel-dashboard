# 📊 Capstone Project — Business Analytics Dataset

## 📝 Short Description

This is a **Business Analytics Capstone Project** workbook containing **10,000 retail sales transactions** spanning the full year of **2024**. It covers multiple product categories, customer segments, and regions across India, along with pre-built analytical summary sheets for business insights.

---

## 📁 File Structure

| Sheet Name | Description |
|---|---|
| `Business_Analytics_Dataset_1000` | **Main dataset** — 10,000 rows of raw sales transaction data |
| `Sheet2` | Pivot summary: Sales trends, Category Profit, Regional Profit, Customer Segment & Payment Method |
| `Sheet3` | High-level KPI aggregates (Revenue, Profit, Customer count) |
| `Discount_Impact` | Analysis of how discount rate ranges affect average profit |
| `Price vs Volume` | Unit price bands vs total quantity sold |
| `Cost vs Revenue` | Category-wise cost vs revenue comparison |
| `Seasonality` | Monthly revenue and profit margin trends across the year |
| `Sheet1` | Empty / unused sheet |

---

## 🗂️ Main Dataset Columns

| Column | Type | Description |
|---|---|---|
| `Order_ID` | Integer | Unique identifier for each order |
| `Customer_ID` | String | Unique customer code (e.g., CUST3818) |
| `Order_Date` | Date | Transaction date (Jan 2024 – Dec 2024) |
| `Region` | Categorical | North, South, East, West |
| `Product_Category` | Categorical | Beauty, Clothing, Electronics, Sports, Home & Kitchen |
| `Customer_Segment` | Categorical | Consumer, Corporate, Home Office |
| `Quantity` | Integer | Units ordered per transaction |
| `Unit_Price` | Float | Price per unit (₹) |
| `Discount_Rate` | Float | Discount applied (0.0 – 1.0 scale) |
| `Revenue` | Float | Total revenue after discount |
| `Cost` | Float | Cost of goods sold |
| `Profit` | Float | Revenue minus Cost |
| `Payment_Method` | Categorical | Credit Card, Debit Card, UPI, Net Banking, Cash on Delivery |

---

## 📊 Key Statistics

| Metric | Value |
|---|---|
| Total Records | 10,000 transactions |
| Date Range | 1 Jan 2024 – 31 Dec 2024 |
| Total Revenue | ₹1,19,52,419 (~₹1.2 Cr) |
| Total Profit | ₹41,89,498 (~₹42 Lakh) |
| Avg Profit Margin | 35.05% |
| Avg Discount Rate | 15.03% |

---

## 🔍 Analysis Sheets Overview

- **Discount Impact** — Segments orders by discount band (0–5%, 5–10%, etc.) and measures effect on average profit. Useful for pricing strategy decisions.
- **Price vs Volume** — Groups unit prices into bands and shows how volume varies — helps identify high-demand price points.
- **Cost vs Revenue** — Category-level breakdown of total cost vs revenue (Beauty, Clothing, Electronics, Sports, Home & Kitchen).
- **Seasonality** — Monthly revenue and profit margin across 12 months — useful for identifying peak/off-peak sales periods.

---

## 🚀 Potential Use Cases

1. **Sales Performance Analysis** — Track revenue and profit trends by region, category, and time.
2. **Customer Segmentation** — Compare Consumer vs Corporate vs Home Office spending behaviour.
3. **Discount Optimization** — Understand how discounting impacts profitability.
4. **Seasonality Forecasting** — Plan inventory and marketing around peak months.
5. **Dashboard Development** — Use as a base dataset for Power BI / Tableau / Excel dashboards.

---

## 🛠️ Tools Recommended

- **Microsoft Excel / Google Sheets** — Pivot tables, charts, and slicers
- **Power BI / Tableau** — Interactive dashboards and drill-down reports
- **Python (Pandas)** — Data cleaning, EDA, and ML modelling
- **SQL** — Querying aggregates by region, category, segment

---

*Capstone Project | Business Analytics | 2024*
