# Loan Default Prediction

## 0verview
Predicts loan default risk from borrower data using classification models, built for a fictional lending company (LoanAnalytics Inc.) evaluating loan applicants.

Overview

**Dataset** : 255K+ loan records (income, credit score, employment, DTI ratio, etc.), ~11.6% default rate

Models compared: Logistic Regression, SGD, Decision Tree, Random Forest — with class weighting to handle the imbalance

Evaluation: precision/recall/F1 per class (accuracy alone is misleading here)

Key Result

The most "accurate" model (Random Forest, 89%) barely caught any real defaulters (3% recall). Class-weighted Logistic Regression traded accuracy (82%) for far better recall (42%) on defaulters — the metric that actually matters for catching risk early.

Tools

Python · Pandas · Scikit-learn · Seaborn

![Loan default](./Loan predict pic.png "San Juan Mountains")
