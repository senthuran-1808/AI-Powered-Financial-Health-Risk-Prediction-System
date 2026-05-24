# AI-Powered Financial Health & Risk Prediction System

## Project Overview

The AI-Powered Financial Health & Risk Prediction System is an end-to-end financial analytics and machine learning project developed using real-world Indian stock market financial data. The project analyzes company financial performance, predicts financial risk levels, calculates financial health scores, and generates AI-based business recommendations automatically.

The system uses multiple financial datasets from the Bombay Stock Exchange (BSE) and applies data engineering, feature engineering, machine learning, and explainable analytics techniques to build an intelligent financial risk analysis platform.

---

# Problem Statement

Analyzing company financial risk manually is difficult because companies generate huge amounts of financial data such as balance sheets, liabilities, profits, cash flow statements, and quarterly financial reports.

Traditional financial analysis methods are time-consuming and may fail to identify hidden financial risk patterns, debt dependency issues, or weak profitability conditions.

There is a need for an intelligent system that can automatically:
- Analyze financial data
- Predict company risk levels
- Measure financial health
- Generate business recommendations

---

# Solution

To solve this problem, an AI-driven financial analytics system was developed using Python and Machine Learning.

The system performs:
- Financial data preprocessing
- Multi-dataset merging
- Financial feature engineering
- Financial health scoring
- Risk classification
- AI-based recommendation generation
- Machine learning-based prediction

The final system automatically identifies:
- Financially healthy companies
- Moderate-risk companies
- High-risk companies

---

# Dataset Information

## Dataset Source
Indian Stock Market Dataset — Kaggle

## Dataset Type
Bombay Stock Exchange (BSE) Financial Dataset

## Major Dataset Files Used
- Balance Sheet Data
- Quarterly Results Data
- Cash Flow Statements
- Company Information
- Peer Comparison Data

---

# Technologies Used

## Programming Language
- Python

## Libraries Used
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

# Data Engineering Process

The raw datasets contained:
- Missing values
- Unnecessary columns
- Multiple CSV files
- Inconsistent column names

Data preprocessing steps performed:
- Removed unwanted columns
- Handled missing values
- Renamed columns professionally
- Merged datasets using `ScripCode`
- Selected important financial features

---

# Important Financial Columns Used

- Sales
- Net Profit
- Borrowings
- Total Assets
- PE Ratio
- PB Ratio
- RONW
- Liabilities
- Operating Profit
- Cash Flow Metrics

---

# Feature Engineering

Additional business intelligence features were created from raw financial data.

## Extra Features Added

| Feature | Purpose |
|---|---|
| Debt_Ratio | Measures debt dependency |
| Profit_Margin | Measures profitability |
| Financial_Health_Score | Measures overall financial condition |
| Health_Category | Healthy / Moderate / Weak |
| Risk_Level | High / Medium / Low Risk |
| AI_Recommendation | Business improvement suggestions |

---

# Financial Logic Used

## Debt Ratio Formula

```python
Debt_Ratio = Borrowings / Total_Assets
```

## Profit Margin Formula

```python
Profit_Margin = Net_Profit / Sales
```

## Financial Health Score Formula

```python
Financial_Health_Score =
(Profit_Margin * 0.5) +
((1 - Debt_Ratio) * 0.3) +
((Net_Profit / Total_Assets) * 0.2)
```

The formula combines:
- Profitability
- Debt risk
- Asset efficiency

to measure overall company financial strength.

---

# AI Recommendation Engine

An AI-based recommendation system was created using business logic rules.

The recommendation engine analyzes:
- Debt conditions
- Profitability
- Financial health
- Company performance

and generates automated business recommendations.

## Example Recommendations

### High Risk Company
```python
"High debt dependency detected. Improve liquidity and reduce borrowings."
```

### Moderate Company
```python
"Financial condition is moderate. Improve operational profitability."
```

### Healthy Company
```python
"Strong financial condition with stable profitability and controlled liabilities."
```

---

# Machine Learning Implementation

## Machine Learning Objective

The objective of the ML model is to predict company financial risk levels automatically.

## ML Problem Type
Classification Problem

## Target Column

```python
Risk_Level
```

## Features Used for ML

- Sales
- Net Profit
- Borrowings
- Total Assets
- Debt Ratio
- Profit Margin
- Financial Health Score
- PE Ratio
- PB Ratio
- RONW

---

# Machine Learning Algorithms Used

## 1. Logistic Regression

Used as a baseline classification algorithm for structured financial data.

### Advantages
- Fast training
- Simple and interpretable
- Good baseline performance

---

## 2. Random Forest

Used multiple decision trees to improve prediction stability and handle nonlinear financial relationships.

### Advantages
- High accuracy
- Handles complex patterns
- Reduces overfitting

---

## 3. Gradient Boosting

Used sequential learning to improve predictions by correcting previous prediction errors.

### Advantages
- Very high prediction accuracy
- Learns complex financial relationships
- Strong classification performance

---

# Model Accuracy

| Model | Accuracy |
|---|---|
| Logistic Regression | 100% |
| Random Forest | 98.7% |
| Gradient Boosting | 100% |

---

# Best Model Selected

## Gradient Boosting Classifier

Gradient Boosting was selected because:
- Achieved highest accuracy
- Improved predictions sequentially
- Learned complex financial patterns effectively

---

# Model Evaluation Techniques

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Actual vs Predicted Analysis
- Feature Importance Analysis

---

# Final Output

The final system successfully provides:
- Financial risk prediction
- Financial health analysis
- AI-based recommendations
- Explainable financial intelligence
- Company risk categorization

---

# Business Impact

This project helps:
- Investors analyze company risk
- Financial analysts automate evaluations
- Businesses identify financial weaknesses
- Improve financial decision-making

---

# Key Highlights

- End-to-end finance AI project
- Real-world BSE stock market dataset
- Financial feature engineering
- Explainable AI implementation
- Multiple ML model comparison
- AI-based recommendation generation
- Industry-level financial analytics pipeline

---

# Conclusion

The AI-Powered Financial Health & Risk Prediction System successfully demonstrates how Artificial Intelligence and Machine Learning can be applied in the finance domain to automate financial analysis and improve risk prediction.

Using real-world Indian stock market financial data, the project performs intelligent financial analytics, predicts company risk levels, calculates financial health scores, and generates business recommendations automatically.

The project combines:
- Financial analytics
- Data engineering
- Feature engineering
- Machine learning
- Explainable AI

to build a complete industry-level finance intelligence solution.

---