# 🔍 Olist Customer Dissatisfaction Analysis

A Power BI dashboard that analyzes customer dissatisfaction on the Olist platform — identifying the operational drivers of negative customer experiences and prioritizing improvement initiatives based on customer business value.

---

## 📊 Project Snapshot

|                     |                                                       |
| ------------------- | ----------------------------------------------------- |
| **Domain**          | E-commerce                                            |
| **Dataset**         | Brazilian E-Commerce Public Dataset by Olist          |
| **Scale**           | 99K+ Orders · 96K+ Customers                          |
| **Analysis Period** | Sep 2016 – Aug 2018                                   |
| **Tools**           | Power BI · Power Query · DAX                          |
| **Focus**           | Customer Experience Analytics · Operational Analytics |

---

## 📈 Dashboard Preview

🔗 [View the live dashboard](https://lnkd.in/gea766am)

![Executive Overview](images/page1_overview.jpg)

---

## 🎯 Business Context

Although **14.7% of Olist orders receive negative reviews (1–2★)**, the underlying drivers of customer dissatisfaction remain unclear. Moreover, not all dissatisfied customers contribute equally to business value.

This project aims to answer:

* Which customer segments should Olist prioritize?
* What operational factors drive customer dissatisfaction?
* How do delivery performance, seller quality, and product quality affect customer experience?
* Which business initiatives should be prioritized to maximize customer satisfaction?

---

## 💡 Key Insights

### 🚚 Delivery Performance
Delivery delay is the strongest driver of customer dissatisfaction.
* Orders delivered after **35+ days** receive **9.5×** more negative reviews than orders delivered within 7 days.
* More than **11,600 orders** exceeded the 21-day delivery risk threshold.

### 👥 Customer Value Segmentation
Customer dissatisfaction does not affect all customers equally.
* Only **21% of customers generate 48.2% of total revenue**.
* High-value customer segments exhibit distinct dissatisfaction patterns, requiring differentiated improvement strategies.

### 🛍 Seller & Product Quality
Customer dissatisfaction is concentrated among a relatively small group of sellers and product categories, enabling targeted quality improvement instead of platform-wide interventions.

### 🌎 Regional Performance
North and Northeast Brazil consistently underperform São Paulo in both delivery reliability and customer satisfaction, indicating structural logistics gaps.

---

## 🚀 Business Recommendations

1. **Strengthen delivery reliability** through proactive SLA monitoring, early-warning mechanisms, and carrier capacity planning during peak periods.

2. **Improve seller and product quality management** through performance monitoring while tailoring remediation strategies for high-priority customer segments.

3. **Invest in logistics capabilities across the North and Northeast regions** through expanded carrier partnerships and enhanced fulfillment capacity.

---

## 🛠 Technical Highlights

- **Built a multi-fact dimensional data analytical model** to support cross-functional analysis across orders, reviews, sellers, products, payments, and logistics data.

- **Developed custom DAX measures** to support customer satisfaction analysis, customer value segmentation, delivery performance monitoring, and seller/category risk identification.

- **Developed a rule-based customer value segmentation framework** adapted from RFM principles and validated against K-Means clustering to prioritize high-impact customer groups while maintaining business interpretability.

- **Implemented risk-tiering logic** with minimum-volume thresholds to reduce false positives when identifying high-risk sellers (≥50 orders) and product categories (≥100 orders).

- **Designed benchmark-based regional performance analysis** comparing underperforming states (e.g., AL, MA, CE) against São Paulo (SP), the platform's delivery-performance benchmark with a 5.9% late-delivery rate.

- **Applied an Impact-vs-Effort prioritization framework** to translate analytical findings into actionable business recommendations.

---

## 📂 Project Files

- ```Olist_Report.pdf``` – Dashboard report for quick viewing.
- ```Olist_Customer_Dissatisfaction_Dashboard.pbix``` – available upon request.
