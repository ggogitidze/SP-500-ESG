# ESG and Financial Performance Analysis of S&P 500 Companies

## Overview

This project aims to analyze the relationship between ESG (Environmental, Social, and Governance) scores and the financial performance metrics of companies listed in the S&P 500. The analysis focuses on understanding correlations and significant differences across various sectors, utilizing hypothesis testing and visualization techniques.

## Table of Contents

- [Overview](#overview)
- [Data Sources](#data-sources)
- [Objectives](#objectives)
- [Data Preparation](#data-preparation)
- [Analysis and Findings](#analysis-and-findings)
  - [Correlation Analysis](#correlation-analysis)
  - [Hypothesis Testing](#hypothesis-testing)
- [Visualizations](#visualizations)
- [Key Findings](#key-findings)
- [Full report](#full-report)

## Data Sources

- **S&P 500 Constituents Financials**: Financial metrics of S&P 500 companies.
- **S&P 500 ESG Risk Ratings**: ESG risk ratings for S&P 500 companies.

## Objectives

1. **Correlation Analysis**: Examine the correlation between ESG scores and financial metrics.
2. **Hypothesis Testing**: Test hypotheses regarding the impact of ESG scores on financial performance.
3. **Sector Analysis**: Analyze the average earnings per share (EPS) for companies with high and low ESG scores across different sectors.

## Data Preparation

The data cleaning process involved handling missing values, renaming columns for consistency, and merging the datasets on the common identifier using PostgreSQL, Excel, python.

## Analysis and Findings

### Correlation Analysis

- **Correlation Matrix of Financial Metrics and ESG Scores**: A detailed correlation matrix to understand the relationships between different financial metrics and ESG scores.

### Hypothesis Testing

### Visualizations
The following visualizations were created using Power BI to support the findings:

- Scatter Plot: Correlation between Market Cap and Total ESG Risk Score.
- Scatter Plot: Impact of Environment Risk Score on Earnings/Share.
- Bar Chart: Mean Governance Risk Scores across Sectors.
- Table: Average Earnings/Share for Low ESG Scores by Sector.
- Table: Average Earnings/Share for High ESG Scores by Sector.
- Correlation Matrix: Financial Metrics and ESG Scores.

### Key Findings
- There is no significant correlation between Market Cap and Total ESG Risk Score.
- The Environment Risk Score has a significant correlation with Earnings/Share.
- The mean Governance Risk Scores are different across different sectors.
- There is a significant difference in Dividend Yield between companies with high and low ESG Risk Percentiles.
- The Social Risk Score does not significantly predict the Price/Earnings ratio.

### Full Report

[Open Project Documentation](S&P500-ESGDataAnalyticsReport.docx)
