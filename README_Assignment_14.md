# Assignment 14: Ethical AI, Fairness, and Explainability

## Project Overview

This project builds a logistic regression model and evaluates it using performance metrics, fairness metrics, and explainability tools. The goal is to show how machine learning models can be assessed for accuracy, fairness, bias, and transparency.

## Dataset

The project uses the public Titanic dataset from the seaborn library. The target variable is `survived`, and the sensitive attribute used for fairness analysis is `sex`.

## Methods Used

- Data preprocessing
- Train-test split
- Logistic regression with scikit-learn
- Accuracy, confusion matrix, and classification report
- Fairness analysis with Fairlearn
- MetricFrame by sensitive group
- SHAP summary and waterfall plots
- LIME local explanation

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells from top to bottom.
3. Save or print the notebook as a PDF with outputs included.
4. Upload the notebook and README.md to GitHub.

## Files

- `Assignment_14_Ethical_AI_Fairness_Explainability.ipynb`: Main Google Colab notebook.
- `README.md`: Project overview and setup instructions.
