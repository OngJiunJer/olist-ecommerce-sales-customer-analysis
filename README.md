# 📊 Customer Satisfaction & Sales Analysis
### Using Excel (Power Query) & Power BI

---

## 📌 Project Overview
This project analyzes customer satisfaction and sales performance using the **Brazilian E-Commerce Public Dataset by Olist (Kaggle)**.

The goal is to transform raw, multi-source data into structured datasets and generate meaningful insights through interactive dashboards.

---

## 📂 Dataset
**Source:** Brazilian E-Commerce Public Dataset by Olist (Kaggle)

**Link:** https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=product_category_name_translation.csv

The project uses multiple related tables:

- `olist_orders_dataset`
- `olist_order_reviews_dataset`
- `olist_order_items_dataset`
- `olist_products_dataset`
- `olist_customers_dataset`
- `olist_sellers_dataset`
- `product_category_name_translation`

---

## ⚙️ Methodology

### 1. Data Preparation (Excel - Power Query)
- Imported multiple datasets into Excel  
- Used **Power Query** to:
  - Merge and join tables across different datasets  
  - Combine data into unified views  

- Created two main datasets:
  - **Customer Satisfaction Dataset**
  - **Sales Overview Dataset**

---

### 2. Data Cleaning & Transformation
Performed automated data cleaning using Power Query:
- Removed duplicate records  
- Trimmed and cleaned text fields  
- Removed unnecessary columns  
- Filtered irrelevant or invalid data  
- Standardized data types (date, numeric, text)
- Rename column name

---

### 3. Data Structuring
- Ensured consistency across merged datasets  
- Validated relationships between tables  
- Prepared clean datasets for analysis and visualization  

---

### 4. Data Visualization (Power BI)
- Imported prepared datasets into Power BI  
- Built interactive dashboards to analyze:
  - **Customer satisfaction** (review scores, feedback trends)  
  - **Sales performance** (revenue, orders, product performance)  

- Designed visuals to highlight:
  - Trends and patterns  
  - Performance comparisons  
  - Relationship between customer satisfaction and sales  

---

# 📊 Sales & Customer Analytics — Key Insights (Olist Dataset)

This project analyzes sales performance and customer satisfaction using the Olist e-commerce dataset.  
The insights are divided into two main areas: **Sales Overview** and **Customer Satisfaction**.

---

# 📈 Sales Overview — Key Insights

## 1. Revenue is growing strongly but unevenly
Total revenue reached **R$16.99M**, with **2018 outperforming 2017 by 20.3%** (R$7.69M → R$9.25M).  
Monthly revenue stabilized around **R$1.1M–R$1.3M (Jan–May 2018)**, indicating a plateau and lack of new growth drivers.

---

## 2. Black Friday 2017 was the biggest revenue event
November 2017 increased **54.6% over October**, reaching the highest monthly revenue at **R$1.29M**.  
No similar spike occurred in 2018, suggesting missed seasonal marketing opportunities.

---

## 3. No dominant category — but Watches & Gifts stand out
The top 3 categories contribute only **25% of total revenue**, showing strong diversification.  
However, **Watches & Gifts** has the highest average order value (**R$233 vs R$164 platform average**), making it a high-margin category.

---

## 4. Freight cost is a structural margin pressure
- Cross-state shipping: **R$26**
- Same-state shipping: **R$15**
- **64.2% of orders are cross-state**
- 70.6% of sellers are located in São Paulo

👉 This creates a structural logistics inefficiency that impacts profitability.

---

## 5. Weekend demand gap represents lost revenue
Weekends average **134 orders/day vs 174 on weekdays**.  
Closing this gap could generate approximately **R$342K additional annual revenue** through promotions and flash sales.

---

# 😊 Customer Satisfaction — Key Insights

## 6. Delivery delay is the most critical factor
Delayed orders average **2.56 stars**, while on-time orders average **4.26 stars**.  
👉 This creates a **1.70-star gap**, the strongest driver of customer dissatisfaction.

---

## 7. Highly polarised customer ratings
- 57.8% of reviews are **5-star**
- 11.5% are **1-star**

👉 This indicates extreme experiences rather than average performance issues.

---

## 8. R$2.53M revenue linked to 1-star customers
Low-satisfaction customers represent a significant revenue segment.  
A recovery strategy (voucher + apology + re-rating request) could potentially recover **~25% (~R$632K)**.

---

## 9. High-volume categories have lower satisfaction
- **Bed Bath Table**: 10,160 orders, **3.91 stars**
- **Health & Beauty**: strong revenue + **4.18 stars**

👉 High volume does not guarantee high satisfaction — operational quality varies by category.

---

## 10. Higher spend = lower satisfaction
- Orders < R$50 → **4.19 stars**
- Orders > R$500 → **3.82 stars**

👉 High-value customers (top 4.5%) contribute **25.3% of revenue** but require premium service handling.

---

## 11. Northeast region shows systemic logistics issues
Low-performing states:
- AL: 3.75 stars  
- MA: 3.76 stars  
- SE: 3.81 stars  

👉 These regions also have high delivery delays, indicating a logistics-driven satisfaction problem.

# 🚚 Delivery Performance — Key Insight

## 📌 Delivery performance is the master variable

Delivery performance is the **single most important driver** of customer satisfaction and overall business performance.

---

## 🔍 Key Findings

### 1. Logistics drives almost all satisfaction issues
Delayed orders score **2.56 stars**, while on-time deliveries score **4.26 stars**.  
👉 This **1.70-star gap** shows that delivery speed and reliability dominate customer perception.

---

### 2. Regional performance mirrors logistics problems
The lowest-scoring states:
- AL  
- MA  
- SE  

👉 These are also the **highest-delay regions**, confirming that poor logistics directly impacts satisfaction at a regional level.

---

### 3. Post-holiday performance drop is logistics-related
A noticeable **score decline in Feb–Mar 2018** aligns with post-holiday order backlogs, suggesting operational strain after peak demand periods.

---

### 4. High-value orders face more risk
There is an inverse relationship between order value and satisfaction.  
👉 Expensive and fragile items are more likely to be affected by shipping damage or delays.

---

## 📊 Core Insight

> Fixing delivery performance improves **every key metric simultaneously**:
- Customer satisfaction 📈  
- Review scores 📊  
- Retention rate 🔁  
- Revenue stability 💰  

---

## 🎯 Conclusion

Delivery is not just an operational metric — it is the **central lever of business performance**.

Improving logistics efficiency directly leads to:
- Higher customer satisfaction
- Reduced 1-star reviews
- Better revenue protection
- Stronger regional performance
