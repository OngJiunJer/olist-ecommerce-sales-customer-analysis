# 📊 Data Analytics Findings & Actionable Insights
### Olist E-Commerce · Sales, Customer Satisfaction & Delivery Performance

> **Prepared for:** Stakeholder Review  
> **Scope:** Sales Overview · Customer Satisfaction · Delivery Performance

---

## 🗂️ Table of Contents

- [Executive Summary](#-executive-summary)
- [Master Finding](#-master-finding)
- [Finding 01 — Delivery Delay & Customer Satisfaction](#-finding-01--delivery-delay-is-the-1-driver-of-customer-dissatisfaction)
- [Finding 02 — Northeast Regional Logistics Failure](#-finding-02--northeast-region-has-systemic-logistics-failures)
- [Finding 03 — Missed Seasonal Marketing Opportunity](#-finding-03--seasonal-marketing-opportunity-missed-in-2018)
- [Finding 04 — Weekend Demand Gap](#-finding-04--weekend-demand-gap-represents-recoverable-revenue)
- [Finding 05 — High-Value Customer Dissatisfaction](#-finding-05--high-value-customers-have-the-lowest-satisfaction)
- [Finding 06 — Cross-State Freight Margin Pressure](#-finding-06--cross-state-freight-creates-structural-margin-pressure)
- [Consolidated Action Plan](#-consolidated-action-plan)

---

## 📌 Executive Summary

| Metric | Value |
|---|---|
| 💰 Total Revenue Analysed | **R$16.99M** |
| ⭐ Satisfaction Gap (Delayed vs On-Time Orders) | **1.70 stars** |
| 🔄 Recoverable Revenue Potential | **~R$632K** |
| 📅 Year-on-Year Growth (2017 → 2018) | **+20.3%** |
| 🚚 Cross-State Orders | **64.2% of all orders** |

---

## ⚡ Master Finding

> ### Delivery Performance is the Central Lever of Business Performance
>
> Every major satisfaction gap, revenue risk, and regional underperformance traces back to logistics.  
> Fixing delivery **simultaneously improves** customer ratings, reduces 1-star reviews, protects revenue, and strengthens regional results.

---

## 🔴 Finding 01 — Delivery Delay is the #1 Driver of Customer Dissatisfaction

**Priority:** `CRITICAL`

### 🔍 Finding
Delayed orders average **2.56 stars** while on-time orders average **4.26 stars** — a gap of **1.70 stars**. This is the strongest single driver of dissatisfaction across the entire dataset. Post-holiday operational strain (Feb–Mar 2018) reveals a recurring seasonal vulnerability.

### ⚡ Impact
- Low-satisfaction customers are linked to **R$2.53M in revenue** at high churn risk
- 1-star reviews damage platform reputation and reduce new customer acquisition
- Post-holiday backlogs create compounding negative review cycles

### ✅ Action
- Implement **real-time delivery tracking alerts** for customers
- Launch a recovery workflow for all delayed orders: **apology + voucher + re-rating request**
- Target **~25% revenue recovery (~R$632K)** from affected customers
- Set and enforce **SLA KPIs** with all logistics partners

---

## 🔴 Finding 02 — Northeast Region Has Systemic Logistics Failures

**Priority:** `CRITICAL`

### 🔍 Finding
The three lowest-rated states are also the highest-delay regions, confirming a direct logistics-to-satisfaction link:

| State | Avg. Rating |
|---|---|
| AL | ⭐ 3.75 |
| MA | ⭐ 3.76 |
| SE | ⭐ 3.81 |
| Platform Average | ⭐ ~4.1 |

### ⚡ Impact
- Persistent poor experiences risk **permanent brand damage** in these markets
- Without intervention, these regions will not reach platform-average satisfaction
- Regional customer loss compounds over time as negative word-of-mouth spreads

### ✅ Action
- **Audit logistics partners** specifically operating in AL, MA, and SE
- Explore **regional fulfilment hubs** or partnerships with local last-mile delivery providers
- Set **region-specific delivery SLA targets** and review monthly

---

## 🟠 Finding 03 — Seasonal Marketing Opportunity Missed in 2018

**Priority:** `HIGH`

### 🔍 Finding
Black Friday 2017 generated **+54.6% revenue vs October**, reaching **R$1.29M** — the platform's highest-ever monthly figure. No comparable spike occurred in 2018, despite overall baseline growth. Monthly revenue plateaued at **R$1.1M–R$1.3M (Jan–May 2018)**.

### ⚡ Impact
- Estimated **R$200K+ in missed seasonal revenue** in 2018
- Revenue plateau signals a **lack of growth catalysts** beyond organic demand
- Post-holiday operational strain in early 2018 was not anticipated or managed

### ✅ Action
- Build a **formal seasonal campaign calendar** anchored to Black Friday, year-end, and mid-year sale events
- Pre-plan **inventory and logistics capacity** ahead of peak periods to avoid post-holiday operational strain
- Assign dedicated campaign budget with measurable uplift targets

---

## 🟠 Finding 04 — Weekend Demand Gap Represents Recoverable Revenue

**Priority:** `HIGH`

### 🔍 Finding
Weekends consistently average only **134 orders/day vs 174 on weekdays** — a **23% gap** that suggests untapped demand during non-work browsing hours.

| Day Type | Avg. Orders/Day |
|---|---|
| Weekdays | 174 |
| Weekends | 134 |
| Gap | **−23%** |

### ⚡ Impact
- Closing even **50% of this gap** could generate approximately **R$342K in additional annual revenue**
- This is achievable without acquiring new customers — purely through demand stimulation on existing traffic

### ✅ Action
- Launch **weekend-exclusive flash sales** and limited-time promotions
- Test **push notifications and email campaigns** deployed on Friday evenings
- A/B test weekend-specific discount strategies to measure conversion lift

---

## 🟠 Finding 05 — High-Value Customers Have the Lowest Satisfaction

**Priority:** `HIGH`

### 🔍 Finding
Orders above R$500 receive the lowest satisfaction ratings, yet this segment contributes a disproportionately large share of total revenue:

| Order Value | Avg. Rating | % of Customers | % of Revenue |
|---|---|---|---|
| < R$50 | ⭐ 4.19 | Majority | — |
| > R$500 | ⭐ 3.82 | Top 4.5% | **25.3%** |

### ⚡ Impact
- A single bad experience from a high-value customer carries **outsized revenue and reputational risk**
- Expensive and fragile items are more susceptible to shipping damage, delays, and handling issues
- This segment represents the highest **lifetime value risk** if left unaddressed

### ✅ Action
- Introduce a **premium fulfilment tier** for orders >R$500: priority processing, dedicated support, and enhanced packaging
- Send **proactive order status updates** for high-value shipments
- Track satisfaction scores separately for this segment with a dedicated dashboard

---

## 🟡 Finding 06 — Cross-State Freight Creates Structural Margin Pressure

**Priority:** `MEDIUM`

### 🔍 Finding
The current seller and fulfilment distribution creates a structurally inefficient logistics network:

| Metric | Value |
|---|---|
| Same-state shipping cost | R$15 |
| Cross-state shipping cost | R$26 |
| % of orders that are cross-state | **64.2%** |
| % of sellers located in São Paulo | **70.6%** |

### ⚡ Impact
- Persistent **margin erosion at scale** — as order volumes grow, this inefficiency compounds
- Profitability is suppressed even when top-line revenue increases
- Heavy São Paulo concentration creates a **single point of logistics risk**

### ✅ Action
- Develop a **seller diversification strategy** to recruit sellers in high-demand regions outside São Paulo
- Explore **regional warehouse or fulfilment partnerships** to reduce cross-state dependency
- Model the margin improvement achievable at various seller distribution scenarios

---

## 📋 Consolidated Action Plan

| # | Action | Owner | Est. Revenue Impact | Timeline |
|---|---|---|---|---|
| 1 | Deploy delayed-order recovery workflow (apology + voucher + re-rating) | CX / Operations | ~R$632K recovery | 0–30 days |
| 2 | Audit Northeast logistics partners (AL, MA, SE) & set delivery SLAs | Logistics / Ops | Churn prevention | 0–30 days |
| 3 | Launch weekend flash sales & Friday evening campaigns | Marketing | +R$342K/year | 30–60 days |
| 4 | Build seasonal campaign calendar (Black Friday, year-end, mid-year) | Marketing / Supply Chain | +R$200K+ seasonal | 30–90 days |
| 5 | Introduce premium fulfilment tier for orders >R$500 | Operations / Product | Protect 25.3% of revenue | 60–90 days |
| 6 | Recruit sellers in non-SP regions to reduce cross-state freight | Commercial / BD | Long-term margin gain | 6–18 months |

---

> **Note to Stakeholders:** Immediate actions (items 1–2) require minimal investment and can generate measurable ROI within 30–60 days. Strategic actions (item 6) address the root cause of structural inefficiency but require cross-team alignment and a longer planning horizon.

---

*Report generated from Olist E-Commerce dataset analysis · Sales, Customer Satisfaction & Delivery Performance*
