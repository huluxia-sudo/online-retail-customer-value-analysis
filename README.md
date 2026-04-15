# Online Retail Customer Value Analysis

## 📌 Project Overview

This project provides a structured, data-driven analysis of customer value in an online retail business.

The main objective is to identify the most valuable customers and understand the patterns that drive their contribution to revenue.

## 🎯 Analytical Problem

Who are the most valuable customers, and what sales patterns support their value?

## 👤 Target Users

This project is designed for beginner e-commerce analysts and business students who seek a clear and practical understanding of customer value using real data.

## 📊 Dataset

- Dataset: Online Retail Dataset  
- Source: UCI Machine Learning Repository  
- Access Date: [Insert Date]

The dataset contains transaction-level records, including customer IDs, product details, quantities, prices, and timestamps.

This makes it suitable for analysing both customer behaviour and sales performance.

## ⚙️ Methodology

The analysis follows a structured Python workflow:

1. Data loading and initial inspection  
2. Data cleaning (removing invalid and missing records)  
3. Feature engineering  
   - Revenue = Quantity × UnitPrice  
   - Time variables (Year, Month, YearMonth)  
4. Exploratory data analysis  

## 🔍 Key Analyses

The project consists of four main analytical components:

1. Top customers by revenue  
2. Revenue concentration analysis  
3. Monthly sales trend analysis  
4. Country-level revenue distribution  

## 💡 Key Findings

1. **Customer value is unevenly distributed**  
   A relatively small group of customers contributes a large share of total revenue.

2. **High-value customers follow different purchasing patterns**  
   Some generate value through frequent transactions, while others contribute via large one-off purchases.

3. **Sales performance is stronger toward the end of the year**  
   Revenue increases significantly between September and November, suggesting seasonal demand.

4. **The business is highly dependent on the UK market**  
   The United Kingdom accounts for approximately 82% of total revenue, indicating strong geographic concentration.

## ⚠️ Limitations

- Records with missing CustomerID and invalid values were removed  
- Returns and cancellations are excluded  
- Potential outliers remain in the dataset  
- The dataset covers a limited time period  
- The analysis is descriptive and does not establish causal relationships  

## ▶️ How to Run

1. Download the dataset  
2. Open the Jupyter Notebook  
3. Run all cells from top to bottom  

## 📁 Project Structure

- `OnlineRetailCustomerValueAnalysis.ipynb` — main analysis notebook  
- `README.md` — project documentation  

## 🎥 Demo Video

[Insert video link here]


## 🤖 AI Disclosure

AI tools (ChatGPT) were used to assist with code structuring, explanation refinement, and writing support. All analysis decisions and interpretations were made by the author.
