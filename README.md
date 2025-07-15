> A comprehensive sales analytics dashboard created using Power BI and Python, integrating customer orders and transaction-level detail to generate actionable insights.

---

## Project Overview

This project presents an end-to-end **E-commerce business intelligence solution** analyzing **500+ customer orders** and **1,500 transaction line items**. The goal was to unify order data with itemized sales details to uncover performance patterns by state, city, product category, and payment method. Visual insights were crafted using **Power BI**, while preprocessing and validation were done using **Python**.

---

## Key Highlights

- Sales & Profit trend breakdown by **State**, **City**, **Category**, and **Sub-Category**
- Analysis by **Payment Mode** and its relation to profitability
- Top customers and high-revenue orders identified
- City-wise distribution to target logistics efficiency
- KPI visuals: **Total Revenue**, **Average Profit**, **Units Sold**, and **Top Payment Channels**

---

## 🧪 Dataset Description

### `Orders.csv`
| Column        | Description                     |
|---------------|---------------------------------|
| Order ID      | Unique order identifier         |
| Order Date    | Order transaction date          |
| CustomerName  | Name of customer                |
| State         | Customer's state                |
| City          | Customer's city                 |

### `Details.csv`
| Column        | Description                           |
|---------------|---------------------------------------|
| Order ID      | Reference to order in `Orders.csv`    |
| Amount        | Sales revenue from that item          |
| Profit        | Profit made from the sale             |
| Quantity      | Number of units sold                  |
| Category      | Product category (e.g., Furniture)    |
| Sub-Category  | Detailed product category             |
| PaymentMode   | Mode of payment (e.g., COD, EMI)      |

---

## 📂 Repository Structure

```
/ecommerce-sales-dashboard
│
├── /data/
│   ├── Orders.csv
│   └── Details.csv
│
├── /powerbi/
│   └── E-commerce_Sales.pbix
│
├── /images/
│   └── dashboard_overview.png
│
├── data_cleaning_notebook.ipynb
└── README.md
```

---

## Power BI Dashboard Preview

Includes visuals for:
- Revenue by State
- Profit by Category
- Top 10 Cities by Sales
- Payment Method Distribution
- Customer-wise Purchase Summary


<img width="1162" height="649" alt="Dashboard" src="https://github.com/user-attachments/assets/7c23b561-acaf-4fd8-b5b2-e9ab61d35ed0" />

---

## Technologies Used

- **Power BI**: Visual analytics and dashboard creation
- **Python**: Data cleaning, merging, and preprocessing
- **pandas**: Data analysis and transformation
- **Jupyter Notebook**: Exploratory Data Analysis (EDA)

---

## Business Impact

- Identified **top 5 profitable cities** and **loss-heavy categories**
- Discovered that **Credit Card users generate the highest profit**
- Suggested focusing on **Printers** and **Phones** for growth
- Highlighted need for improved margins on **Bookcases** and **Chairs**

---

