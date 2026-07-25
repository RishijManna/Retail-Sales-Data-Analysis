# 🛍️ Retail Sales Data Cleaning & Exploratory Data Analysis

A complete end-to-end **Retail Sales Data Analysis** project demonstrating the complete data analytics workflow, including **data understanding, data cleaning, preprocessing, exploratory data analysis (EDA), interactive visualizations, business insights, and recommendations** using Python.

This project transforms a raw and intentionally uncleaned retail sales dataset into meaningful business insights through systematic data preprocessing and interactive analytics.

---

# 📌 Project Overview

Retail businesses generate large volumes of transactional data every day. However, raw data often contains missing values, duplicate records, inconsistent formats, and invalid entries, making it unsuitable for analysis.

The objective of this project is to clean the dataset, improve data quality, and perform an extensive exploratory data analysis to understand customer behavior, product performance, regional sales trends, profitability, shipping efficiency, and overall business performance.

Interactive Plotly visualizations are used throughout the project to make the analysis more intuitive and business-friendly.

---

# 🎯 Objectives

- Understand the structure and quality of the dataset.
- Identify and resolve data quality issues.
- Handle missing values and duplicate records.
- Standardize categorical variables.
- Correct invalid and inconsistent data.
- Perform feature engineering and preprocessing.
- Analyze customer demographics.
- Analyze product performance.
- Study sales and profitability trends.
- Evaluate operational performance.
- Generate business insights and recommendations.
- Build an executive business dashboard.

---

# 📂 Dataset Information

The dataset contains retail transaction records representing customer purchases from an online retail business.

### Dataset Summary

- **Rows:** 4,310
- **Columns:** 21

### Features

| Feature | Description |
|----------|-------------|
| order_id | Unique order identifier |
| customer_id | Unique customer identifier |
| customer_name | Customer name |
| age | Customer age |
| gender | Customer gender |
| city | Customer city |
| region | Customer region |
| product_category | Product category |
| product_name | Product name |
| quantity | Number of items purchased |
| unit_price | Price per product |
| discount_pct | Discount percentage |
| sales_amount | Total sales amount |
| profit | Profit earned |
| payment_method | Payment method |
| shipping_cost | Shipping cost |
| days_to_ship | Shipping duration |
| customer_satisfaction | Customer rating |
| return_flag | Product return status |
| order_status | Order status |
| order_date | Date of purchase |

---

# 🧹 Data Cleaning & Preprocessing

The raw dataset contained multiple quality issues that were identified and corrected before analysis.

### Data Cleaning Performed

- Removed duplicate records
- Handled missing values
- Corrected invalid ages
- Fixed negative numerical values
- Standardized categorical values
- Removed unnecessary ID prefixes
- Converted data types
- Parsed mixed-format dates
- Trimmed extra spaces
- Standardized text formatting
- Reset DataFrame index
- Exported cleaned dataset

---

# 📊 Exploratory Data Analysis

The project performs comprehensive exploratory data analysis using interactive Plotly visualizations.

### Customer Analysis

- Age Distribution
- Gender Distribution
- Region-wise Customers
- Top Cities by Customers

### Product Analysis

- Product Category Distribution
- Top Selling Products
- Category-wise Sales
- Category-wise Profit

### Sales Analysis

- Sales Distribution
- Monthly Sales Trend
- Region-wise Sales
- Top Customers by Sales

### Profitability Analysis

- Profit Distribution
- Product Category vs Sales & Profit
- Region-wise Profit

### Customer Behavior Analysis

- Payment Method Distribution
- Customer Satisfaction Analysis
- Product Return Analysis

### Operational Analysis

- Shipping Time Distribution
- Shipping Cost Analysis
- Order Status Distribution

### Relationship Analysis

- Correlation Heatmap
- Quantity vs Sales
- Discount vs Sales
- Discount vs Profit
- Customer Satisfaction vs Profit

### Executive Dashboard

The notebook concludes with an Executive Business Dashboard summarizing important KPIs:

- Total Orders
- Total Sales
- Total Profit
- Average Order Value
- Average Shipping Time
- Customer Satisfaction
- Return Rate

---

# 📈 Key Business Insights

The analysis provides several valuable business insights, including:

- Identification of high-performing product categories.
- Regional sales and profit comparison.
- Customer purchasing behavior analysis.
- Monthly sales trends.
- Profitability analysis across products.
- Customer payment preferences.
- Shipping performance evaluation.
- Customer satisfaction trends.
- Product return behavior.
- Relationships between discounts, sales, and profits.

---

# 💡 Business Recommendations

Based on the analysis, the following recommendations are proposed:

- Increase inventory for high-performing products.
- Improve logistics in regions with higher shipping costs.
- Optimize discount strategies to improve profitability.
- Focus marketing campaigns on high-performing regions.
- Enhance customer loyalty programs.
- Monitor customer satisfaction continuously.
- Reduce product return rates through quality improvement.
- Improve forecasting using historical sales trends.

---

# 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Plotly
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📦 Python Libraries

```python
numpy
pandas
matplotlib
seaborn
plotly
scikit-learn
```

Install the required libraries using:

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn
```


# 📊 Project Workflow

```
Raw Dataset
      │
      ▼
Data Understanding
      │
      ▼
Data Cleaning
      │
      ▼
Data Preprocessing
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Interactive Visualizations
      │
      ▼
Business Insights
      │
      ▼
Business Recommendations
      │
      ▼
Executive Dashboard
      │
      ▼
Conclusion
```

---

# 🎓 Learning Outcomes

This project demonstrates practical knowledge of:

- Data Cleaning
- Data Preprocessing
- Data Wrangling
- Exploratory Data Analysis
- Business Analytics
- Interactive Data Visualization
- Dashboard Development
- Statistical Analysis
- Business Intelligence
- Data Storytelling

---

# 🌟 Project Highlights

✅ Complete Data Cleaning Pipeline

✅ Missing Value Treatment

✅ Duplicate Removal

✅ Data Standardization

✅ Interactive Plotly Visualizations

✅ 20+ Business Charts

✅ Correlation Analysis

✅ Executive KPI Dashboard

✅ Business Insights

✅ Business Recommendations

---

# 🔮 Future Scope

The project can be further extended by:

- Sales Forecasting using Time Series Models
- Customer Segmentation using Clustering
- Market Basket Analysis
- Recommendation Systems
- Predictive Analytics
- Power BI Dashboard Development
- Tableau Dashboard Integration
- Machine Learning Models for Sales Prediction

---

# 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

If you find this project useful, feel free to fork the repository and submit a pull request.

---

# 📜 License

This project is developed for educational and portfolio purposes.

---

# 👨‍💻 Author

**Rishij Manna**

If you found this project useful, don't forget to ⭐ star the repository!
