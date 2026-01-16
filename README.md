# Supplier Selection Analytics — Power Query + Excel Dashboard
Procurement analytics project using Power Query, Excel, and KPI engineering to understand supplier selection drivers.

## Data Source: https://www.kaggle.com/datasets/programmer3/supply-chain-dataset?resource=download\

## Overview
This project analyzes 3,089 supplier bids to understand what drives supplier selection in a procurement process.  
Using Power Query, Excel, and custom KPI engineering, I built a complete analytics pipeline and dashboard that compares **Selected vs Rejected** suppliers across performance, cost, reliability, and value metrics.

---

## Business Problem
Procurement teams must choose suppliers who deliver high performance, low risk, and strong value.  
But what metrics actually influence selection?

This project answers:

- What characteristics differentiate selected suppliers from rejected ones?  
- Are decisions driven more by price, quality, or delivery performance?  
- What is the “ideal profile” of a selected supplier?  
- Which KPIs matter most in supplier evaluation?

---

## Dataset
The dataset contains 3,089 supplier bids with:

- Cost metrics  
- Quality metrics  
- Delivery performance  
- Reliability indicators  
- Procurement action codes  
- Delivery terms  
- Seasonal and demand volatility  
- Outcome: selected or rejected  

---

## Methodology

### 1. Descriptive Analysis
- Summary statistics  
- Column profiling  
- Categorical distributions  
- Monthly volume analysis  

### 2. Feature Engineering (Power Query)
Created business‑meaningful KPIs:

- Delivery performance  
- Order accuracy  
- OTIF  
- Risk score + category  
- Value score + category  
- Price category  
- Lead‑time consistency  
- Fulfillment ratio + category  
- Shipping cost estimate  
- Total cost impact  
- Customer satisfaction estimate  

### 3. Summary KPIs
Compared Selected vs Rejected across:

- Performance  
- Cost  
- Risk  
- Value  
- Fulfillment  
- Satisfaction  

### 4. Category Distributions
Grouped suppliers by:

- Risk  
- Value  
- Price  
- Lead time  
- Fulfillment  

### 5. Numeric Parameter Summary
Unpivoted numeric fields → compared averages → calculated differences and % differences.

### 6. Correlation Analysis
Exploratory correlations between metrics and selection status.

### 7. Dashboard
Interactive Excel dashboard with:

- Selection overview  
- KPI comparison  
- Category-based evaluation  
- Numeric parameter drilldown  
- Monthly distribution  

---

## Key Insights

- **Fulfillment ratio** is the strongest differentiator (+22% for selected suppliers).  
- **Total cost impact** is significantly lower for selected suppliers (−4%).  
- **Shipping cost** is lower for selected suppliers (−3.5%).  
- Price and quality score have **minimal influence** on selection.  
- Selected suppliers tend to be **more consistent**, **lower risk**, and **better value**.

---

## Dashboard Preview

dashboard_screenshoot/selection_overveiw.png

---

## Tools Used

- Excel  
- Power Query (M language)  
- PivotTables  
- Data Visualization  
- KPI Engineering  

---

## What I Learned

- How to engineer KPIs from raw procurement data  
- How to compare supplier groups using numeric and categorical analysis  
- How to build a complete analytics pipeline in Power Query  
- How to design an executive‑ready dashboard  
- How to translate data into business insights  

---
