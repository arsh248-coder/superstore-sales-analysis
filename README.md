# 🏬 Superstore Sales Analysis (Retail Analytics Project)

This project analyzes retail performance using the Superstore dataset to uncover trends in revenue, profit, discounts, customer value, and delivery patterns.  
The focus is on **business insights and data-driven decision making**, not just charts or code.

---

## 🚀 Business Questions Answered
- Which regions generate the most revenue vs profit?
- Which product categories underperform due to discounts?
- What percentage of revenue comes from top customers?
- How do late deliveries affect customer value?
- Which products/regions are best candidates for investment vs scaling down?

---

## 📁 Project Structure
superstore-sales-analysis/
│
├─ data/
│ ├─ raw/
│ │ └─ superstore_sales.csv # original dataset (unchanged)
│ │
│ ├─ processed/ # analysis outputs
│ │ ├─ monthly_sales.csv
│ │ ├─ avg_sales_per_year.csv
│ │ ├─ avg_sales_per_year_region.csv
│ │ ├─ top_products_by_region.csv
│ │ ├─ top10_high_sales_low_discount.csv
│ │ ├─ top_customers_with_delivery.csv
│ │ ├─ bottom_customers_with_delivery.csv
│ │ └─ late_summary.csv
│
├─ notebooks/
│ └─ Superstore_Sales_Analysis.ipynb
│
├─ visuals/
│ └─ dashboard.png # Tableau dashboard export
│
└─ README.md

yaml
Copy code

---

## 📊 Included Processed Files (Why They Matter)
| File Name                            | Purpose / Insight Type                     |
|--------------------------------------|---------------------------------------------|
| monthly_sales.csv                    | Trend analysis by month                    |
| avg_sales_per_year.csv               | Yearly performance comparison              |
| avg_sales_per_year_region.csv        | Region-based strategy planning             |
| top_products_by_region.csv           | Which products win where                   |
| top10_high_sales_low_discount.csv    | Highlights profit loss from discounting    |
| top_customers_with_delivery.csv      | Identifies high-value customer segments    |
| bottom_customers_with_delivery.csv   | Detects revenue-draining customer groups   |
| late_summary.csv                     | Logistics and late delivery impact         |

> These files are intentionally kept to show the **data exploration process**, even if not all are used in the final dashboard.

---

## 📈 Key Insights (Executive Summary)
- West region shows **lower volume but higher profit margins**
- Furniture category loses profit due to **heavy discounting**
- Top 10% of customers contribute **~35–40% of total revenue**
- Standard Class shipments have the **highest late delivery rate**
- 2014 has the **highest recorded sales**, but stability improves by 2016
- Several products sell well but produce **negative profit due to discounts**

---

## 📉 Dashboard Preview (Tableau)
📁 Located in: `visuals/dashboard.png`

![Dashboard Preview](visuals/dashboard.png)

---

## 🛠 Tools & Libraries
- Python (`pandas`, `matplotlib`, `seaborn`, `numpy`)
- Jupyter Notebook
- Tableau / Power BI (data visualization)

---

## 🧠 Project Outcome
This project demonstrates:
- Real business-context analytics
- KPI storytelling for non-technical stakeholders
- Customer, product, and logistics segmentation
- Tableau dashboard reporting
- Clean repo organization with **raw vs processed data**

---

## 📬 Contact
GitHub: https://github.com/arsh248-coder
KPI storytelling for non-technical stakeholders

Customer, product, and logistics segmentation

Dashboard reporting using Tableau

Clean repo organization with raw + processed data separation
