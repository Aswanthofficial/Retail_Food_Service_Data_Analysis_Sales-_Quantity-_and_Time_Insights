# 🍽️ Retail Food Service Data Analysis: Sales, Quantity & Time Insights

This project presents a real-world data analysis of a restaurant’s retail transactions. The goal is to extract actionable insights by analyzing sales, customer preferences, peak hours, and item performance based on invoices, quantities, and timestamps.

---

## 📁 Dataset Overview

- **File**: `Restaurant.xlsx`
- **Contents**:
  - `DATE` – Transaction date
  - `TIME` – Transaction time
  - `ITEM` – Item sold
  - `QUANTITY` – Quantity sold
  - `INVOICE_NO` – Bill number
  - `AMOUNT`, `SUB_TOTAL` – Sales amount details

---

## 🎯 Key Objectives

- Analyze daily and invoice-wise sales trends
- Identify top-performing and least-performing products
- Investigate time-based sales (e.g., peak sales between 6–9 PM)
- Explore quantity-based item popularity
- Generate meaningful visualizations for business insights

---

## 🛠️ Tools & Libraries

- **Python 3.11**
- **Pandas**, **NumPy** – Data wrangling and summarization
- **Matplotlib**, **Seaborn** – Data visualization
- **Datetime** – Time filtering and aggregation

---

## 📊 Insights & Visualizations

### ✅ Daily & Invoice-Wise Sales
- Filtered sales by specific date (e.g., `01.10.23`)
- Calculated average and total sales for invoices (e.g., Invoice 117)

### ✅ Product Performance
- Top 5 products by revenue (`SUB_TOTAL`)
- Top 5 products by quantity sold
- Least sold items (for specific days)

### ✅ Time-Slot-Based Analysis
- Quantity of **Porotta** sold between **6 PM – 9 PM** on `01.10.23`
- Used datetime filtering for precise hourly insights

### ✅ Invoice Trends
- Grouped and sorted invoices based on total amount spent

### 📈 Visuals Included:
- Bar charts for:
  - Top 5 products by sales
  - Top/least selling items
- Time-filtered quantity analysis

---
