# Machine Learning UTEC - Customer Churn Prediction in Telecommunications

## Instructions

Create a virtual environment in Python 3.11

```python
python3 -m venv .venv
```

Install dependencies from requirements.txt

```python
pip install -r requirements.txt
```

## Introduction

In the telecommunications industry, customer retention is a critical factor for sustainable business growth. This project focuses on predicting customer churn using machine learning models. The goal is to develop models that can analyze provided data and anticipate potential customer churn, contributing to effective retention strategies.

## Project Overview

- *Objective:* Maximize "recall" metric for effective customer churn prediction.
- *Data Preprocessing:* Comprehensive cleaning, encoding, and scaling of relevant variables.
- *Outlier Handling:* Utilized a custom class to clean outlier values.
- *Modeling:* Employed various machine learning models for prediction.

## Code Snippet

```python
# Importing necessary libraries

# ...

# Reading the data

# ...

# Data preprocessing steps

# ...

# Feature engineering

# ...

# Model training and evaluation

# ...

```

## Results for Logistic Regression

| Metric           | Training Set | Test Set |
|-------------------|--------------|----------|
| Recall Score      | 0.789        | 0.763    |
| Precision Score   | 0.626        | 0.621    |
| F1 Score          | 0.698        | 0.685    |
| Accuracy Score    | 0.784        | 0.758    |

## Results for XGBoost

| Metric           | Training Set | Test Set |
|-------------------|--------------|----------|
| Recall Score      | 0.991        | 0.826    |
| Precision Score   | 0.985        | 0.685    |
| F1 Score          | 0.988        | 0.748    |
| Accuracy Score    | 0.989        | 0.825    |

## Conclusion
XGBoost and LightGBM demonstrated the best performance. The results provide valuable insights for telecommunications companies to develop effective customer retention strategies.

Feel free to explore the detailed code and results in the Jupyter Notebook provided.