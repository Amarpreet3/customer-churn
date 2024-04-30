# Churn Prediction Project

## Overview

This repository contains the churn prediction analysis for a telecom company. The goal is to predict which customers will churn in the near future using Decision Tree and Naïve Bayes predictive models.

## Data

The dataset includes various customer attributes such as daily usage, service calls, and plan subscriptions, which are used to predict churn likelihood.

## Files Description

- `data_preparation.ipynb` - Jupyter notebook for data cleaning and preparation.
- `decision_tree_model.ipynb` - Implementation of the Decision Tree model in Python.
- `naive_bayes_model.ipynb` - Implementation of the Naïve Bayes model in SAS.
- `model_comparison.ipynb` - Comparison of models to evaluate performance.

## Models

Two types of predictive models were used:

1. Decision Tree
   - Best accuracy: 92.32%
   - Implemented in Python
2. Naïve Bayes
   - Best accuracy: 84.79%
   - Implemented in SAS
![image](https://github.com/Amarpreet3/customer-churn/assets/96805692/ab97085f-4a1d-4a4a-a152-be4645ed3afb)

## Key Findings

- The most important predictors of customer churn are:
  - Day Mins: The number of minutes the customer used the service during daytime.
  - CustServ Calls: The number of calls to customer support.
  - Int'l Plan: Whether the customer has an international calling plan.

## Recommendations

- Focus on improving customer experience for heavy users with high day minutes and those with international plans.
- Implement a flag system in the CRM to monitor customers with increased churn risk.

## How to Run

Ensure you have Python and SAS installed on your machine. Each notebook contains detailed steps to run the models and visualize the results.

