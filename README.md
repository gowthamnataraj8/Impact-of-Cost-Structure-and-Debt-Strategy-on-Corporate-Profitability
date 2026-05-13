# Impact-of-Cost-Structure-and-Debt-Strategy-on-Corporate-Profitability
 Analysis of corporate profitability using SEC financial data, panel regression, and machine learning techniques.
# Corporate Profitability Analysis Using ML

## Overview
This project analyses the impact of cost structure and debt strategy on corporate profitability using SEC Financial Statement datasets, econometric analysis, and machine learning techniques.

The study combines traditional financial analysis with modern data-driven approaches to evaluate how operational and financing decisions affect firm performance.

---

## Objectives
- Analyse the relationship between cost structure and corporate profitability
- Examine the effect of debt strategy on firm performance
- Build a panel dataset from SEC financial filings
- Compare econometric and machine learning models
- Identify the most influential financial variables affecting profitability

---

## Dataset
Source:
- SEC Financial Statement Data Sets (XBRL-based corporate filings)

Files used:
- `num.txt`
- `sub.txt`

Time Period:
- 2016–2026

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Linearmodels
- Jupyter Notebook

---

## Data Processing Workflow
1. Extract SEC quarterly datasets
2. Filter important XBRL financial tags
3. Clean and preprocess data
4. Create financial ratios
5. Build panel dataset
6. Train econometric and machine learning models
7. Evaluate model performance

---

## Financial Variables

### Dependent Variable
- Return on Assets (ROA)

### Independent Variables
- Cost Structure
- Debt Ratio

### Control Variables
- Firm Size
- Revenue Growth

---

## Econometric Model
Fixed Effects Panel Regression:

ROA_it = β₀ + β₁(CostStructure_it) + β₂(DebtRatio_it) + β₃(Size_it) + β₄(Growth_it) + ε_it

---

## Machine Learning Model
Model Used:
- Random Forest Regressor

Evaluation Metrics:
- RMSE
- R² Score

---

## Key Findings
- Cost structure positively affects profitability
- High debt ratios negatively impact firm performance
- Random Forest achieved better predictive performance
- Econometric models provided stronger interpretability

---

## Project Structure
```bash
├── main.ipynb
├── dissertation.docx
├── README.md
├── requirements.txt
└── .gitignore
