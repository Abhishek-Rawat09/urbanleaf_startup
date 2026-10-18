# UrbanLeaf Startup — Sales & Customer Analytics

**End-to-End Data Analytics Project | Python | Pandas | Power BI | Business Intelligence**

## 1. Project Overview

UrbanLeaf is a fictional Indian e-commerce startup selling lifestyle products, accessories, stationery, fitness products, and home essentials.

The objective of this project is to analyze sales performance, customer behavior, product demand, payment methods, sales channels, discounts, delivery performance, and customer satisfaction.

This project follows a practical business analytics workflow to transform raw transactional data into actionable insights and recommendations for business stakeholders.

> **Project type:** Portfolio / Business Analytics Case Study
> **Dataset:** Synthetic data created for practice
> **Business domain:** E-commerce
> **Currency:** Indian Rupee (INR)

## 2. Business Problem

UrbanLeaf wants to understand its business performance and identify opportunities for improvement.

The key business questions are:

* How is sales revenue changing over time?
* Which products and categories generate the most revenue?
* Which cities contribute the most sales?
* How do customers behave across different segments?
* Which payment methods and sales channels perform best?
* How do discounts affect order values?
* What are the major order cancellation and return patterns?
* Which product categories need customer-experience improvements?
* What business actions can improve customer retention and sales?

## 3. Project Objectives

1. Assess overall sales performance using business KPIs.
2. Identify high-performing and low-performing products and categories.
3. Analyze customer segments and geographical sales patterns.
4. Evaluate sales channels and payment preferences.
5. Examine order statuses, delivery performance, and customer ratings.
6. Identify data-quality risks and validate KPI calculations.
7. Build an interactive Power BI dashboard.
8. Provide practical, data-driven business recommendations.

## 4. Tools & Technologies

| Tool        | Purpose                                                  |
| ----------- | -------------------------------------------------------- |
| Python      | Data preparation and analysis                            |
| Pandas      | Data cleaning, grouping, aggregation, and transformation |
| NumPy       | Numerical operations                                     |
| Matplotlib  | Data visualization                                       |
| Seaborn     | Statistical visualization                                |
| Power BI    | Interactive dashboard development                        |
| Excel / CSV | Dataset storage and inspection                           |
| GitHub      | Project documentation and portfolio presentation         |

## 5. Dataset Description

The dataset contains synthetic e-commerce order records designed to simulate a small startup's business operations.

Important fields include:

| Column                | Description                       |
| --------------------- | --------------------------------- |
| `order_id`            | Unique order identifier           |
| `order_date`          | Date of order placement           |
| `customer_id`         | Customer identifier               |
| `customer_age`        | Customer age                      |
| `gender`              | Customer gender category          |
| `customer_segment`    | Customer segment                  |
| `city`                | Customer city                     |
| `state`               | Customer state                    |
| `product_id`          | Product identifier                |
| `product_name`        | Product name                      |
| `category`            | Product category                  |
| `quantity`            | Quantity ordered                  |
| `unit_price_inr`      | Selling price per unit            |
| `discount_percent`    | Discount percentage               |
| `discount_amount_inr` | Discount amount                   |
| `shipping_cost_inr`   | Shipping cost                     |
| `order_value_inr`     | Order value after discount        |
| `total_amount_inr`    | Order value plus shipping         |
| `payment_mode`        | Payment method                    |
| `sales_channel`       | Channel used to place the order   |
| `acquisition_source`  | Customer acquisition source       |
| `order_status`        | Current order status              |
| `delivery_date`       | Delivery date, when available     |
| `delivery_days`       | Delivery duration, when available |
| `customer_rating`     | Customer rating                   |

**Data note:** This dataset is synthetic and does not represent actual transactions or confidential information from a real company.

## 6. Data Preparation & Quality Checks

The data preparation and validation process focuses on:

* Inspecting dataset dimensions and column data types.
* Checking missing values and duplicate records.
* Validating order identifiers.
* Converting date columns into appropriate date formats.
* Checking numerical columns for invalid values.
* Validating revenue and order-value calculations.
* Reviewing missing delivery dates based on order status.
* Checking customer segment definitions.
* Standardizing currency presentation.
* Ensuring monthly trends are sorted chronologically.

Missing values should not automatically be deleted or replaced. Each treatment should be justified by business logic.

For example, a missing delivery date for a cancelled or processing order may be expected rather than a data-quality defect.

## 7. Exploratory Data Analysis

The project examines the following areas:

### Sales Analysis

* Total revenue
* Total orders
* Average Order Value (AOV)
* Monthly revenue trends
* Weekday sales patterns
* Payment-method performance
* Sales-channel performance

