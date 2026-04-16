# Online Retail Customer Value Analysis

## 1. Problem & User
This project examines who the most valuable customers are in an online retail business and what sales patterns support their value.  
It is designed for beginner e-commerce analysts and business students who want a clear, practical, and data-driven understanding of customer value.

## 2. Data
**Dataset:** Online Retail Dataset  
**Source:** UCI Machine Learning Repository  
**Access Date:** 2026.4.15  

The dataset contains transaction-level retail records, including:
- `InvoiceNo`
- `StockCode`
- `Description`
- `Quantity`
- `InvoiceDate`
- `UnitPrice`
- `CustomerID`
- `Country`

These fields make the dataset suitable for customer-level and sales-pattern analysis.

## 3. Methods
The project follows a structured Python workflow:
- data loading and initial inspection
- data cleaning (removing missing and invalid records)
- feature engineering
  - `Revenue = Quantity × UnitPrice`
  - time variables (`Year`, `Month`, `YearMonth`)
- customer-level aggregation
- revenue concentration analysis
- monthly sales trend analysis
- country-level revenue analysis
- insight generation
- interactive recommendation engine for decision support

## 4. Key Findings
- Customer value is unevenly distributed across the customer base.
- A relatively small group of customers contributes a large share of total revenue.
- High-value customers are driven by different purchasing patterns, including frequent transactions and large purchases.
- Sales increase noticeably toward the end of the year, suggesting seasonal demand.
- The business is highly dependent on the UK market, which contributes the majority of total revenue.

## 5. How to Run
1. Download the dataset.
2. Make sure the dataset is placed in the same folder as the notebook, because the code uses a relative file path.
3. Open the Jupyter Notebook.
4. Run all cells from top to bottom.

## 6. Product Link / Demo
**Notebook:** `OnlineRetailCustomerValueAnalysis.ipynb`  
**Demo Video:** [Insert video link here]

## 7. Limitations & Next Steps
### Limitations
- Records with missing `CustomerID` and invalid values were removed.
- Returns and cancellations are excluded from the analysis.
- Potential outliers may still remain in the dataset.
- The dataset covers a limited time period.
- The analysis is descriptive and does not establish causal relationships.

### Next Steps
- extend the workflow to multiple years of retail data
- add product-category analysis
- develop a more advanced customer segmentation model
- improve the recommendation engine with more flexible user inputs
