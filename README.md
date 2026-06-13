# Sales & Profitability Analysis – Superstore Dataset

## Overview
This project analyzes a retail Superstore dataset to identify which product 
categories, sub-categories, and individual products are driving — or hurting — 
profitability. The goal was to move beyond "what are our sales?" to "where 
should the business focus or cut back?" — a Business Analyst-style approach 
rather than a purely descriptive one.

## Business Questions Explored
1. Which category sells the most and is most profitable (revenue vs. profit)?
2. Which sub-categories drive or hurt profitability within each category?
3. Are there sub-categories with high revenue but poor profit?
4. Which specific products are causing these issues?
5. Which products are actively loss-making?
6. Which products have unhealthy low margins?
7. Which products are the strongest profit contributors, worth promoting further?

## Key Findings
- **Furniture** generates nearly as much revenue as Office Supplies and 
  Technology (~$742K) but earns drastically less profit (~$18K, ~2.5% margin 
  vs ~17% for the other two categories).
- This gap is driven almost entirely by **Tables** (-$17.7K loss, -8.6% margin) 
  and **Bookcases** (-$3.5K loss) — losses are spread across most products in 
  these sub-categories, suggesting a structural pricing/cost issue rather than 
  a few bad SKUs.
- In contrast, **Machines** and **Supplies** are mostly healthy but are dragged 
  down by a small number of high-loss products (e.g., Cubify CubeX 3D Printer: 
  -$8,880 on $11K sales). Removing/repricing ~10-15 SKUs could meaningfully 
  improve these sub-categories.
- The **Canon imageCLASS 2200 Advanced Copier** is the single largest profit 
  contributor ($25.2K profit, ~41% margin) and, along with other copiers, 
  binders, and shredders, represents the business's strongest product mix — 
  good candidates for increased marketing focus.

## Recommendations
1. Conduct a pricing/cost review of the **Tables** sub-category — losses are 
   widespread, not isolated.
2. Reassess or discontinue the worst-performing **Bookcase** SKUs (~25-28 of 
   ~50 products are loss-making).
3. Remove or reprice the ~10-15 specific loss-making products in **Machines** 
   and **Supplies** to unlock the profitability already present in these 
   categories.
4. Increase marketing/inventory focus on top performers like the **Canon 
   imageCLASS 2200**, **Ativa V4110MDD Shredder**, and **Zebra ZM400 Printer** 
   — proven high-margin, high-revenue products.

## Tools Used
- Excel (Pivot Tables, Charts) for data exploration and analysis
- Raw dataset: Sample Superstore dataset (Kaggle)

## Files
- `Sample - Superstore.csv` — raw data
- `Q1-Q3 analysis.xlsx` — category and sub-category profitability
- `Q4-Q6 analysis.xlsx` — product-level loss-makers and low-margin items
- `Q7 analysis.xlsx` — top profit-contributing products

## Files
- `Sales Analysis.xlsx` — single workbook containing:
  - Raw data sheet
  - Sheet 2-5: Analysis for Q1-Q7 (pivot tables, charts, and findings)
