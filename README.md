# RFM-Analysis-for-Customer-Segmentation
Executed a comprehensive RFM customer segmentation project using SQL on a large retail dataset. The analysis identified high-value "Champion" customers, revealing that 15% of the customer base generates over 58% of total revenue. This project delivered a strategic framework for targeted marketing to improve customer retention and ROI.
---
## Business Problem

"Global Retail Inc." is an online retail company with a large, diverse customer base. Their "one-size-fits-all" marketing strategy was inefficient, leading to:
* **Wasted Marketing Spend**: High-value customers were not being treated differently from low-value or inactive customers.
* **Low Customer Engagement**: Generic messaging led to poor campaign performance and low conversion rates.
* **High Customer Churn**: The company could not proactively identify or retain customers who were at risk of leaving.

This project solves this by using RFM (Recency, Frequency, Monetary) analysis to segment customers into distinct groups, enabling a data-driven, personalized marketing approach.

---
## Key Performance Indicators (KPIs) Analyzed

The following KPIs were calculated to diagnose business health and provide actionable insights:
1.  Total Revenue
2.  Average Order Value (AOV)
3.  Average Purchase Frequency
4.  Simplified Customer Lifetime Value (CLV)
5.  New Customer Acquisitions
6.  Cohort Retention Rate
7.  Customer Count per RFM Segment
8.  Revenue Contribution per RFM Segment

---
## Detailed KPI Results

### 1. Total Revenue
This measures the overall sales performance of the business.

| Metric | Value |
| :--- | :--- |
| **Total Revenue** | **₹1.18 Million** |

### 2. Average Order Value (AOV)
This shows the average amount a customer spends in a single transaction.

| Metric | Value |
| :--- | :--- |
| **Average Order Value** | **₹496.98** |

### 3. Average Purchase Frequency
This shows how often, on average, a customer makes a purchase.

| Metric | Value |
| :--- | :--- |
| **Average Purchase Frequency** | **1.85 times** |

### 4. Simplified Customer Lifetime Value (CLV)
This estimates the historical revenue an average customer has generated.

| Metric | Value |
| :--- | :--- |
| **Simplified CLV** | **₹919.37** |

### 5. New Customer Acquisitions
This tracks the number of new customers acquired per month.

| Acquisition Month | New Customers |
| :--- | :--- |
| **2009-12** | **955** |
| **2010-01** | **331** |

### 6. Cohort Retention Rate
This tracks the percentage of new customers who return in subsequent months.

| Acquisition Month | New Customers | Month 1 Retention | Month 2 & 3 Retention |
| :--- | :--- | :--- | :--- |
| **2009-12** | 955 | **~30%** | **0%** |

### 7. Customer Count per RFM Segment
This KPI shows the size of each customer persona group after segmentation.

| RFM_Segment | Customer_Count |
| :--- | :--- |
| At-Risk | 236 |
| Champions | 192 |
| Other | 168 |
| Hibernating | 131 |
| Loyal Customers | 127 |
| Promising | 115 |
| Potential Loyalists | 93 |
| Customers Needing Attention| 86 |
| New Customers | 70 |
| Lost | 68 |

### 8. Revenue Contribution per RFM Segment
This crucial KPI shows the monetary value each segment brings to the business.

| RFM_Segment | Total_Revenue | Revenue_Percentage |
| :--- | :--- | :--- |
| **Champions** | **₹690,252.81** | **58.38%** |
| Other | ₹115,650.68 | 9.78% |
| Loyal Customers | ₹100,042.49 | 8.46% |
| Customers Needing Attention| ₹87,156.93 | 7.37% |
| At-Risk | ₹58,792.81 | 4.97% |
| Promising | ₹42,833.46 | 3.62% |
| Lost | ₹29,701.62 | 2.51% |
| Potential Loyalists | ₹27,071.62 | 2.29% |
| Hibernating | ₹21,328.20 | 1.80% |
| New Customers | ₹9,482.43 | 0.80% |

---
## Overall Insights & Recommendations

The analysis provides several clear, actionable insights that can directly shape the company's strategy:

1.  **The 80/20 Rule is in effect**: The most critical insight is that the **"Champions"** segment, while only comprising **192 customers (~15% of the base)**, generates a massive **58.38%** of the total revenue. This confirms that a small group of high-value customers is vital to the business's success.

2.  **High Churn Risk is Confirmed**: The cohort analysis revealed a severe retention problem (0% retention after Month 1). The RFM analysis validates this by showing a large number of customers in the **"At-Risk" (236)**, **"Hibernating" (131)**, and **"Lost" (68)** segments. The business is failing to convert new customers into loyal ones.

3.  **Low Engagement is Widespread**: The low overall purchase frequency (1.85 times) is reflected in the segmentation results. A significant portion of the customer base falls into low-frequency categories, representing a huge opportunity for growth if they can be nurtured effectively.

### Recommendations

* **Nurture the Champions**: Implement a VIP loyalty program for the "Champions" segment. Offer them exclusive benefits, early access to new products, and personalized communication to ensure their continued loyalty.

* **Re-engage At-Risk Customers**: Launch targeted win-back campaigns for the "At-Risk" and "Hibernating" segments. Use personalized discounts and recommendations based on their past purchases to encourage them to return.

* **Develop Potential Loyalists**: For "Potential Loyalists" and "Promising" customers, create a nurturing email sequence to build a stronger relationship and encourage their next purchase, converting them into "Loyal Customers."
