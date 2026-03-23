# 📊 Sales & Promotions Analytics — AtliQ Mart

## 📌 Project Overview
AtliQ Mart is a retail chain with 50+ supermarkets across South India. During Diwali 2023 and Sankranti 2024, the company ran multiple promotional campaigns on AtliQ-branded products.

The objective of this project is to evaluate the effectiveness of these promotions and help leadership understand:
- Which promotions generated incremental revenue
- Which promotions increased volume but hurt profitability
- Which stores, cities, and product categories performed best
- How future promotion strategy can be improved

This analysis focuses on incremental impact, not raw sales.

---

## 🎯 Business Objectives
- Determine whether promotions generated incremental revenue or only discounted volume  
- Identify best and worst performing promotions  
- Analyze performance across stores, cities, and categories  
- Evaluate promotion efficiency using discount cost vs revenue lift  
- Support data-driven pricing and promotion decisions  

---

## 🧩 Dataset Description
The project uses a star schema with one fact table and three dimension tables.

### Fact Table
**fact_events**
- store_id  
- campaign_id  
- product_code  
- base_price  
- promo_type  
- quantity_sold_before_promo  
- quantity_sold_after_promo  

### Dimension Tables
- **dim_campaigns** → campaign name, start and end dates  
- **dim_products** → product name and category  
- **dim_stores** → store_id and city  

---

## 🧠 Key Metrics & Concepts
All KPIs are designed to measure incremental impact, not absolute sales.

- After Promo Revenue  
- Baseline Revenue  
- Incremental Revenue  
- Incremental Sold Units  
- IR % (Incremental Revenue %)  
- ISU % (Incremental Sold Units %)  
- Total Discount Cost  
- IR per Discount  
  - Incremental revenue generated per unit of discount given  

---

## 📊 Dashboard Structure
The Power BI report contains three focused pages, each answering a distinct business question.

---

## 🏬 Page 1 — Store View
**Purpose:**  
Analyze promotion performance across cities and individual stores.

**Key Insights:**
- Cities driving the highest incremental revenue  
- Revenue comparison before vs during promotion  
- Top 10 and bottom 10 stores by incremental revenue  

**Visuals:**
- KPI cards  
- Incremental revenue by city  
- Baseline vs After Promo revenue by city  
- Top and bottom performing stores tables  

---

## 🎯 Page 2 — Promotion Type Analysis
**Purpose:**  
Evaluate promotion effectiveness and efficiency.

**Key Insights:**
- Promotion types generating the most incremental revenue  
- High-volume but inefficient promotions  
- Value-destructive promotions  

**Visuals:**
- KPI cards  
- Promotion efficiency matrix (revenue vs volume vs discount cost)  
- Incremental revenue by promotion type  
- Promotion performance summary table  

---

## 📦 Page 3 — Product View
**Purpose:**  
Understand category and product-level performance.

**Key Insights:**
- Categories with highest volume lift  
- Categories driving incremental revenue  
- Top and bottom products by incremental revenue  

**Visuals:**
- Incremental sold units by category  
- Incremental revenue by category  
- Top and bottom products tables  

---

## 🎛️ Interactivity & Usability
- Page navigation buttons for Store, Promotion, and Product views  
- Slicers for Campaign and City (City slicer excluded from Product View)  
- Consistent KPIs across all pages  
- Clean, executive-focused layout  

---

## 🛠 Tools & Technologies
- Power BI  
- DAX for calculated measures  
- Star schema data modeling  

---

## 🧠 Key Takeaways
- Not all promotions are profitable; some increase volume but destroy value  
- Cashback and BOGOF promotions outperform flat discount offers  
- Promotion performance varies significantly by city and product category  
- Incremental analysis is critical for correct promotion evaluation  

---

## 📁 Repository Contents
- Power BI report file  
- Dataset files (CSV)  
- Dashboard screenshots  
- README.md  

---

## 🔗 Related Conceptual Analysis

This project is supported by a foundational analysis of promotion KPIs and business concepts:

👉 https://github.com/tanmay-sahu-411/sales-promotion-analysis

---

## ✅ Project Status
Completed and portfolio-ready.  
Designed to reflect real-world business analytics and decision-making.
