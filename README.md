# Loan Default Risk Analysis | Power BI

## Project Overview

This project analyzes **255,347 loan records** to identify patterns and characteristics associated with loan default risk.

The analysis examines borrower demographics, financial characteristics, employment information, credit profiles, and loan attributes to understand how these factors vary between defaulting and non-defaulting borrowers.

The project was developed using **Microsoft Power BI** and focuses on transforming a large loan dataset into an interactive business intelligence report.

---

## Business Problem

Financial institutions need to understand the characteristics associated with loan defaults in order to monitor credit risk and make better-informed lending decisions.

This project explores questions such as:

- What is the overall loan default rate?
- How does default risk vary across employment types?
- How do income and loan amount differ between defaulting and non-defaulting borrowers?
- How does credit score relate to loan characteristics and default behavior?
- How do loan purposes and borrower demographics vary across the portfolio?
- How has loan default activity changed over time?
- Which borrower and financial characteristics appear most associated with default?

---

## Objectives

The main objectives of this analysis were to:

1. Analyze the overall loan portfolio and default rate.
2. Compare financial characteristics of defaulting and non-defaulting borrowers.
3. Examine default patterns across demographic and employment segments.
4. Analyze loan amounts across credit-score categories.
5. Evaluate changes in loan activity and defaults over time.
6. Identify relationships between borrower characteristics and financial risk indicators.
7. Present the findings through an interactive Power BI dashboard.

---

## Dataset

The dataset contains **255,347 loan records** and **20 variables**.

### Key Variables

| Category | Variables |
|---|---|
| Borrower Profile | Age, Education, Marital Status |
| Financial Profile | Income, Loan Amount, Interest Rate, DTI Ratio |
| Credit Profile | Credit Score, Number of Credit Lines |
| Employment | Employment Type, Months Employed |
| Loan Information | Loan Purpose, Loan Term, Loan Date |
| Household Factors | Mortgage, Dependents, Co-signer |
| Outcome | Default |

The dataset covers loan records from **2013 to 2018**.

---

## Tools & Technologies

- **Microsoft Power BI**
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Exploratory Data Analysis

---

## Power BI Dashboard

The report is organized into three analytical sections.

### 1. Loan Default Overview

This page provides a high-level view of:

- Loan amount by purpose
- Average income by employment type
- Average loan amount by age group
- Default rate by year
- Default rate by employment type

### 2. Applicant Demographics & Financial Profile

This section examines:

- Loan amounts across credit-score categories
- Credit-score segments
- Loan amount by credit-score range
- Mortgage and dependent status
- Loan amount by education level

### 3. Financial Risk Metrics

This section focuses on:

- Year-over-year loan amount changes
- Year-over-year default loans
- Loan amount by credit-score category and marital status
- Decomposition-tree analysis of financial risk factors

---

## Key Findings

### Overall Default Rate

The dataset has an overall default rate of approximately **11.6%**.

### Employment Type

Default rates vary considerably by employment type.

- Unemployed borrowers have the highest observed default rate at approximately **13.6%**.
- Full-time borrowers have the lowest observed default rate at approximately **9.5%**.

### Income and Loan Amount

Defaulting borrowers have a lower average income and a higher average loan amount than non-defaulting borrowers.

| Metric | Non-Default | Default |
|---|---:|---:|
| Average Income | ~$83.9K | ~$71.8K |
| Average Loan Amount | ~$125.4K | ~$144.5K |
| Average Interest Rate | ~13.2% | ~15.9% |

### Credit & Financial Risk

Defaulting borrowers also show differences in credit score and interest rate compared with non-defaulting borrowers.

These patterns indicate that borrower financial capacity, credit profile, and loan characteristics are important dimensions to examine when assessing loan-default risk.

> These findings represent relationships observed in the dataset and should not be interpreted as evidence that any single factor independently causes loan default.

---

## Business Recommendations

Based on the observed patterns, financial institutions could consider:

- Monitoring higher-risk borrower segments more closely.
- Using income, credit profile, loan amount, and DTI ratio together when evaluating borrower risk.
- Paying particular attention to applicants with combinations of weaker financial indicators.
- Monitoring default trends across employment and demographic segments.
- Using interactive risk dashboards to support portfolio monitoring and management decisions.

These recommendations are analytical considerations rather than a substitute for formal credit-risk models or lending policies.

---

## Project Structure

```text
loan-default-risk-analysis/
│
├── README.md
│
├── data/
│   └── Loan_default.csv
│
├── powerbi/
│   └── Loan_Default_Risk_Analysis.pbix
│
├── screenshots/
│   ├── loan-default-overview.png
│   ├── applicant-demographics.png
│   └── financial-risk-metrics.png
│
└── documentation/
    └── data-dictionary.md
```

---

## Skills Demonstrated

- Data Analysis
- Exploratory Data Analysis
- Power BI
- Power Query
- DAX
- Data Modeling
- Dashboard Development
- KPI Analysis
- Financial Analysis
- Credit Risk Analysis
- Segmentation
- Time-Series Analysis
- Business Intelligence

---

## Disclaimer

This project is intended for educational and portfolio purposes.

The analysis identifies patterns within the provided dataset and does not constitute a credit-scoring model, financial advice, or a recommendation for actual lending decisions.
