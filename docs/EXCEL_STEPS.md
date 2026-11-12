# Excel work — matches résumé bullets

These are the steps used when building `Sales_Data_Analysis.xlsx` in Advanced Excel (Cloud Vision Technologies).

## Cleaning

1. Load raw sales extract.  
2. **Remove duplicates** on Order ID.  
3. **Missing values:** fill or drop per column (e.g. quantity; blank region flagged then filled).

## Calculated columns (résumé: Profit, Total Cost, Sales Categories)

| Column | Logic |
|--------|--------|
| Revenue | Quantity × Unit Price × (1 − Discount %) |
| Total Cost | Quantity × Unit Cost |
| Profit | Revenue − Total Cost |
| Sales Categories | Band from margin % (e.g. High / Medium / Low performer product mix) |

## Pivot tables

- **Rows:** Region × Category; **Values:** Sum of Profit, Sum of Revenue  
- **Rows:** Sales Representative; **Values:** Profit margin %, order count  
- **Filters:** Date period, category

The saved workbook is the deliverable; this doc is the written record of the same work claimed on the résumé.
