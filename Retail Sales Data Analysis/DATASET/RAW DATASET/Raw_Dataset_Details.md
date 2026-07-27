# 📂 Dataset Details

The project uses an **Indian Retail Sales Dataset** containing transactional records of customer purchases across multiple product categories and regions. The dataset is intentionally uncleaned and includes common real-world data quality issues, making it suitable for demonstrating data preprocessing and exploratory data analysis techniques.

## Dataset Summary

| Attribute | Details |
|-----------|---------|
| Dataset Type | Retail Sales Dataset (Raw / Uncleaned) |
| Total Records | **4,310** |
| Total Features | **21** |
| File Format | CSV |
| Data Type | Structured Tabular Data |

---

## Dataset Features

| Column | Description |
|--------|-------------|
| order_id | Unique identifier for each customer order |
| order_date | Date on which the order was placed |
| customer_id | Unique customer identifier |
| customer_name | Name of the customer |
| age | Age of the customer |
| gender | Gender of the customer |
| region | Region where the order was placed |
| city | Customer's city |
| product_category | Category of the purchased product |
| product_name | Name of the purchased product |
| quantity | Quantity of products purchased |
| unit_price | Price per product unit |
| discount_pct | Discount applied (%) |
| sales_amount | Total sales amount of the order |
| profit | Profit generated from the transaction |
| shipping_cost | Shipping cost for the order |
| payment_method | Payment method used by the customer |
| customer_satisfaction | Customer satisfaction rating (1–5) |
| return_flag | Indicates whether the product was returned |
| order_status | Current order status |
| days_to_ship | Number of days taken to ship the order |

---

## Data Quality Issues

The raw dataset contains several real-world data quality problems, including:

- Missing values
- Duplicate records
- Invalid age values
- Negative numerical values
- Mixed date formats
- Inconsistent categorical values
- Extra spaces in text fields
- Identifier prefixes in Order ID and Customer ID
- Incorrect data types

These issues were resolved during the data cleaning and preprocessing phase.
