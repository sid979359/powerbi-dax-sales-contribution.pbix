# powerbi-dax-sales-contribution.pbix
DAX practice project demonstrating filter context control using ALL and ALLEXCEPT in Power BI
# Power BI DAX Practice – Sales Contribution Analysis

## Overview
This project is a **DAX-focused Power BI practice exercise** based on a Codebasics assignment.  
The objective is to understand how filter context behaves in Power BI and how to control it using
`CALCULATE()`, `ALL()`, and `ALLEXCEPT()` functions.

The solution is implemented entirely inside a **Power BI (.pbix) file**.

---

## Dataset
- **Source:** `apparels_dataset.xlsx`
- Contains sales data for apparel products with:
  - Category
  - Brand
  - Product
  - Quantity
  - Sale Amount

---

## Objective
1. Create a **Matrix visual** showing:
   - Category-wise sales
   - Total sales (constant, unaffected by category or brand filters)
   - Percentage contribution of each category to total sales

2. Create a **Card visual** that:
   - Shows sales by category
   - Responds **only to category filters**
   - Remains unaffected by brand or product filters

---

## Key DAX Measures Used
The solution demonstrates practical use of:

- `CALCULATE()`
- `ALL()`
- `ALLEXCEPT()`

These functions are used to control filter context and ensure that:
- Total sales remain constant
- Percentage contribution is calculated correctly
- Category-level filtering behaves as expected

All measures are organized inside a dedicated **measure table** for clarity.

---

## File Included
- `solved.pbix`  
  👉 Open this file in **Power BI Desktop** to view the complete solution:
  - Data model
  - DAX measures
  - Matrix and Card visuals

---

## Tools Used
- Power BI Desktop
- DAX (Data Analysis Expressions)

---

## Learning Outcome
Through this exercise, the following concepts were reinforced:
- Difference between row context and filter context
- How `ALL()` removes filters
- How `ALLEXCEPT()` preserves specific filters
- Best practices for organizing measures in Power BI

---

## Notes
- This project focuses on **DAX logic**, not visual design.
- No Power Query transformations were required beyond basic loading.
- The solution is intentionally kept simple to highlight DAX behavior clearly.

powerbi-dax-sales-contribution.pbix
/report.png
