# Required Assignment 17.1 — Comparing Classifiers (Bank Marketing)

## Summary of Findings
This project compares **KNN**, **Logistic Regression**, **Decision Trees**, and **SVM (RBF)** on the UCI Bank Marketing dataset to predict whether a client subscribes to a **term deposit** (`y`).

Key takeaways:
- The target is **imbalanced**, so **F1 / recall** are more meaningful than accuracy.
- `duration` is highly predictive but may not be usable **before** calling a customer. The notebook evaluates models **with** and **without** `duration`.
- For **pre-call targeting**, select the best-performing **no-duration** model to rank who to call, and keep an **interpretable** model (Logistic Regression or a shallow Decision Tree) for stakeholder explanations.

## Notebook
- [`required_assignment_17_1.ipynb`](required_assignment_17_1.ipynb)

## Data
- `data/bank-additional-full.csv`
