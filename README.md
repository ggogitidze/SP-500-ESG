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
    - [Question 1](#question-1)
    - [Question 2](#question-2)
    - [Question 3](#question-3)
    - [Question 4](#question-4)
    - [Question 5](#question-5)
- [Visualizations](#visualizations)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Files](#files)
- [How to Run](#how-to-run)
- [License](#license)

## Data Sources

- **S&P 500 Constituents Financials**: Financial metrics of S&P 500 companies.
- **S&P 500 ESG Risk Ratings**: ESG risk ratings for S&P 500 companies.

## Objectives

1. **Correlation Analysis**: Examine the correlation between ESG scores and financial metrics.
2. **Hypothesis Testing**: Test hypotheses regarding the impact of ESG scores on financial performance.
3. **Sector Analysis**: Analyze the average earnings per share (EPS) for companies with high and low ESG scores across different sectors.

## Data Preparation

The data cleaning process involved handling missing values, renaming columns for consistency, and merging the datasets on the common identifier (company symbol).

## Analysis and Findings

### Correlation Analysis

- **Correlation Matrix of Financial Metrics and ESG Scores**: A detailed correlation matrix to understand the relationships between different financial metrics and ESG scores.

### Hypothesis Testing

#### Question 1: Is there a significant correlation between Market Cap and Total ESG Risk Score?

**Null Hypothesis (H0)**: There is no significant correlation between Market Cap and Total ESG Risk Score.

**Test Used**: Pearson Correlation

**Results**:
- Correlation coefficient: 0.094
- p-value: 0.067

**Conclusion**: Since the p-value is greater than 0.05, we fail to reject the null hypothesis. There is no significant correlation between Market Cap and Total ESG Risk Score.

```python
import scipy.stats as stats

# Calculate the Pearson correlation coefficient and p-value
corr, p_value_corr = stats.pearsonr(updated_df['Market Cap'], updated_df['total_esg_risk_score'])
print(f'Correlation between Market Cap and Total ESG Risk Score: {corr}, p-value: {p_value_corr}')
