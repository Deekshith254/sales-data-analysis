# Part A — Excel tasks 1–4

Open **`Sales_Data_Analysis.xlsx`** and work through each task below.

**Data file (optional download):** [Kaggle sales dataset](https://www.kaggle.com/datasets/vinothkannaece/sales-dataset) → `sales_data.csv` in the `data/` folder.

## Task 1 — Cleaning

- Remove duplicate `Product_ID` / full rows if duplicate transactions  
- Fix missing values and date/number formats  
- Document findings in a short “Data cleaning log” sheet  

## Task 2 — Calculated columns

| Column | Formula idea |
|--------|----------------|
| Total Cost | `=Quantity_Sold * Unit_Cost` |
| Profit | `=Sales_Amount - Total_Cost` or use unit profit × qty |
| Profit Per Unit | `=Unit_Price - Unit_Cost` (after discount logic if applied in sheet) |

## Task 3 — Date & category

- **Year** / **Month** from `Sale_Date`  
- **Sales category** band from `Sales_Amount` (e.g. Low / Medium / High)  

## Task 4 — Pivot tables

Build pivots for:

- Region  
- Product_Category  
- Sales_Rep  
- Customer_Type  

Summarize **Sales_Amount**, **Profit**, and/or **Quantity_Sold**. Note 2–3 performance insights in a short summary.

Python **Part B & C** and GitHub submission: [python-sales-analysis](https://github.com/Deekshith254/python-sales-analysis).
