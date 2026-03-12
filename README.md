# E-Commerce Sales Analysis

Python data analysis project exploring e-commerce sales performance, customer concentration and international market opportunities.

---

## Project Overview

This project analyses e-commerce transaction data to identify key drivers of revenue and customer behaviour.

The analysis explores:

- Revenue distribution across products
- Geographic sales performance
- Customer concentration and high-value customers
- Monthly revenue trends and seasonality

The goal is to generate insights that could help an e-commerce business improve inventory management, marketing strategy, and customer retention.

---

# Dataset

The dataset contains **541,000+ transactions** from an e-commerce retailer and includes:

- Invoice number
- Product SKU
- Product description
- Quantity purchased
- Invoice date
- Unit price
- Customer ID
- Country

The dataset used in this analysis is the **Online Retail dataset**.

Source:  
https://archive.ics.uci.edu/ml/datasets/Online+Retail

Due to file size limitations the dataset is not included in this repository.

---

# Tools Used

Python  
Pandas  
Matplotlib  
Jupyter Notebook  

---

# Key Analyses

## Revenue by Country

This chart shows where the business generates the majority of its revenue.

![Revenue by Country](images/revenue_by_country.png)

### Insight

The United Kingdom dominates sales, but several international markets show meaningful demand.

---

## International Market Opportunity

Removing the UK reveals the strongest international markets.

![International Markets](images/international_markets.png)

### Insight

The Netherlands, Ireland, Germany, and France are the most significant non-UK markets.

These countries represent strong candidates for **international expansion or targeted marketing**.

---

## Monthly Revenue Trend

![Monthly Revenue](images/monthly_revenue_trend.png)

### Insight

Revenue rises significantly in the final quarter of the year, indicating strong **seasonality and holiday demand**.

Businesses could prepare by:

- Increasing inventory
- Scaling advertising
- Improving fulfilment capacity

---

## Product Revenue Concentration (Pareto Analysis)

![Product Pareto](images/product_pareto_analysis.png)

### Insight

Revenue is distributed across a wide range of products rather than being concentrated in a few best sellers.

The top 10 products generate only a small share of total revenue, indicating that many SKUs contribute meaningfully to overall sales.

This suggests the business relies on a **broad product catalogue rather than a few dominant items.**

---

## Customer Revenue Concentration

![Customer Pareto](images/customer_pareto_analysis.png)

### Insight

Approximately **27% of customers generate 80% of revenue**.

This suggests opportunities for:

- Customer loyalty programs
- Targeted retention strategies
- VIP customer segmentation

---

# Business Recommendations

Based on the analysis:

### Maintain a diverse product portfolio

Revenue is distributed across many products rather than concentrated in a few best sellers.

This suggests the business benefits from maintaining a **broad product range** rather than relying on a small number of hero products.

Possible strategies include:

- Ensuring consistent availability across a wide SKU range
- Monitoring long-tail products that contribute steady revenue
- Avoiding over-concentration on a small set of items

---

### Expand high-potential international markets

Countries such as:

- Netherlands  
- Ireland  
- Germany  
- France  

show strong demand outside the UK.

---

### Prepare for seasonal demand spikes

Revenue increases significantly during Q4, suggesting strong seasonal demand leading up to the holiday period.

Planning inventory levels and marketing campaigns ahead of this period could help maximise sales during peak demand.

---

### Retain high-value customers

Customer analysis shows that a relatively small proportion of customers contributes a large share of revenue.

Focusing on retaining these customers could improve long-term profitability.

Possible strategies include:

- Loyalty programs
- Personalised offers
- Customer retention campaigns

---
