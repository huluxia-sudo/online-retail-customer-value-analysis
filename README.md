# Online Retail Customer Value Analysis

## 📌 Project Overview

This project develops a simple **data-driven customer value analysis product** for an online retail business.

It transforms raw transaction-level data into structured analysis, generates insights, and provides **basic decision support through an interactive recommendation layer**.

The main objective is to identify high-value customers and understand the patterns that drive their contribution to revenue.


## 🎯 Analytical Problem

**Who are the most valuable customers, and what sales patterns support their value?**


## 👤 Target Users

This project is designed for:

- beginner e-commerce analysts  
- business students  

who want a clear and practical understanding of customer value using real transaction data.

The product helps users move from raw data to interpretable insights without requiring advanced analytical skills.


## 📊 Dataset

- **Dataset:** Online Retail Dataset  
- **Source:** UCI Machine Learning Repository  
  https://archive.ics.uci.edu/dataset/352/online%2Bretail?utm_source  
- **Access Date:** 2026.4.15  

The dataset contains transaction-level records, including:

- customer IDs  
- product details  
- quantities  
- prices  
- timestamps  

This makes it suitable for analysing both customer value and sales performance.


## ⚙️ Methodology

The project follows a structured analytical workflow:

1. Data loading and initial inspection  
2. Data cleaning (removing missing and invalid records)  
3. Feature engineering  
   - Revenue = Quantity × UnitPrice  
   - Time variables (Year, Month, YearMonth)  
4. Exploratory data analysis  
5. Insight generation  
6. Decision support through a recommendation engine  


## 🔍 Key Analyses

The analysis focuses on four core components:

- Customer-level analysis (identifying top customers)  
- Revenue concentration analysis  
- Monthly sales pattern analysis  
- Country-level revenue distribution  


## 💡 Key Findings

- **Customer value is unevenly distributed**  
  A relatively small group of customers contributes a large share of total revenue.  

- **High-value customers follow different purchasing patterns**  
  Some generate value through frequent transactions, while others contribute through large purchases.  

- **Sales show seasonal patterns**  
  Revenue increases significantly between September and November, suggesting demand peaks.  

- **The business is highly dependent on the UK market**  
  The United Kingdom accounts for approximately 82% of total revenue, indicating strong geographic concentration.  


## 🧠 Recommendation Engine (Decision Support Layer)

The notebook includes a simple **interactive decision-support module**.

Users can:

- view high-level business recommendations  
- explore detailed analytical results  
- navigate between different perspectives (customers, revenue concentration, time, and geography)  

This transforms the analysis into a lightweight, user-facing data product.


## ⚠️ Limitations

- Records with missing `CustomerID` and invalid values were removed  
- Returns and cancellations are excluded  
- Potential outliers remain in the dataset  
- The dataset covers a limited time period  
- The analysis is descriptive and does not establish causal relationships  


## ▶️ How to Run

1. Download the dataset  
2. Place the dataset in the same folder as the notebook  
3. Open the Jupyter Notebook  
4. Run all cells from top to bottom  


## 📁 Project Structure

- `OnlineRetailCustomerValueAnalysis.ipynb` — main analysis notebook  
- `README.md` — project documentation  


## 🎥 Demo Video

[Insert video link here]


## 🤖 AI Disclosure

AI tools (ChatGPT) were used to assist with:

- code structuring  
- explanation refinement  
- writing support  

All analysis decisions, interpretations, and final outputs were completed by the author.
