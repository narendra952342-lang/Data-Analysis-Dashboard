# 📊 Narendra E-commerce Sales Dashboard

An interactive **E-commerce Sales Dashboard** created using sales
transaction data to analyze revenue, profit, quantity sold, customers,
product categories, sub-categories, states, payment methods, and monthly
performance.

## 📌 Project Overview

This project analyzes an e-commerce dataset containing **1,500 sales
transaction records** linked to **500 unique orders**. The data covers
sales made during **2018**.

The dashboard provides a clear view of business performance and helps
identify:

-   Overall sales and profit
-   Quantity sold
-   State-wise sales performance
-   Category-wise quantity distribution
-   Customer-wise sales
-   Payment method usage
-   Monthly profit trends
-   Profit by product sub-category

## 📊 Dashboard Highlights

  KPI                                         Value
  ------------------------ ------------------------
  💰 Total Sales Amount           ₹437,771 (\~438K)
  📈 Total Profit                   ₹36,963 (\~37K)
  📦 Total Quantity Sold               5,615 (\~6K)
  🧾 Unique Orders                              500
  📅 Data Period             January--December 2018

## 🔍 Key Insights

### State-wise Sales

Maharashtra records the highest sales amount at approximately
**₹102.5K**, followed by Madhya Pradesh at **₹87.5K**, Uttar Pradesh,
and Delhi.

### Category-wise Quantity

-   **Clothing:** 3,516 units (\~63%)
-   **Electronics:** 1,154 units (\~21%)
-   **Furniture:** 945 units (\~17%)

Clothing contributes the largest share of total quantity sold.

### Payment Mode

Based on quantity: - **COD:** 2,456 (\~44%) - **UPI:** 1,157 (\~21%) -
**Debit Card:** 741 (\~13%) - **Credit Card:** 672 (\~12%) - **EMI:**
589 (\~10%)

### Monthly Profit

Profit varies across the year. **November** has the highest monthly
profit at approximately **₹10.25K**, while May, July, September, and
December show negative monthly profit.

### Sub-category Profit

The highest-profit sub-categories are: 1. Printers --- ₹8,606 2.
Bookcases --- ₹6,516 3. Saree --- ₹4,057 4. Accessories --- ₹3,353 5.
Tables --- ₹3,139

### Customer Sales

Among the customers shown on the dashboard, **Harivansh** has the
highest sales amount, followed by **Madhav**, **Madan Mohan**, and
**Shiva**.

## 🗂️ Dataset

The project uses two CSV files:

### 1. Sales Dataset

Contains transaction-level sales information:

-   `Order ID`
-   `Amount`
-   `Profit`
-   `Quantity`
-   `Category`
-   `Sub-Category`
-   `PaymentMode`

### 2. Order Details Dataset

Contains order and customer information:

-   `Order ID`
-   `Order Date`
-   `CustomerName`
-   `State`
-   `City`

The two datasets are connected using **Order ID**.

## 🛠️ Tools & Technologies

-   **Power BI** -- Dashboard and data visualization
-   **CSV** -- Dataset format
-   **Data Analysis** -- Aggregation and business insights
-   **Data Visualization** -- Charts, KPIs, and interactive filters

## 📈 Dashboard Components

The dashboard includes:

-   KPI Cards for Amount, Profit, and Quantity
-   Quarterly filters
-   State-wise sales bar chart
-   Category-wise quantity donut chart
-   Monthly profit chart
-   Customer-wise sales chart
-   Payment-mode donut chart
-   Sub-category profit bar chart

## 🎯 Project Objective

The main objective of this project is to transform raw e-commerce
transaction data into an interactive dashboard that makes business
performance easy to understand.

It can help a business:

-   Monitor sales and profit
-   Identify high-performing states
-   Understand customer purchasing patterns
-   Analyze preferred payment methods
-   Identify profitable product sub-categories
-   Track monthly profit fluctuations
-   Support data-driven business decisions

## 📁 Suggested GitHub Structure

``` text
Ecommerce-Sales-Dashboard/
│
├── Dataset/
│   ├── Sales.csv
│   └── Order_Details.csv
│
├── Dashboard/
│   └── Ecommerce_Sales_Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

## 🚀 How to Use

1.  Clone or download this repository.
2.  Open the `.pbix` file using **Microsoft Power BI Desktop**.
3.  Make sure the CSV files are available in the `Dataset` folder.
4.  Update the data source path if required.
5.  Refresh the data.
6.  Use the dashboard filters to explore different quarters and business
    metrics.

## 📌 Conclusion

This project demonstrates how raw e-commerce data can be converted into
meaningful business insights using data analysis and visualization. The
dashboard provides a consolidated view of sales, profit, quantity,
customers, products, regions, and payment methods, making it easier to
understand business performance and identify important trends.

------------------------------------------------------------------------

### 👨‍💻 Author

**Narendra Sahu**\
B.Tech -- Data Science

⭐ If you find this project useful, consider giving the repository a
star!
