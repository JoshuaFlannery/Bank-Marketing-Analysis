# Bank Marketing Analysis

## Overview

This project analyzes a banking dataset to identify factors that influence whether a customer subscribes to a term deposit. The analysis focuses on customer characteristics, campaign timing, and data quality to uncover patterns in subscription behavior.

The project includes exploratory data analysis (EDA) and a simple predictive model to validate key findings.

## Overview

This project analyzes a banking dataset to identify factors that influence whether a customer subscribes to a term deposit. The analysis focuses on customer characteristics, campaign timing, and data quality to uncover patterns in subscription behavior.

The project includes exploratory data analysis (EDA) and a simple predictive model to validate key findings.

## Dataset

- Source: UCI Machine Learning Repository – Bank Marketing Dataset  
- Each observation represents a customer contacted during a marketing campaign  
- Target variable: `deposit` (yes/no)

The dataset includes demographic, financial, and campaign-related features such as age, job, balance, contact method, and previous campaign outcomes.

## Key Questions

- What factors most influence term deposit subscriptions?
- Which variables are associated with higher subscription rates?
- How can marketing efforts be optimized?

## Approach

- Cleaned and prepared data, including handling "unknown" values
- Conducted exploratory data analysis on key variables (contact method, campaign timing, previous outcomes)
- Built logistic regression models to evaluate predictive factors
- Addressed data leakage by removing call duration from the final model

## Modeling Results

- Model with call duration achieved higher accuracy (~81%)
- Removing duration reduced accuracy (~71%) but produced more realistic, actionable insights
- Final model highlights prior engagement and campaign timing as key predictors

## Tools Used

- Python
- pandas
- matplotlib
- scikit-learn

## How to Run

1. Clone the repository
2. Open the Jupyter Notebook
3. Run all cells to reproduce the analysis
