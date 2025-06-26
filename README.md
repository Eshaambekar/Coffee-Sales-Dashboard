# ☕ Coffee Sales Dashboard – Power BI Project

This Power BI project provides an interactive dashboard for analyzing coffee sales data. It allows stakeholders to gain insights into sales performance across various product types, sizes, time periods, and store locations.

## 📊 Key Features

- 📈 **Total Sales & Transaction Count Overview**
- 🍵 **Sales by Product Category & Detail**
- 🧊 **Sales Volume by Size (Small, Regular, Large, etc.)**
- 📅 **Time-based Trends: Day of Week, Month Name**
- 🌍 **Store-wise Analysis (Location & ID)**

## 🧠 DAX Measures Used

```DAX
Total Quantity Sold = SUM(Transactions[transaction_qty])

Average Items per Transaction = 
    [Total Quantity Sold] / [Count of Transactions]

