# Cafe Sales Data Analytics Portfolio

Two connected data analytics projects completed as part of the DecodeLabs Data Analytics track. Both use one practice dataset, [*Cafe Sales - Dirty Data for Cleaning Training*](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training) (10,000 transactions from a fictional cafe), and tell one story: **messy export -> audited dataset -> business insights**.

| | Project 1: Data Cleaning | Project 2: Exploratory Data Analysis |
|---|---|---|
| **Question** | Can the owner trust this export? | What is the data actually telling us? |
| **Tools** | Microsoft Excel (formula-driven workbook with audit sheet) | Python, pandas, seaborn, scipy, Jupyter |
| **Headline result** | 10,000 rows in, 10,000 out; 0 duplicate IDs; 0 badly formatted dates; 17-entry change log | Revenue is driven by price, not popularity; no strong seasonality; in-store and takeaway behave alike |
| **Deliverables** | Workbook, cleaned CSV, PDF change log | Notebook, executive summary PDF, charts and tables |
| **Go to** | [project-1-data-cleaning](project-1-data-cleaning) | [project-2-eda](project-2-eda) |

## Repository structure

```
cafe-sales-data-analytics/
├── README.md
├── .gitignore
├── project-1-data-cleaning/
│   ├── README.md
│   ├── cafe_sales_cleaning_workbook.xlsx
│   ├── cafe_sales_clean.csv
│   └── cafe_sales_change_log.pdf
└── project-2-eda/
    ├── README.md
    ├── requirements.txt
    ├── cafe_sales_eda.ipynb
    ├── cafe_sales_clean.csv
    ├── cafe_sales_eda_executive_summary.pdf
    ├── key_observations.txt
    ├── figures/   (7 charts)
    └── tables/    (4 summary tables)
```

## Skills demonstrated

Data cleaning and validation, missing-value imputation strategy, audit design, exploratory data analysis, outlier detection, hypothesis testing, data visualisation, and communicating findings to non-technical readers.

## Note on the data

This is a practice dataset for a fictional business, so the projects demonstrate method rather than real business outcomes. Check the Kaggle page for the dataset's licence and terms of use.
