# Tunda Box – Junior Data Analyst Assessment

## Project Overview

This repository contains my completed Junior Data Analyst assessment. The assessment demonstrates my understanding of SQL, Python, data cleaning, spreadsheet formulas, statistics, A/B testing, and business analysis.

## Assessment Document

[View the completed Junior Data Analyst Assessment on Google Drive](https://docs.google.com/document/d/16JPZYd3hE99O3n7k2NwQlNIRME8a5mNaLY9cp85G7cs/edit?usp=sharing)
## Files in This Repository

- `assessment.ipynb` – Jupyter Notebook containing the Python code, SQL queries, calculations, and written responses.
- `README.md` – Project overview, assessment responses, methodology, and thought process.

## Part 2: SQL and Python

### S1. Orders by Status
Counted distinct orders grouped by status:
- Completed: 16
- Cancelled: 2
- Refunded: 2

### S2. Revenue by City
Calculated completed revenue by city after removing duplicate orders, excluding missing amounts, and standardising city names.

- Kisumu: KES 187,100
- Nairobi: KES 20,650
- Mombasa: KES 5,150
- Nakuru: KES 3,300

### S3. Customers Who Never Ordered
Identified customers 109 and 110 using a LEFT JOIN.

### S4. Repeat Purchase Rate
Identified 4 repeat customers out of 10 customers, giving a repeat purchase rate of 40%.

I counted distinct completed orders, including completed orders with missing amounts.

### S5. Month-on-Month Revenue

| Month | Revenue (KES) | Change |
|---|---:|---:|
| June | 9,000 | — |
| July | 6,800 | -24.44% |
| August | 192,000 | +2,723.53% |
| September | 10,300 | -94.64% |

Duplicate orders were removed, and cancelled, refunded, and missing-amount transactions were excluded.

## Part 3: Data Quality and Spreadsheets

### D1. Data Quality Audit
Identified duplicate orders, missing amounts, unusual transaction values, inconsistent city names, invalid customer references, and order statuses that should be excluded from completed revenue calculations.

### D2. Spreadsheet Formulas
Used SUMIFS to calculate completed M-Pesa revenue and XLOOKUP to retrieve customer city information.

### D3. Mean or Median
Selected the median because it is less affected by the unusually high KES 185,000 transaction. The median completed order value was KES 2,450.

## Part 4: Statistics

### T1. P-values and Causation
Explained how p-values help assess evidence against a no-effect assumption and why correlation does not necessarily establish causation. Recommended a randomised experiment to test whether SMS messages influence customer spending.

### T2. A/B Testing
- Current version: 5% conversion rate.
- New version: 6% conversion rate.
- Improvement: 1 percentage point, or 20% relative increase.

Recommended checking statistical significance and test reliability before launching the new version.

## Part 5: Business Case

Compared September and October conversion rates:

- September: 5.20%
- October: 4.34%

Found that paid social traffic increased significantly as a share of total visitors, while conversion rates within both marketing channels improved slightly.

Recommended investigating paid traffic quality and campaign performance before pausing paid social.

## Part 6: Questions for the Employer

Prepared questions about the role's responsibilities, tools and technologies, mentorship opportunities, and expectations during the first three months.

## Thought Process and Methodology

My approach to the assessment was to:

1. Understand the structure and purpose of the available data.
2. Inspect the datasets and identify possible quality issues.
3. Use SQL to answer questions involving filtering, grouping, joins, aggregation, and window functions.
4. Use Python and pandas to calculate conversion rates and analyse business performance.
5. Apply data cleaning techniques such as deduplication, handling missing values, and standardising text.
6. Interpret the results in business terms and provide practical recommendations.
7. Consider limitations in the data before making conclusions.

## Tools and Technologies

- Python
- SQL
- SQLite
- Pandas
- NumPy
- Google Colab
- GitHub
- Google Docs

## Conclusion

This assessment strengthened my practical understanding of data analysis, data quality, statistical interpretation, and business decision-making. It also helped me practise communicating analytical findings and recommendations clearly.