### Customer Analysis

* Customer distribution
* Gender-wise sales
* City-wise and state-wise revenue
* New, returning, and loyal customer segments
* Customer ratings and satisfaction patterns

### Product Analysis

* Product-wise revenue
* Category-wise order volume
* High-performing products
* Low-performing products
* Discount distribution
* Category-wise customer ratings

### Operations Analysis

* Order-status distribution
* Cancellation and return rates
* Delivery duration
* Delivery performance
* Customer-experience indicators

## 8. Key Business Findings

The following findings were reported from the analyst's UrbanLeaf dashboard.

| Business Area       | Finding                                                       |
| ------------------- | ------------------------------------------------------------- |
| Monthly Sales       | May was the strongest month at approximately ₹71K             |
| Monthly Sales       | April was the weakest month at approximately ₹45K             |
| Payment Method      | UPI contributed approximately ₹290.97K                        |
| Sales Channel       | Website sales were approximately ₹263K                        |
| Geography           | Jaipur was the leading city at approximately ₹134K            |
| Product Performance | Steel Lunch Box generated approximately ₹121K                 |
| Product Performance | Reusable Water Bottle generated approximately ₹81K            |
| Product Performance | Yoga Strap generated approximately ₹31K                       |
| Category Demand     | Accessories recorded 393 orders                               |
| Category Demand     | Lifestyle recorded 339 orders                                 |
| Category Demand     | Fitness recorded 171 orders                                   |
| Weekday Sales       | Friday generated approximately ₹116K                          |
| Customer Ratings    | Accessories averaged 4.0                                      |
| Customer Ratings    | Home & Office had the lowest reported category average at 3.8 |

*Figures are approximate dashboard-reported values. They should be reconciled against the final dataset before publication or external use.*

## 9. Business Recommendations

### Improve Website Performance

Investigate website conversion, product-page quality, checkout experience, and abandoned orders.

### Strengthen Customer Retention

Use verified repeat-purchase behavior to design loyalty offers and customer re-engagement campaigns.

### Review Product Performance

Evaluate leading and low-performing products using sales volume, costs, returns, inventory availability, and customer feedback.

### Improve Customer Experience

Investigate Home & Office ratings and review product quality, packaging, product descriptions, and customer complaints.

### Optimize Marketing Activities

Compare sales channels using attributed orders, conversion rates, customer acquisition costs, and campaign spending.

### Investigate Sales Trends

Review campaign activity, inventory, and comparable periods to understand the monthly and weekday sales patterns.

## 10. Power BI Dashboard

The recommended dashboard structure contains four pages.

**Page 1 — Executive Overview**

* Revenue
* Total orders
* Average Order Value
* Monthly sales trend
* Payment methods
* Sales channels

**Page 2 — Customer Insights**

* City-wise revenue
* State-wise revenue
* Customer segments
* Gender-wise sales
* Customer retention indicators

**Page 3 — Product & Category Analysis**

* Product-wise revenue
* Category-wise orders
* Product ratings
* Discount analysis

**Page 4 — Order & Operations Analysis**

* Order-status distribution
* Cancellation rate
* Return rate
* Delivery duration
* Weekday performance

Recommended slicers include date, city, state, category, product, sales channel, payment method, and order status.

## 11. Limitations

* The dataset is synthetic and is intended for portfolio practice.
* Revenue does not represent profit.
* Profitability analysis requires product costs and operating expenses.
* Marketing ROI and ROAS require advertising expenditure and reliable attribution data.
* Low sales may reflect product availability, limited exposure, or customer demand.
* Customer segments must be defined consistently before comparing their performance.
* Dashboard findings must be reconciled against the final source dataset.

## 12. Project Deliverables

The repository can contain:

* `urbanleaf_startup_orders.csv` — Dataset
* `UrbanLeaf_Startup_Analytics_Report.docx` — Editable report
* `UrbanLeaf_Dashboard.pbix` — Power BI dashboard, once saved
* `UrbanLeaf_Analysis.ipynb` — Python analysis notebook
* `README.md` — Project documentation


## 13. Conclusion

This project demonstrates an end-to-end approach to e-commerce data analytics, from data-quality assessment and exploratory analysis to dashboard reporting and business recommendations.

It focuses not only on identifying trends but also on validating metrics, recognizing analytical limitations, and translating findings into practical business actions.

The project represents a portfolio case study demonstrating data preparation, analytical thinking, visualization, and business communication.

---

**Disclaimer:** UrbanLeaf is a fictional startup created for educational and portfolio purposes. All dataset records are synthetic.
