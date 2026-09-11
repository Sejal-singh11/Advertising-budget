# Advertisement Sales Prediction using Machine Learning

## Project Overview

This project analyzes the relationship between advertising expenditure and product sales using Machine Learning.

The dataset contains advertising budgets for **TV, Radio, and Newspaper** across 200 markets, with **Sales** as the target variable.

The main objective is to develop a model that can predict Sales based on advertising budgets and identify which advertising channels have the strongest relationship with Sales.

## Project Workflow

The project follows an end-to-end Machine Learning workflow:

1. Problem Definition
2. Data Loading
3. Data Understanding
4. Data Cleaning and Quality Checks
5. Exploratory Data Analysis (EDA)
6. Correlation Analysis
7. Linear Regression
8. Multiple Linear Regression
9. Train-Test Split
10. Model Evaluation
11. Residual Analysis
12. Statistical Analysis
13. Business Insights
14. Final Visualization Dashboard

## Dataset

The dataset contains four variables:

| Variable | Description |
|----------|-------------|
| TV | TV advertising budget |
| Radio | Radio advertising budget |
| Newspaper | Newspaper advertising budget |
| Sales | Product sales |

The dataset contains **200 observations and 4 variables**.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## Machine Learning Model

The primary model used is **Multiple Linear Regression**.

The model predicts:

**Sales**

using:

- TV advertising
- Radio advertising
- Newspaper advertising

The regression model can be represented as:

`Sales = β₀ + β₁(TV) + β₂(Radio) + β₃(Newspaper) + ε`

## Key Findings

The analysis shows that:

- TV has a strong positive relationship with Sales.
- Radio also has a positive relationship with Sales.
- Newspaper has a comparatively weaker relationship with Sales.
- In the multiple regression model, TV and Radio are statistically significant predictors.
- Newspaper is not statistically significant after accounting for TV and Radio.
- The full-data OLS model achieves an R² of approximately **0.897**.

## Final Dashboard

The project concludes with a visualization dashboard summarizing:

- Dataset overview
- Relationship between advertising channels and Sales
- Actual vs Predicted Sales
- Model performance
- Regression coefficients
- Key business insights

## Business Objective

The model can help businesses understand how advertising budgets are associated with Sales and support more informed advertising-budget decisions.

## Project Structure

```text
Advertisement-Sales-Prediction/
│
├── Advertising.csv
├── Advertisement_Budget_ML.ipynb
└── README.md
