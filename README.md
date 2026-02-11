# E-commerce Customer Funnel Analysis using SQL (Google BigQuery)

## 📌 Project Overview
This project analyzes customer behavior on an e-commerce website using
SQL in Google BigQuery. The analysis focuses on understanding the customer
conversion funnel, traffic source performance, time-to-purchase behavior,
and revenue metrics over the last 30 days.

The goal is to derive actionable business insights that can help improve
conversion rates, customer experience, and revenue performance.

---

## 🎯 Objectives
- Analyze user movement through the e-commerce funnel
- Calculate conversion rates between funnel stages
- Compare funnel performance across traffic sources
- Measure time taken by users to convert
- Evaluate revenue and order-level performance

---

## 🧾 Dataset Description
- Event-level e-commerce data
- Key columns include:
  - `user_id`
  - `event_type` (page_view, add_to_cart, checkout_start, payment_info, purchase)
  - `event_date`
  - `traffic_source`
  - `amount` (purchase value)

- Data filtered to the last 30 days for recent behavior analysis

---

## 🛠 Tools & Technologies
- Google BigQuery
- SQL (Standard SQL)
- GitHub

---

## 📂 Project Structure
- `sql/` → SQL queries for analysis
- `screenshots/` → Query outputs from BigQuery
- `README.md` → Project documentation

---

## 🔍 Analysis Performed

### 1️⃣ Funnel Stage Analysis
Identified the number of unique users at each stage:
- Page View
- Add to Cart
- Checkout Start
- Payment Info
- Purchase

This provides a high-level view of drop-offs across the funnel.

---

### 2️⃣ Conversion Rate Analysis
Calculated conversion rates between consecutive funnel stages:
- View → Cart
- Cart → Checkout
- Checkout → Payment
- Payment → Purchase
- Overall conversion rate from view to purchase

---

### 3️⃣ Funnel Performance by Traffic Source
Compared how different traffic sources perform across:
- Page views
- Add-to-cart actions
- Purchases
- Cart and purchase conversion rates

This helps identify high-quality acquisition channels.

---

### 4️⃣ Time-to-Conversion Analysis
Measured:
- Average time from page view to add to cart
- Average time from cart to purchase
- Total time taken from first interaction to purchase

Only converted users were included to ensure accurate timing insights.

---

### 5️⃣ Revenue Funnel Analysis
Calculated key revenue metrics:
- Total visitors and buyers
- Total revenue
- Total orders
- Average Order Value (AOV)
- Revenue per buyer
- Revenue per visitor

---

## 📊 Key Insights
- Significant user drop-off occurs between viewing and adding to cart
- Certain traffic sources generate higher purchase conversion rates
- Converted users typically complete purchases within a short time window
- A small portion of users contributes a large share of revenue
- Revenue per visitor highlights the effectiveness of overall funnel design

---

## 🚀 How to Run the Project
1. Open Google BigQuery Console
2. Load the e-commerce event dataset
3. Run SQL queries in the provided order
4. Review outputs for funnel, timing, and revenue insights

---

## 📌 Notes
This project was completed as a guided learning exercise.
All queries, logic, and insights reflect my understanding of
SQL-based data analysis and customer funnel analytics.
