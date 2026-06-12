# Walmart Black Friday — Customer Purchase Behavior Analysis
### Business Case: Central Limit Theorem & Confidence Intervals | Score: 100/100 ⭐

## Problem Statement
The Management team at Walmart Inc. wants to analyze customer purchase behavior 
against customer demographics to make better business decisions.

**Central Question:** Do women spend more on Black Friday than men?  
*(Assuming a population of 50 million male and 50 million female customers)*

## Key Findings
| Analysis | Result |
|---|---|
| Gender (Male vs Female) | **NON-OVERLAPPING** at 99% CI — Men spend 8% more |
| Marital Status | **OVERLAPPING** — No statistically significant difference |
| Age Groups | **NON-OVERLAPPING** — 51-55 highest spenders, 0-17 lowest |

## Tech Stack
- Python 3.13 | Pandas | NumPy | Matplotlib | Seaborn | SciPy

## Dataset
[Walmart Black Friday Dataset](https://www.kaggle.com/datasets/mehdidag/black-friday)

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```

## Results Summary
- **550,068 transactions** analyzed across 10 features
- Applied **CLT** to project sample findings to 50 million customers
- Gender CIs are **non-overlapping at 90%, 95%, and 99%** confidence levels
- Marital status shows **no statistical significance** — overlapping CIs
- **6 actionable business recommendations** delivered to Walmart leadership
