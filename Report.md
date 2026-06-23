# E-Commerce Data Analysis Report

___

## Executive Summary

This project analyzes 1,000 Blinkit e-commerce orders to evaluate business performance, customer behavior, delivery efficiency, product category trends, and payment preferences.

This analysis is done by using SQL, Python (Pandas & Matplotlib), and Power BI.

The objective is to identify key performance indicators (KPIs) and generate actionable insights that can support operational and strategic business decisions.

___

# Dataset Overview

| Metric             | Value                 |
| ------------------ | --------------------- |
| Total Orders       | 1,000                 |
| Product Categories | 8                     |
| Cities Covered     | 8                     |
| Analysis Tools     | SQL, Python, Power BI |

___

# Key Performance Indicators (KPIs)

## Sales Performance

| KPI                       | Value       |
| ------------------------- | ----------- |
| Total Revenue             | ₹387,524.54 |
| Average Order Value       | ₹387.52     |
| Total Discount Given      | ₹35,742.59  |

### Insight

The platform generated nearly ₹3.88 lakh in revenue from 1,000 orders, with an average order value of approximately ₹388.

___

## Customer Experience

| KPI                     | Value         |
| ----------------------- | ------------- |
| Average Customer Rating | 3.99 / 5      |
| Average Delivery Time   | 21.25 Minutes |

### Insight

Customers generally reported positive experiences, with ratings close to 4 stars and average delivery times maintained around 21 minutes.

___

# Product Category Analysis

## Revenue by Category

| Category            | Revenue (₹) |
| ------------------- | ----------: |
| Meat & Seafood      |  123,449.12 |
| Staples             |   61,277.13 |
| Personal Care       |   52,540.00 |
| Snacks & Beverages  |   37,102.99 |
| Household           |   36,829.17 |
| Bakery              |   28,382.33 |
| Dairy & Eggs        |   27,500.05 |
| Fruits & Vegetables |   20,443.75 |

### Key Findings

* Meat & Seafood generated the highest revenue, contributing approximately 31.9% of total revenue.
* Staples emerged as the second-largest revenue contributor.
* Fruits & Vegetables generated the lowest revenue among all categories.

___

## Category-wise Order Volume

| Category            | Orders |
| ------------------- | -----: |
| Snacks & Beverages  |    148 |
| Bakery              |    139 |
| Dairy & Eggs        |    127 |
| Personal Care       |    125 |
| Fruits & Vegetables |    122 |
| Staples             |    118 |
| Meat & Seafood      |    114 |
| Household           |    107 |

### Insight

Although Snacks & Beverages recorded the highest number of orders, Meat & Seafood generated significantly more revenue due to its higher product value.

___

# Revenue Trend Analysis

## Monthly Revenue

| Month     | Revenue (₹) |
| --------- | ----------: |
| January   |   29,943.79 |
| February  |   40,384.07 |
| March     |   35,708.64 |
| April     |   25,787.99 |
| May       |   34,223.73 |
| June      |   30,560.15 |
| July      |   36,168.84 |
| August    |   32,857.27 |
| September |   23,739.78 |
| October   |   31,874.75 |
| November  |   36,535.43 |
| December  |   29,740.10 |

### Key Findings

* February recorded the highest monthly revenue (₹40,384.07).
* September generated the lowest revenue (₹23,739.78).
* Revenue remained relatively stable throughout the year with moderate seasonal fluctuations.

___

## Quarterly Revenue

| Quarter | Revenue (₹) |
| ------- | ----------: |
| Q1      |  106,036.50 |
| Q2      |   90,571.87 |
| Q3      |   92,765.89 |
| Q4      |   98,150.28 |

### Insight

Q1 was the strongest quarter, accounting for the highest revenue contribution, while Q2 showed the weakest performance.

___

# City-wise Performance Analysis

## City-wise revenue

| City      | Revenue (₹) |
| --------- | ----------: |
| Ahmedabad |   59,045.79 |
| Chennai   |   51,642.57 |
| Bangalore |   48,476.65 |
| Kolkata   |   48,006.74 |
| Hyderabad |   47,292.56 |
| Mumbai    |   46,326.48 |
| Delhi     |   43,895.51 |
| Pune      |   42,838.24 |

### Insight

Ahmedabad generated the highest revenue among all cities, while Pune generated the lowest.
### Chart
<img width="908" height="470" alt="image" src="https://github.com/user-attachments/assets/f2673b44-0a7d-4992-8a16-27d1fc281d24" />
___

## City-wise Customer Ratings 

| City      | Avg Rating |
| --------- | ---------: |
| Mumbai    |       4.10 |
| Pune      |       4.03 |
| Chennai   |       4.02 |
| Delhi     |       4.00 |
| Ahmedabad |       3.99 |
| Kolkata   |       3.98 |
| Bangalore |       3.92 |
| Hyderabad |       3.89 |

### Insight

Mumbai achieved the highest customer satisfaction score, whereas Hyderabad recorded the lowest average rating.

### Chart
<img width="855" height="393" alt="image" src="https://github.com/user-attachments/assets/0ced4112-7b09-4dda-a168-02bcabe0236e" />

___

## City-wise Average Delivery Time

| City      | Delivery Time (Minutes) |
| --------- | ----------------------: |
| Delhi     |                   20.04 |
| Pune      |                   20.79 |
| Mumbai    |                   20.88 |
| Bangalore |                   20.92 |
| Kolkata   |                   21.29 |
| Ahmedabad |                   21.64 |
| Hyderabad |                   22.22 |
| Chennai   |                   22.24 |

### Insight

Delhi maintained the fastest delivery performance, while Chennai recorded the longest average delivery times.
### Chart
<img width="855" height="393" alt="image" src="https://github.com/user-attachments/assets/343335ee-8d85-42f5-8dd9-37ef52aeb3c6" />
___

# Payment Method Analysis

| Payment Method   | Orders |
| ---------------- | -----: |
| Cash on Delivery |    230 |
| Blinkit Wallet   |    205 |
| Debit Card       |    194 |
| UPI              |    186 |
| Credit Card      |    185 |

### Key Findings

* Cash on Delivery remained the most preferred payment method.
* Digital payment methods collectively accounted for the majority of transactions.

### Chart
<img width="493" height="411" alt="image" src="https://github.com/user-attachments/assets/a0128fdd-0f9b-496b-8bc2-3015051b8b4d" />
___

# Order Status Analysis

| Status    | Orders |
| --------- | -----: |
| Delivered |    677 |
| Cancelled |    168 |
| Returned  |    155 |

### Key Findings

* 67.7% of orders were successfully delivered.
* 16.8% of orders were cancelled.
* 15.5% of orders were returned.

### Chart
<img width="411" height="411" alt="image" src="https://github.com/user-attachments/assets/43e0df36-3df2-466a-bc2f-f1b268192224" />
___

# Business Recommendations

1. Increase focus on Meat & Seafood products, as they generate the highest revenue.
2. Improve customer experience in Hyderabad and Bangalore, where ratings are comparatively lower.
3. Investigate factors contributing to slower deliveries in Chennai and Hyderabad.
4. Promote digital payment methods through rewards and cashback programs.
5. Analyze reasons for cancellations and returns to improve order fulfillment efficiency.
___

# Conclusion

The Blinkit e-commerce platform demonstrates strong sales performance with stable revenue generation, efficient delivery operations, and positive customer satisfaction levels.

Revenue is primarily driven by high-value categories such as Meat & Seafood and Staples, while city-wise analysis highlights opportunities to improve customer experience and logistics performance in specific markets.
___

# Author
**Chirantan Sarkar**
___
