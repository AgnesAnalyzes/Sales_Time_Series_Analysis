# Sales Time Series Analysis (2019)

## Project Overview
This project presents an end-to-end **time series and exploratory data analysis** of sales data from 2019.  
The goal is to understand **sales dynamics over time** by identifying trends, seasonal patterns, and irregular effects, and to translate these findings into **actionable business insights**.

The analysis is designed as a **portfolio project** and follows a structured, business-oriented workflow commonly used in data analytics roles.

---

## Business Objectives
- Understand how sales evolve over time  
- Identify seasonal patterns and recurring trends  
- Analyze customer purchasing behavior by time, product, and region  
- Detect anomalies and irregular sales effects  
- Support data-driven decision-making in sales planning and forecasting  

---

## Dataset
The dataset contains transactional sales data with the following key attributes:
- Order ID  
- Product  
- Quantity Ordered  
- Price Each  
- Order Date  
- Purchase Address  

Additional features were engineered during the analysis:
- Total Sales per order  
- City  
- Month, weekday, and hour of purchase  

---

## Analysis Workflow

### 1. Data Cleaning & Feature Engineering
- Removal of duplicate records  
- Data type conversion (dates and numeric values)  
- Feature creation (total sales, city, time-based features)  
- Aggregation of daily sales data for time series analysis  

### 2. Descriptive & Business Analysis
- Total revenue and average order value (AOV)  
- Monthly order volume to identify seasonality  
- Revenue concentration by product  
- Revenue distribution by city  
- Distribution of order values  
- Sales patterns by weekday and hour of day  

### 3. Data Visualization
- Monthly order trends  
- Revenue by product  
- Revenue by city  
- Distribution of order values  
- Sales by weekday  
- Orders by hour of day  

All visualizations are interpreted from a **business perspective**, not just descriptively.

### 4. Time Series Analysis
- Daily revenue aggregation  
- Seasonal decomposition (additive model)  
- Separation into:
  - Trend  
  - Seasonality  
  - Residuals (irregular effects)
 
---

## Key Insights
- Sales show **strong seasonality**, with a pronounced peak in Q4 driven by holiday demand.  
- Revenue is highly concentrated in a small number of **high-priced products** (e.g. laptops and smartphones).  
- Accessories sell frequently but contribute less to overall revenue.  
- Sales are geographically concentrated in major metropolitan areas.  
- Daily revenue patterns are explained by a combination of long-term trend, stable seasonality, and occasional irregular events.  
- Customer activity peaks during **midday and early evening hours**, reflecting typical leisure and after-work shopping behavior.  

---

## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Statsmodels  
- Jupyter Notebook  
