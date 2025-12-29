# 🏨 Hotel Performance Management — Power BI Data Story

## 📌 Business Context
A **hotel chain** operating two types of properties:
- **City Hotels**
- **Resort Hotels**

aims to better **monitor and steer the performance of its hotels** in order to:
- identify **revenue growth levers**,
- optimize **operational capacity** (especially parking),
- and better understand **demand trends and seasonality**.

Management needs a **clear, decision-oriented BI dashboard** to support strategic and operational decisions.


## 🎯 Business Challenges Addressed
The dashboard answers three key business questions:

### 1️⃣ Is hotel revenue growing year over year?
- Revenue evolution over time
- Comparison between **City Hotels** and **Resort Hotels**
- Identification of growth phases and slowdowns

### 2️⃣ Should we increase parking capacity?
- Analysis of guests arriving with personal vehicles
- Detection of demand patterns and peak periods
- Decision support for **infrastructure investment**

### 3️⃣ What trends can we observe in the data?
- Seasonality analysis (ADR, nights, discounts)
- Relationship between price, volume, and time
- Better anticipation of demand fluctuations


## 🔄 Data Workflow (End-to-End BI Approach)
This project follows a complete **Business Intelligence lifecycle**, from raw data to actionable insights.

### 1️⃣ SQL – Data Preparation (SSMS)
- Selection of relevant analytical fields
- Data cleaning (nulls, inconsistencies)
- Initial aggregations
- Structuring data for downstream analytics

> Goal: deliver **reliable and analysis-ready data**


### 2️⃣ Power Query – Data Transformation
- Data normalization (dates, categories)
- Creation of business logic and indicators
- Preparation of analytical tables
- Model optimization before loading

> Goal: transform raw data into **business-ready information**


### 3️⃣ Power BI – Data Modeling & Visualization
- Performance-oriented data model
- DAX measures for key KPIs:
  - Revenue
  - Average Daily Rate (ADR)
  - Total Nights
  - Average Discount
  - Parking Demand (Car Spaces)
- Interactive dashboards with filters:
  - Hotel Type
  - Country
  - Time period

> Goal: deliver a **clear and actionable data story**


## 📊 Key KPIs
- **Revenue**
- **Average Daily Rate (ADR)**
- **Total Nights**
- **Average Discount**
- **Parking Demand**


## 🧠 Insights & Improvement Opportunities
Based on the analysis, several improvement areas can be identified:

### 🔹 Revenue Management
- Dynamic pricing adjustments based on seasonality
- Differentiated pricing strategies for City vs Resort hotels
- Smarter discount management during high-demand periods

### 🔹 Operations & Capacity Planning
- Cost–benefit analysis for parking expansion
- Better resource allocation during peak periods

### 🔹 Strategic Steering
- Year-over-year performance monitoring
- Early detection of risk periods (revenue drop or overcapacity)
- Data-driven decision-making for management teams


