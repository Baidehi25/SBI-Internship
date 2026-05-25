# Customer Lifecycle Classification & Product Recommendation System
### Data Analytics Internship — State Bank of India

---

## Overview

This project was developed as part of a Data Analytics Internship at **State Bank of India (SBI)**, one of India's largest public sector banks. The core objective was to move beyond rigid, date-based customer segmentation and instead build a **dynamic, behaviour-driven classification system** that maps customers to their actual financial lifecycle stage.

> **Goal:** Develop and implement a classifier that utilizes transaction history, demographic data, and account/product service profiling — enabling delivery of more relevant products and high-frequency engagement tailored to each customer's actual stage of life and financial behaviour, irrespective of arbitrary day counts.

---

## Problem Statement

Traditional customer segmentation at banks often relies on crude metrics such as the number of days since account opening or product purchase. This approach fails to capture the **true financial maturity and behaviour** of a customer, leading to:

- Irrelevant product recommendations
- Missed up-sell/cross-sell opportunities
- Low customer engagement and wallet share
- Poor alignment between customer needs and bank offerings

This project addresses these gaps by building a **rule-based recommendation engine** grounded in real behavioural and transactional signals.

---

## Objectives

- Classify customers based on their actual financial lifecycle stage using multi-dimensional profiling
- Identify **up-sell and cross-sell** opportunities for targeted financial product offerings
- Surface **fee-based revenue opportunities** by intelligently mapping customer profiles to relevant banking products
- Contribute to the **Customer Lifecycle (CLC)** use case initiative to deepen engagement and grow wallet share

---

## Key Contributions

- **Rule-Based Recommendation Engine** — Designed and implemented decision logic to match customer profiles with the most relevant banking products (e.g., fixed deposits, insurance, mutual funds, credit cards, loans)
- **Behavioural & Transactional Analysis** — Analyzed large-scale customer relationship data to extract patterns across spending, saving, and product usage behaviour
- **Customer Lifecycle (CLC) Use Case** — Contributed to a strategic bank-wide initiative to replace arbitrary day-count segmentation with lifecycle-aware targeting
- **Profile Engineering** — Built structured customer profiles combining transaction data, demographics, and account/product attributes to power the classification model
- **Rule Validation at Scale** — Built and validated recommendation rules across structured datasets with multiple customer relationship attributes

---

## Tech Stack

| Category | Tools / Technologies |
|---|---|
| Language | Python, SQL |
| Data Analysis | Pandas, NumPy, Microsoft Excel |
| Visualization | Matplotlib, Seaborn |
| Data Source | Structured CRM / customer relationship datasets |
| Version Control | Git, GitHub |

---

## Methodology

### 1. Data Collection & Understanding
- Worked with structured datasets containing multiple customer relationship attributes including demographics, account types, transaction history, and product holdings

### 2. Customer Profiling
- Built multi-dimensional profiles combining:
  - **Transaction profiling** — frequency, volume, categories
  - **Demographic profiling** — age, income band, occupation, location
  - **Account/product profiling** — current holdings, tenure, product mix

### 3. Lifecycle Classification
- Engineered classification logic to assign each customer a **lifecycle stage** (e.g., New-to-Bank, Growth, Mature, Dormant) based on behavioural signals rather than arbitrary time thresholds

### 4. Product Recommendation
- Developed rule-based decision trees to match lifecycle stages with relevant product recommendations
- Prioritised **fee-generating products** to surface revenue opportunities for the bank
- Ensured recommendations were personalised, contextual, and actionable

### 5. Validation
- Validated rules against historical data to measure coverage and relevance of recommendations

---

## Key Learnings

- Hands-on experience working with **large-scale banking CRM data**
- Understanding of **customer lifecycle management** in the financial services domain
- Practical knowledge of building **rule-based AI/ML systems** for business use cases
- Exposure to how India's largest public sector bank approaches **data-driven product distribution**
- Gained insight into **up-sell/cross-sell strategies** and revenue engineering in retail banking

---

## ⚠️ Disclaimer

All data used in this project is the property of **State Bank of India** and has been used solely for the purpose of this internship under a confidentiality agreement. No customer data is included or referenced in this repository.
