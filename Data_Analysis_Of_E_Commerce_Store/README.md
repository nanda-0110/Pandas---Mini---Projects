# E-Commerce Sales Analytics Using Pandas

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the **Olist Brazilian E-Commerce Dataset** using Python and Pandas.

The objective of this project is to analyze customer purchasing behavior, product performance, payment trends, delivery performance, and customer reviews by combining multiple datasets into a single analytical dataset.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Dataset Information

The project uses multiple datasets, including:

- Customers
- Orders
- Order Items
- Products
- Sellers
- Payments
- Reviews
- Product Categories

The datasets were merged using common keys such as **customer_id**, **order_id**, **product_id**, and **seller_id** to create a complete sales dataset.

---

## Analysis Performed

### Dataset Exploration

- Dataset Information
- Missing Value Analysis
- Duplicate Value Analysis
- Data Types
- Statistical Summary
- Dataset Merging

### Customer Analysis

- Total Customers
- Unique Customers
- Customers Who Ordered Once
- Customers with Multiple Orders
- Customer Spending Categories

### Product Analysis

- Top Selling Product Categories
- Total Products Sold
- Product Revenue Analysis

### Payment Analysis

- Most Preferred Payment Method
- Revenue by Payment Method
- Average Payment Value

### Delivery Analysis

- Average Delivery Time
- Fastest Deliveries
- Slowest Deliveries
- Delivery Performance Categories

### Review Analysis

- Review Score Distribution
- Average Review Score
- Customer Satisfaction Analysis

### Sales Analysis

- Total Revenue
- Average Order Value
- Highest Spending Customers
- Highest Revenue Orders

---

## Feature Engineering

Created new columns:

### Total Amount Spent

```python
total_amount_spent = Sum of payment_value for each order
```

### Delivery Duration

```python
Delivery_Duration = order_delivered_customer_date - order_purchase_timestamp
```

### Spending Category

Customers were classified as:

- Low Spender
- Medium Spender
- High Spender

### Delivery Category

Orders were classified based on delivery duration into different delivery performance groups.

### Review Quality

Customer reviews were categorized into:

- Excellent
- Good
- Average
- Poor

---

## Data Visualizations

Created visualizations using Matplotlib:

- Top 10 Selling Product Categories
- Payment Method Distribution
- Review Score Distribution

---

## Key Pandas Concepts Practiced

- `read_csv()`
- `merge()`
- `groupby()`
- `transform()`
- `apply()`
- `lambda`
- `value_counts()`
- `sort_values()`
- `isna()`
- `drop_duplicates()`
- `fillna()`
- `nunique()`
- `idxmax()`
- `idxmin()`
- Boolean Filtering
- Aggregations (`sum`, `count`, `mean`, `max`, `min`)

---

## Learning Outcomes

Through this project I learned:

- How to merge multiple real-world datasets using Pandas
- How to clean and preprocess large datasets
- How to perform customer, product, payment, delivery, and review analysis
- How to engineer meaningful features from raw data
- How to generate business insights from sales data
- How to visualize analytical results using Matplotlib
- How to build an end-to-end exploratory data analysis (EDA) project

---

## Acknowledgement

This project was built as part of my learning journey in Pandas.

I learned the core concepts from the **Codebasics Pandas course** and independently applied them to perform a complete end-to-end analysis of the **Olist Brazilian E-Commerce Dataset**, including data cleaning, merging, feature engineering, visualization, and business insights.
