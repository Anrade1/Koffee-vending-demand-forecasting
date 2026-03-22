# Koffee-vending-demand-forecasting
End-to-end analysis of coffee vending machine sales using EDA, machine learning, time series forecasting, and clustering to optimize demand and product strategy.
# Capstone Project  
## Coffee Vending Machine Sales Analysis – Final Report  

---

## 1. Define the Problem Statement

Coffee vending machine operators often rely on intuition rather than data to make decisions about inventory, product offerings, and restocking schedules. This can lead to overstocking low-demand products, stockouts during peak periods, and missed revenue opportunities.

The goal of this project is to analyze transaction-level sales data to uncover patterns in customer purchasing behavior and build predictive models that enable demand forecasting and optimization of product offerings.

---

## 2. Model Outcomes or Predictions

This project primarily uses **regression models** to predict transaction revenue (`money`), making it a **supervised learning problem**.

Additionally:
- **Time series modeling (ARIMA)** is used for short-term forecasting  
- **Clustering (KMeans)** is used as an **unsupervised learning approach** to identify purchasing behavior segments  

Expected outputs:
- Predicted revenue values  
- Forecasted short-term demand  
- Segmented customer behavior patterns  

---

## 3. Data Acquisition

The dataset consists of coffee vending machine transaction data from March 2024 onward.

Key features include:
- Product type (`coffee_name`)
- Revenue (`money`)
- Transaction date and time
- Day of week and month

The dataset provides sufficient granularity to analyze temporal patterns and customer behavior.

Initial exploration included:
- Inspecting dataset structure (`df.head()`, `df.info()`)
- Evaluating distributions of key variables
- Identifying patterns in time-based and product-based data

---

## 4. Data Preprocessing / Preparation

### a. Data Cleaning
- Converted date and time fields into usable formats  
- Extracted time-based features such as hour, day of week, and month  
- Handled inconsistent time formatting by extracting hour directly from strings  
- Removed missing or invalid records using `.dropna()`  

### b. Train/Test Split
- Data was split into training and testing sets using an 80/20 split:
```python
train_test_split(X, y, test_size=0.2, random_state=42)
