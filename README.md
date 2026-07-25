# Indian Retail Sales Dataset (Cleaned)

## About this Dataset

A cleaned and preprocessed retail sales dataset containing **4,201 e-commerce transactions** collected from across India. This dataset is the refined version of the original raw retail sales data and is designed for **Exploratory Data Analysis (EDA), data visualization, feature engineering, business intelligence, and machine learning**. All major data quality issues have been addressed, making it suitable for learners, analysts, and developers who want to focus directly on data analysis rather than preprocessing.

---

## Context

The dataset represents order-level transactions from an online retail business operating across India's five major regions—**North, South, East, West, and Central**—between **2020 and 2024**. Each record contains customer demographics, product information, sales performance, profitability, shipping details, payment methods, and post-purchase feedback, providing a comprehensive view of retail operations.

Unlike the original raw dataset, this version has been carefully cleaned and standardized to ensure consistency, accuracy, and reliability for analytical and predictive tasks.

---

## Content

The dataset contains **4,201 cleaned records** and **21 attributes**, where each row represents a single customer order.

| Column | Description |
|---------|-------------|
| `order_id` | Unique identifier for each order |
| `order_date` | Date on which the order was placed |
| `customer_id` | Unique customer identifier |
| `customer_name` | Name of the customer |
| `age` | Customer's age |
| `gender` | Customer gender |
| `region` | Region of India (North, South, East, West, Central) |
| `city` | City where the order was placed |
| `product_category` | Product category (Groceries, Beauty, Furniture, Books, Clothing, Electronics, Sports) |
| `product_name` | Name of the purchased product |
| `quantity` | Number of units purchased |
| `unit_price` | Price per unit (₹) |
| `discount_pct` | Discount applied on the order |
| `sales_amount` | Total sales value (₹) |
| `profit` | Profit earned from the order (₹) |
| `shipping_cost` | Shipping charges (₹) |
| `payment_method` | Payment mode (UPI, Credit Card, Debit Card, EMI, Net Banking, Cash on Delivery) |
| `customer_satisfaction` | Customer satisfaction rating (1–5) |
| `return_flag` | Indicates whether the order was returned (True/False) |
| `order_status` | Current status of the order |
| `days_to_ship` | Number of days taken to ship the order |

---

## Data Cleaning Performed

The original dataset was thoroughly cleaned and preprocessed before being published. The following improvements were made:

- Removed **109 duplicate records**.
- Handled missing values using appropriate statistical imputation techniques (mean and median).
- Standardized inconsistent text formatting across categorical columns.
- Removed unnecessary prefixes from `order_id` and `customer_id`.
- Converted mixed date formats into a consistent datetime format.
- Corrected invalid and unrealistic numerical values such as negative prices, quantities, shipping costs, discounts, and customer ages.
- Converted columns to appropriate data types for analysis.
- Validated the dataset to ensure consistency and completeness.

---

## Suggested Use Cases

- Exploratory Data Analysis (EDA)
- Sales and profit trend analysis
- Customer behavior and demographic analysis
- Regional and city-wise sales comparison
- Product category performance analysis
- Customer satisfaction and return-rate analysis
- Business intelligence dashboard development (Power BI, Tableau)
- Feature engineering practice
- Machine learning models for sales prediction, customer segmentation, and return prediction
- Educational projects and data analytics portfolios

---

## Disclaimer

This is a **synthetic retail sales dataset** created for educational and practice purposes. The customer names, products, orders, and transactions are fictional and do not represent any real individuals, organizations, or commercial activities.

---

## Acknowledgements / License

This dataset is intended for **learning, research, portfolio development, and educational projects**. It may be freely used, modified, and shared for non-commercial purposes with appropriate attribution.
