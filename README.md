# Minor_Project_2
# 💰 Transaction Spending Analysis

A Python-based data analysis project that cleans, categorizes, and analyzes transaction data to understand spending patterns, vendors, categories, and monthly trends.

## 📌 Project Overview

This project analyzes a transaction dataset containing debit and credit transactions.

The main goal is to transform raw transaction data into meaningful insights such as:

- Spending by category
- Spending by vendor
- Monthly spending trends
- Top spending vendors
- Savings rate
- Spending concentration
- Vendor and category distribution

The project uses **Python, Pandas, Matplotlib, and Jupyter/Google Colab** for data processing and analysis.

---

## 🚀 Core Features

### 1. Data Cleaning & Preprocessing

The raw transaction data is cleaned and prepared for analysis.

Operations include:

- Handling missing values
- Standardizing transaction descriptions
- Removing duplicate transactions
- Converting dates into proper date format
- Preparing transaction amounts and types

### 2. Vendor Extraction

Vendor names are extracted from transaction descriptions using keyword-based matching.

Examples include:

- Swiggy
- Zomato
- Amazon
- Flipkart
- Ola
- Uber
- Rapido
- DMart
- BMTC
- Myntra
- Zerodha
- Groww

The final vendor extraction resulted in:

- **1,310 transactions**
- **48 unique vendors**
- **0 uncategorised transactions**

### 3. Category Tagging

Extracted vendors are mapped into spending categories.

Categories include:

- Food Delivery
- Transport
- Groceries
- Shopping
- Dining/Cafes
- P2P Transfers
- Utilities
- Investments
- Entertainment
- Subscriptions
- Cash Withdrawal
- Rent

Final category verification:

| Category | Transactions |
|---|---:|
| Food Delivery | 344 |
| Transport | 272 |
| Groceries | 187 |
| Shopping | 187 |
| Dining/Cafes | 126 |
| P2P Transfers | 72 |
| Utilities | 40 |
| Investments | 23 |
| Entertainment | 18 |
| Subscriptions | 18 |
| Cash Withdrawal | 17 |
| Rent | 6 |

No transactions were left under `Other`.

### 4. Spending Overview

The project calculates important financial metrics.

| Metric | Value |
|---|---:|
| Total Credits | ₹509,774 |
| Total Debits | ₹1,678,901 |
| Net Savings | -₹1,169,127 |
| Savings Rate | -229.34% |

The negative savings rate occurs because total debit spending is significantly higher than total credits in the dataset.

### 5. Monthly Trend Analysis

Monthly spending is calculated using debit transactions.

The analysis identifies:

- Monthly spending
- Highest spending month
- Lowest spending month
- Month-over-month changes
- Biggest monthly increase
- Biggest monthly decrease

Key findings:

- **Highest spending month:** August 2024 — ₹41,383
- **Lowest spending month:** April 2024 — ₹5,246
- **Biggest increase:** December 2024 — 382.96%
- **Biggest decrease:** April 2024 — -80.26%

### 6. Vendor Analysis

Vendor-level spending is analyzed to identify the vendors responsible for the highest spending.

#### Top 10 Vendors

| Rank | Vendor | Spending |
|---:|---|---:|
| 1 | Amazon | ₹328,530 |
| 2 | Zerodha | ₹210,000 |
| 3 | Flipkart | ₹177,510 |
| 4 | Rent | ₹108,000 |
| 5 | Swiggy | ₹95,523 |
| 6 | P2P Transfer | ₹71,189 |
| 7 | Myntra | ₹69,529 |
| 8 | Zomato | ₹55,316 |
| 9 | DMart | ₹46,662 |
| 10 | Cash Withdrawal | ₹45,500 |

### 📊 Spending Concentration

The top 5 vendors account for:

**₹919,563**

out of total spending of:

**₹1,678,901**

This represents:

**54.77% of total spending**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Google Colab

---

