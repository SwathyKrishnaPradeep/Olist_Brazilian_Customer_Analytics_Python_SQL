# Data

The original Olist Brazilian E-Commerce dataset is not included in this repository due to GitHub file size limitations.

You can download the dataset from Kaggle:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

This project uses processed datasets generated during the analysis, including:
- customer_features.csv #This file has been uploaded
- master_orders.csv

These files can be recreated by running the notebooks in sequence.

# Customer Analytics Project using the Olist Brazilian E-Commerce Dataset

## Project Overview

This project presents an end-to-end customer analytics solution using the **Olist Brazilian E-Commerce Public Dataset**, one of the largest publicly available e-commerce datasets from Brazil (2016–2018).

The project follows a complete analytics workflow—from data preparation and feature engineering to customer segmentation, predictive modeling, recommendation systems, and business insights. The analysis is implemented using **Python**, **DuckDB**, and **Machine Learning** techniques within Jupyter Notebooks.

---

## Objectives

* Build a complete customer analytics pipeline
* Understand customer purchasing behavior
* Engineer customer-level features
* Perform exploratory data analysis (EDA)
* Segment customers using RFM analysis and clustering
* Predict customer lifetime value (CLV)
* Forecast sales trends
* Build product recommendation systems
* Generate actionable business insights

---

## Dataset

**Source:** Olist Brazilian E-Commerce Public Dataset (Kaggle)

The project uses the following tables:

* Customers
* Orders
* Order Items
* Order Payments
* Order Reviews
* Products
* Sellers
* Geolocation
* Product Category Translation

---

## Tools & Technologies

| Category         | Tools               |
| ---------------- | ------------------- |
| Programming      | Python              |
| Database         | DuckDB              |
| Data Processing  | Pandas, NumPy       |
| Visualization    | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn        |
| Development      | Jupyter Notebook    |

---

## Project Workflow

### 1. Data Loading

* Imported multiple relational datasets
* Loaded data into DuckDB
* Performed SQL-based joins

### 2. Feature Engineering

Created customer-level features including:

* Total spend
* Average order value
* Purchase frequency
* Delivery performance
* Review statistics
* Payment behavior
* Product diversity
* Freight metrics

### 3. Exploratory Data Analysis

Performed analysis on:

* Customer spending
* Order trends
* Payment methods
* Delivery performance
* Product categories
* Seller distribution
* Geographic patterns

### 4. Customer Segmentation

Implemented:

* RFM Analysis
* Customer Personas
* K-Means Clustering

### 5. Customer Lifetime Value (CLV)

Estimated customer value using historical purchasing behavior to identify high-value customers.

### 6. Repeat Customer Analysis

Developed a machine learning model to identify repeat customers based on engineered behavioral features.

### 7. Sales Forecasting

Forecasted future sales trends using historical order data.

### 8. Recommendation System

Built a product recommendation engine to suggest relevant products based on customer purchasing patterns.

---

## Repository Structure

```text
Customer-Analytics-Olist/
│
├── Data/
│   ├── customer_features.csv
│   
│   └── Dataset_Link.txt
│
├── Notebooks/
│   ├── 01_Data_Loading.ipynb
│   ├── 02_Feature_Engineering.ipynb
│   ├── 03_EDA.ipynb
│   ├── ...
│   ├── 16_Recommendation_System.ipynb
│
├── Executive_Summary.pdf
├── README.md
└── requirements.txt
```

---

## Key Skills Demonstrated

* SQL using DuckDB
* Python Programming
* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis
* Customer Analytics
* RFM Analysis
* Customer Segmentation
* Machine Learning
* Recommendation Systems
* Sales Forecasting
* Data Visualization
* Business Insight Generation

---

## Business Insights

Some key insights generated include:

* Identification of high-value customer segments
* Customer purchasing behavior analysis
* Revenue concentration across customer groups
* Popular product categories
* Delivery performance trends
* Geographic sales distribution
* Customer review patterns
* Sales forecasting for business planning

---

## Future Improvements

* Churn prediction model
* Interactive Power BI dashboard
* Advanced recommendation algorithms
* Deep learning approaches
* Customer retention strategy optimization

---

## Dataset Credit

This project uses the **Olist Brazilian E-Commerce Public Dataset**, publicly available on Kaggle for educational and research purposes.

---

## Author

**Swathy Krishna Pradeep**

Feel free to connect or reach out for feedback and collaboration.

