# Koffee-vending-demand-forecasting
End-to-end analysis of coffee vending machine sales using EDA, machine learning, time series forecasting, and clustering to optimize demand and product strategy.
# Capstone Project  
## Coffee Vending Machine Sales Analysis – Final Report  

---

#### Define the Problem Statement

Coffee vending machine operators often rely on intuition rather than data to make decisions about inventory, product offerings, and restocking schedules. This can lead to overstocking low-demand products, stockouts during peak periods, and missed revenue opportunities.

The goal of this project is to analyze transaction-level sales data to uncover patterns in customer purchasing behavior and build predictive models that enable demand forecasting and optimization of product offerings.

---

#### Model Outcomes or Predictions

This project primarily uses **regression models** to predict transaction revenue (`money`), making it a **supervised learning problem**.

Additionally:
- **Time series modeling (ARIMA)** is used for short-term forecasting  
- **Clustering (KMeans)** is used as an **unsupervised learning approach** to identify purchasing behavior segments  

Expected outputs:
- Predicted revenue values  
- Forecasted short-term demand  
- Segmented customer behavior patterns  

---

#### Executive summary

This project analyzes coffee vending machine sales to understand customer purchasing behavior and identify patterns in demand. The analysis shows that sales are highly predictable based on time of day, day of the week, and product type.

By applying data analysis and forecasting techniques, this project demonstrates how vending operators can improve inventory planning, reduce waste, and increase revenue through more informed decision-making.

---

#### Rationale

Vending machine operators often rely on intuition to decide what products to stock and when to restock. This can lead to missed sales opportunities, overstocking, and inefficient operations.

Understanding customer behavior and demand patterns allows operators to make better decisions, improve efficiency, and provide a better customer experience.

---

#### Research Question

What sales trends and customer purchasing patterns emerge from coffee vending machine transactions, and how can these insights be used to forecast demand and optimize product offerings?

---

#### Data Sources

The dataset consists of transaction-level coffee vending machine sales data, including:

- Product type (coffee_name)  
- Revenue (money)  
- Transaction date and time  
- Day of the week and month  

This data provides detailed insight into when purchases occur and how much customers spend.

---

#### Methodology

To answer the research question, the following methods were used:

- **Exploratory Data Analysis (EDA):**  
  Identified patterns in sales by time of day, day of week, and product performance  

- **Machine Learning Models:**  
  Built regression models to predict revenue and understand key drivers of demand  

- **Time Series Analysis:**  
  Analyzed trends and seasonal patterns over time and generated short-term forecasts  

- **Clustering:**  
  Grouped transactions into segments to identify different types of customer behavior  

---

#### Results

The analysis revealed several key insights:

- Sales are highest during **weekday working hours (9 AM – 5 PM)**  
- A small number of products drive the majority of revenue  
- Demand follows consistent and repeatable patterns over time  
- Predictive models can accurately forecast short-term demand  
- Customer behavior can be segmented into different spending patterns  

These findings show that vending machine sales are structured and predictable rather than random.

---

#### Next steps

To further improve this analysis, the following steps are recommended:

- Incorporate external data such as weather or foot traffic  
- Test more advanced forecasting models  
- Apply dynamic pricing or promotions based on demand patterns  
- Deploy the model into a real-time inventory management system  

---
