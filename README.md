# 🏠 Housing Market Analysis Dashboard  
*Tech Stack:* BigQuery | Power BI | SQL | DAX  

## 📌 Project Overview
This project analyzes housing market trends across multiple regions using historical sales data.  
The objective is to understand *regional performance, pricing behavior, sales types, and growth trends* through interactive Power BI dashboards backed by BigQuery.

The analysis focuses on *sales performance, **market overview, and **pricing dynamics*, enabling data-driven insights for business and policy decision-making.

---

## 🎯 Objectives
- Analyze *sales distribution by region*
- Compare *offer price vs purchase price*
- Track *YoY sales growth by sales type*
- Identify *key influencers* affecting purchase prices
- Evaluate *average price per square meter (SQM)* by region
- Provide a *12-month sales performance snapshot*

---

## 🗂️ Data Pipeline
1. *Data Source*
   - Historical housing sales data (region, price, SQM, sales type, time)

2. *Data Storage*
   - Uploaded and stored in *Google BigQuery*

3. *Data Preparation*
   - Data cleaning and transformation using *SQL*
   - Date hierarchies (Year, Quarter, Month)
   - Region and sales-type categorization

4. *Visualization*
   - Connected *Power BI to BigQuery*
   - Created calculated measures using *DAX*
   - Built interactive dashboards

---

## 📊 Dashboards Description

### 1️⃣ Sales Performance Dashboard
*Key Insights:*
- *Sales by Region*
  - Zealand leads total sales, followed by Jutland
  - Bornholm contributes the least
- *Offer to SQM Ratio by Sales Type*
  - Regular sales have the highest SQM ratio
  - Auctions show relatively lower SQM value
- *Key Influencers*
  - Age group (16–40) has a noticeable impact on purchase price
- *Average Price per SQM*
  - Zealand has the highest average price per SQM
  - Bornholm shows comparatively lower pricing

*Visuals Used:*
- Funnel charts
- Donut chart
- Key Influencers visual
- Data table with time hierarchy

---

### 2️⃣ House Market Overview Dashboard
*Key Metrics:*
- *Units Sold (Latest Year & Quarter):* 77
- *12-Month Sales:* 13 billion

*Insights:*
- *Median Sales Price Change*
  - Jutland shows positive growth
  - Bornholm reflects a price decline
- *Offer Price vs Purchase Price*
  - Strong linear relationship indicating rational market pricing
- *YoY Sales Growth by Sales Type*
  - Auctions show positive growth
  - Family sales experience the largest decline

*Visuals Used:*
- Bar charts
- Line & area charts
- Scatter plot
- KPI cards

---

## 🧠 Key Business Insights
- Regional disparities strongly influence housing prices
- Sales type significantly impacts YoY growth trends
- Offer prices are reliable predictors of final purchase prices
- Younger buyer segments influence price reductions
- Zealand remains the most premium housing market

---

## 🛠️ Tools & Technologies
- *Google BigQuery* – Data storage & querying  
- *Power BI* – Data visualization & dashboards  
- *SQL* – Data transformation  
- *DAX* – KPI & measure creation  

---

## 🚀 Future Enhancements
- Add *price forecasting* using time-series models
- Include *buyer demographics analysis*
- Integrate *machine learning models* for price prediction
- Automate data refresh with scheduled pipelines

---

## 📁 Project Status
✅ Completed  
📊 Dashboards published and interactive  

---

## 👩‍💻 Author
*Tanya Pandey*  
B.Tech CSE (AI & ML)  
Skills: Data Analytics | Power BI | BigQuery | SQL | Python
