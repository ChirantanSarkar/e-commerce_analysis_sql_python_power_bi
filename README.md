# 🛒 Blinkit E-Commerce Data Analysis

## 📌 Project Overview

This project focuses on analyzing Blinkit's e-commerce order data using **SQL, Python, Pandas, Matplotlib, and Power BI**. The objective is to uncover business insights related to sales performance, customer behavior, delivery efficiency, product performance, and payment trends.

The analysis helps identify key growth opportunities and operational improvements through data-driven decision making.

___

## 🎯 Objectives

* Analyze overall business performance through key KPIs.
* Understand city-wise, monthly revenue trends.
* Evaluate product category performance.
* Analyze customer satisfaction and ratings.
* Measure delivery efficiency across cities.
* Understand payment method preferences.
* Examine order status distribution.
* Create interactive visualizations for business reporting.

___

## 🛠️ Technologies Used

* **SQL** – Data extraction, cleaning and querying
* **Python**

  * Pandas
  * Matplotlib
  * SQLAlchemy

* **Power BI** – Interactive dashboards and visualization
* **Jupyter Notebook**
* **Git and GitHub**

___

## 📂 Project Structure

```text
|-- blinkit_1000_rows.sql          # Database and sample dataset
|-- Analysis_with_python.ipynb     # Data analysis using Python
|-- Power BI Visualisation.pbix    # Interactive Power BI dashboard
|-- README.md
```

___

## 📊 Key Performance Indicators (KPIs)

The following business metrics were analyzed:

* Total Orders
* Total Revenue
* Average Order Value (AOV)
* Total Discount Amount
* Average Delivery Time
* Average Customer Rating
* Number of Product Categories

___

## 📈 Analysis Performed

### 1. Revenue Analysis

* Monthly Revenue Trend
* Quarterly Revenue Analysis
* Product Category Revenue
* City-wise Revenue
* Discount vs Revenue Relationship

### 2. Product Performance Analysis

* Top Selling Products
* Category-wise Sales Performance
* Product Revenue Contribution

### 3. Customer Analysis

* Customer Rating Distribution
* Customer Satisfaction Insights

### 4. Delivery Performance Analysis

* Delivery Time Distribution
* City-wise Delivery Efficiency
* City-wise Customer Ratings

### 5. Payment Method Analysis

* Payment Method Distribution
* Customer Payment Preferences

### 6. Order Status Analysis

* Delivered Orders
* Cancelled Orders
* Returned Orders

### 7. City-wise Performance Analysis

* Revenue by City
* Average Delivery Time by City
* Average Customer Rating by City

___

## 📊 Power BI Dashboard

The Power BI dashboard provides interactive visualizations for:

* Revenue Trends
* Product Category Performance
* Customer Ratings
* Delivery Performance
* Payment Analysis
* City-wise Business Metrics

Users can filter and explore insights dynamically.

___

## 🔍 Key Insights

* Identified top-performing product categories and products.
* Analyzed seasonal and monthly revenue trends.
* Measured the impact of discounts on revenue generation.
* Evaluated customer satisfaction using rating distributions.
* Compared delivery performance across different cities.
* Discovered preferred payment methods among customers.
* Monitored order completion, cancellation, and return rates.

___

## 🚀 How to Run

### SQL

1. Import the SQL file into MySQL.
2. Create the required database.
3. Execute the SQL script.

### Python Analysis

```bash
pip install pandas matplotlib sqlalchemy mysql-connector-python
```

Update the database connection string in the notebook:

```python
engine = create_engine(
    "mysql+mysqlconnector://username:password@localhost/database_name"
)
```

Run all notebook cells to reproduce the analysis.

### Power BI

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the dataset connection if required.
3. Explore the dashboard interactively.

---

## 📚 Business Value

This project demonstrates how data analytics can be used to:

* Improve operational efficiency
* Optimize delivery performance
* Understand customer behavior
* Increase revenue opportunities
* Support strategic business decisions

___

## 👤 Author

**Chirantan Sarkar**
___