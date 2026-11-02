# Loan Risk Analysis Dashboard<img width="954" height="534" alt="Screenshot 2026-10-27 112933" src="https://github.com/user-attachments/assets/df8ba10c-db69-438a-a935-b8408748c738" />



Interactive Power BI dashboard for analyzing credit and loan portfolio risk.  
Designed to help lenders and risk analysts monitor default exposure, loan grades, borrower income, and loan purposes.

**Visual By:** Peter Kess

---

## Project Overview

This dashboard provides a clear executive view of loan portfolio performance and risk.  
It tracks key metrics across **32.5K+ applicants** and helps identify high-risk segments for better lending decisions.

### Business Objectives
- Monitor overall portfolio health and default exposure  
- Identify high-risk loan grades and loan purposes  
- Compare income profiles of defaulted vs non-defaulted borrowers  
- Support data-driven credit risk decisions  

---

## Key Performance Indicators (KPIs)

| Metric                  | Value      | Description                              |
|-------------------------|------------|------------------------------------------|
| Loan Applicants         | 32.581K    | Total number of loan applications        |
| Default Cases           | 7K         | Number of loans that defaulted           |
| Default Rate %          | 21.82%     | Percentage of loans that defaulted       |
| Average Loan Amount     | 9.59K      | Average size of loans issued             |
| Average Interest Rate   | 11%        | Average interest rate across the portfolio |

---

## Dashboard Visuals

### 1. Loan Grade Risk Analysis by Loan Amount
Line chart showing total loan volume by credit grade (B → G).  
Higher grades hold significantly larger loan amounts.

### 2. Sum of Loan Intent by Loan Amount
Horizontal bar charts ranking loan purposes by total amount:
- EDUCATION
- MEDICAL
- VENTURE
- PERSONAL
- DEBTCONSOLIDATION
- HOMEIMPROVEMENT

### 3. Average Person Income by Loan Amount
Donut chart showing the distribution of borrower income relative to loan size.

### 4. Average Person Income by Loan Status
Donut chart comparing average income of defaulted borrowers versus non-defaulted borrowers.

---

## Key Insights

- Default rate stands at **21.82%** — indicating elevated portfolio risk.
- Grades **B** and **A** dominate in total loan volume.
- **Education** and **Medical** are the top two loan intents by amount.
- Borrowers who default generally have lower average income compared to non-defaulters.

---

## Tech Stack

- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)
- **Power Query** (data cleaning & transformation)
- Single fact table data model focused on loan records

---

## Data Fields Used

| Field                | Description                          |
|----------------------|--------------------------------------|
| loan_id              | Unique loan identifier               |
| person_income        | Annual income of the applicant       |
| loan_amount          | Loan amount                          |
| loan_intent          | Purpose of the loan                  |
| loan_grade           | Risk grade (A–G)                     |
| loan_status          | 0 = Non-default, 1 = Default         |
| loan_int_rate        | Interest rate (%)                    |

---

## How to Use

1. Clone this repository
2. Open the `.pbix` file in Power BI Desktop (or recreate using the DAX measures)
3. Connect your own loan dataset if needed
4. Explore the interactive visuals and filters

---

## Author

**Peter Kess**  
Visual Designer & Data Analyst

---


