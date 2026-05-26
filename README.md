# Northwind-Traders-Sales-Analysis
# 📊 Northwind Traders — Sales Performance Analysis
### Power BI Dashboard | July 2013 – May 2015

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Period](https://img.shields.io/badge/Period-July%202013%20–%20May%202015-blue?style=for-the-badge)

## 📌 Project Overview

Northwind Traders is a fictional wholesale food trading company 
that sells specialty food products to restaurants, retailers and 
distributors across Europe, North America and South America. 

This project delivers a **three-page interactive Power BI dashboard** 
analysing the company's sales performance across two years of 
transactional data — covering product performance, order behaviour 
and overall revenue trends. The goal was to transform raw sales data 
into clear, actionable business intelligence that leadership could 
use to make informed decisions about products, customers and regions.

---

## 🎯 Business Questions Answered

This analysis was designed to answer the following key business 
questions:

**Revenue & Products**
- Which products generate the most revenue for the business?
- Which products are underperforming and at risk?
- Which product categories drive the most value?
- How does discounting affect net revenue across categories?

**Orders & Customers**
- When do order volumes peak and drop throughout the year?
- Which product categories drive the most order demand?
- What proportion of customers are repeat buyers vs one-time buyers?
- What is the average order value per product category?

**Sales Performance**
- Who are the top customers by quantity purchased?
- How does monthly net revenue trend across the year?
- Which region generates the most revenue?
- What is the overall impact of discounts on gross revenue?


## 📈 Dashboard Pages

### Page 1 — Product Performance

<img width="1170" height="680" alt="Product Performance" src="https://github.com/user-attachments/assets/bfd243cd-d1ee-417d-afeb-de431e472303" />


**Key Metrics at a Glance:**
| Metric | Value |
|--------|-------|
| Total Product Revenue | £1.27M |
| Total Products Sold | 51K units |
| Avg Revenue per Product | £16.44K |

**What this page shows:**

**Top 10 Products by Revenue** — Côte de Blaye dominates with 
£141K in revenue, nearly double the second-placed Thüringer 
Rostbrat at £80K. The top 10 products account for a 
disproportionate share of total revenue highlighting a classic 
long-tail distribution where a small number of products drive most 
of the value.

**Top 10 Products by Units Sold** — Camembert Pierrot leads 
volume with 1,577 units sold followed closely by Raclette 
Courdava at 1,496 units. Importantly the highest revenue products 
are not necessarily the highest volume products — Côte de Blaye 
does not appear in the top 10 by units, suggesting it commands a 
significantly higher unit price.

**Revenue by Product Category** — Beverages lead all categories 
at £268K followed by Dairy Products at £235K. Grains & Cereals 
is the lowest performing category at £96K suggesting potential 
for either rationalisation or investment depending on margin data.

**Bottom 5 Products by Revenue** — Chocolade, Geitost, Genen 
Shushi, Laughing Lumberjack Lager and Longlife Tofu all generate 
under £2.4K in revenue. These products should be reviewed for 
discontinuation or promotional intervention.

**Discount Impact on Revenue by Category** — The dual-axis chart 
reveals that categories with higher average discount rates do not 
necessarily show proportionally higher net revenue suggesting 
discounting is not always driving incremental sales volume 
effectively.

---

### Page 2 — Order Analysis

<img width="1170" height="682" alt="Order Analysis" src="https://github.com/user-attachments/assets/442ffbdd-c081-4f27-b036-ee672134fc2f" />


**Key Metrics at a Glance:**
| Metric | Value |
|--------|-------|
| Total Orders | 830 |
| Total Customers | 91 |
| Orders per Customer | 9.1 |
| Avg Order Value | £1.53K |

**What this page shows:**

**When do order volumes change?** — Order volumes follow a clear 
seasonal pattern. Volume peaks in March and April at 103 and 105 
orders respectively before dropping sharply to a low of 30 in June. 
Recovery is gradual through the second half of the year reaching 79 
in December. This pattern suggests strong Q1 demand followed by a 
significant mid-year slowdown that the business should plan 
inventory and staffing around.

**Which products drive order demand?** — Beverages dominate order 
frequency with 354 orders followed by Dairy Products at 303 and 
Confections at 295. Produce generates the fewest orders at 129 
despite being a standard food category suggesting either limited 
product range or lower customer demand in this segment.

**Orders by Customer Type** — A striking 96.58% of all orders 
come from repeat customers with only 3.42% from one-time buyers. 
This indicates exceptionally strong customer retention and loyalty 
but also highlights a risk — the business is heavily dependent on 
a small base of loyal customers with very limited new customer 
acquisition.

**AOV by Product Category** — Beverages have the highest average 
order value at £323 followed by Dairy Products at £283. Grains & 
Cereals has the lowest AOV at £115. The colour-coded summary table 
uses traffic light formatting to immediately communicate which 
categories are high, medium and low value.

---

### Page 3 — Sales Performance

<img width="1170" height="675" alt="Sales_Performance" src="https://github.com/user-attachments/assets/515cc152-b114-432f-a176-e184e5bacef2" />


**Key Metrics at a Glance:**
| Metric | Value |
|--------|-------|
| Net Revenue | £1.27M |
| Gross Revenue | £1.35M |
| Discount Rate | 7% |
| Avg Revenue per Customer | £14.22K |

**What this page shows:**

**Top 8 Customers by Quantity Sold** — Save-a-lot Markets and 
Ernst Handel are joint top customers at 5K units each followed by 
QUICK-Stop at 4K units. The remaining five customers all purchased 
between 1K and 2K units. The heavy concentration at the top two 
customers represents a customer concentration risk — losing either 
account would have a material impact on revenue.

**Monthly Net Revenue Trend** — Revenue peaks in April at £177K 
before declining sharply to a low of £36K in June — consistent 
with the order volume drop seen on Page 2. Recovery builds steadily 
through the second half of the year closing at £117K in December. 
The dotted baseline at £105.48K represents the average monthly 
revenue making it easy to identify above and below average months 
at a glance.

**Revenue by Region** — Europe is by far the dominant region 
generating £775K which represents approximately 61% of total net 
revenue. North America contributes £319K at around 25% and South 
America accounts for £172K at approximately 14%. The business is 
heavily European-dependent which represents both a strength in 
terms of established relationships and a risk in terms of 
geographic concentration.

**Revenue vs Discount Impact** — The donut chart breaks total 
gross revenue into three components. Net revenue accounts for 
50% of the pie, non-discounted revenue for 29.65% and discounted 
revenue for 20.35%. The overall 7% discount rate is relatively 
modest but the composition suggests there is an opportunity to 
analyse whether the discounted segment is generating proportional 
volume lift.

---

## 🔍 Key Business Insights

### 1. Product Concentration Risk
The top 3 products — Côte de Blaye, Thüringer Rostbrat and 
Raclette Courdavault — account for a disproportionate share of 
total revenue. Strong performance from a small number of products 
creates supply chain and revenue risk if any of these products 
face availability issues or competitive pressure.

### 2. Seasonal Demand Pattern
Order volumes and revenue both follow a consistent pattern — 
strong Q1, sharp June trough, steady H2 recovery. This pattern 
should drive inventory planning, staffing decisions and 
promotional timing to smooth out the mid-year revenue gap.

### 3. Customer Retention is Exceptional — But Acquisition is Low
96.58% repeat customer rate is a remarkable retention figure. 
However with only 91 total customers and minimal new customer 
acquisition, the business should invest in expanding its customer 
base to reduce concentration risk across both products and accounts.

### 4. Europe Drives the Business
61% of revenue comes from Europe. While this reflects strong 
regional relationships, North America and South America together 
represent significant untapped potential. Targeted growth 
strategies in these regions could meaningfully diversify revenue.

### 5. Discounting Needs Review
A 7% overall discount rate with 20.35% of revenue coming from 
discounted orders warrants closer analysis. The discount impact 
chart on Page 1 shows that higher discount rates do not always 
correlate with higher net revenue by category suggesting some 
discounting may be margin dilutive rather than volume generative.

### 6. Bottom Products Need a Decision
The five lowest revenue products all generate under £2.4K across 
the entire analysis period. A clear decision framework should be 
applied — promote, reprice or discontinue — to free up sales and 
inventory resources for higher performing SKUs.


## 🛠️ Tools and Techniques Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard design and visualisation |
| Power Query | Data cleaning and transformation |
| DAX | Calculated measures and KPI metrics |
| Data Modelling | Relationships between sales, product and customer tables |
