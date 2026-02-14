# Retail Customer Retention Analytics – Adidas
## 📌 Project Overview

This project focuses on analyzing customer retention, churn behavior, loyalty impact, and Customer Lifetime Value (CLV) for Adidas retail operations using Power BI.

The objective is to identify high-value customers, understand churn drivers, evaluate promotion effectiveness, and derive actionable insights to improve retention strategy.

## 📄 Detailed Project Report:


## 🎯 Business Objectives

Measure and monitor Churn Rate, Repeat Rate, and CLV

Identify high-value and at-risk customers

Evaluate promotion and loyalty program effectiveness

Analyze store and channel performance

Provide strategic recommendations for customer retention

## 🛠 Tools & Technologies

Power BI

Power Query (Data Cleaning & Transformation)

DAX (Measures & Calculated Columns)

Data Modeling

## 📊 Project Workflow
### 1️⃣ Data Modeling & Cleaning

Created Membership_Duration using DATEDIFF

Extracted Transaction Year and Transaction Month

Structured relationships between:

Customer Demographics

Transactions

Store Data

### 2️⃣ Churn & Retention Metrics

Churn Rate Formula:

Churn Rate = Churned Customers / Total Customers


Built measures for:

Churned Customers

Total Customers

Repeat Customers

Visualized churn by:

Region

Income Group

Channel (Online/Store)

Loyalty Tier

Funnel Analysis:
Total Customers → Repeat Customers → Churned Customers

### 3️⃣ Repeat Purchase Analysis

Customer segmentation based on transaction count:

0–3 → Low Tier

4–8 → Mid Tier

9+ → High Tier

Compared purchase frequency by:

Region

Age Group

Loyalty Tier

Identified most purchased categories by loyal customers:

Apparel

Accessories

### 4️⃣ Promotion & Loyalty Impact

52.70% transactions had promotions applied

Compared:

Avg purchase amount (With vs Without Promotion)

Churn rate across loyalty tiers

Points Earned vs Redeemed

### 5️⃣ Store & Channel Performance

Merged store dataset with transaction data

Analyzed:

Avg transaction amount by store type

Churn rate by store type

Correlation between store opening year & retention

Correlation insight:
Retention shows strong positive relationship with store maturity.

### 6️⃣ Customer Lifetime Value (CLV)

CLV Formula:

CLV = Total Spend / Membership Duration (Years)


Segmented customers into:

Low CLV

Medium CLV

High CLV

Visualized:

CLV vs Days Since Last Purchase

CLV by Loyalty Tier & Region

## 📈 Final Dashboard Structure

The Power BI report contains 4 pages:

### 🔹 Page 1: Executive KPIs

Churn Rate KPI

CLV KPI

Repeat Rate KPI

Trend analysis by Membership Duration

### 🔹 Page 2: Loyalty & Promotion Impact

Promotion usage by loyalty tier

Customer count by product category

### 🔹 Page 3: Store & Channel Insights

Store type vs region performance

Channel preference analysis

### 🔹 Page 4: Customer Segmentation

Churned vs Repeat vs High-Value customers

Income, region, and channel segmentation

## 🔍 Key Insights
✅ Customers to Prioritize

Elite and Premium loyalty tier customers (especially franchise store customers)

High purchase frequency

Strong revenue contribution

Redemption behavior indicates engagement opportunity

⚠ Underperforming Channels

Online and Store channels within Elite loyalty segment show weaker retention trends.

## 🚀 Loyalty Program Recommendation

Increase reward points for repeat purchases

Offer targeted discounts to elite-tier customers

Improve balance between points earned vs redeemed to reduce churn

## 📌 Business Impact

This analysis enables:

Data-driven retention strategy

Targeted marketing interventions

Optimization of loyalty programs

Identification of high-value customer segments

Improved channel-level performance monitoring
