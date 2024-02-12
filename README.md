# 2023 Travelers Analytics Case Competition
## Project Description:
In this competition, the primary goal is to utilize historical auto claim data to create an effective
rating plan for InsNova Auto Insurance Company. The objective is to develop a robust
predictive model for claim cost that optimizes the company's pricing strategy and enhances
competitiveness in the Australian auto insurance market. Leveraging machine learning
techniques, specifically XGBoost and Random Forest models, to accurately predict claim costs
based on relevant dataset features. 

## Research Question:
How accurately we can predict claim costs for auto insurance policies using XGBoost, Random
Forest, and Neural Network models?

## Datasets:
‒ Training dataset: 22,619 policies with 1,542 (6.8%) have at
least one claim (80% for model generation and 20% for test)
‒ Validation dataset (Company evaluation): 22,620 policies
## Variables:
‒ Response variables: claim (0 or 1), claim counts, claim cost
‒ Potential predictors:18 variables

## Preprocessing:

Feature Transformation: Used log, square root, square transformations for the continuous features.
MinMaxScaler: Transform the data to a specific range, [0, 1]
StandardScaler: Standardizes data by subtracting mean and dividing by standard deviation.

## Model Training:
Models: KNN, Xgboost, Random Forest, Decision Tree, Regression. 
Cross Validation: 5-fold and 10-fold CV.
Hyper-parameter Tuning: Used grid search for Hyperparameter tuning which systematically searches for the optimal parameters for machine leaning models.

## Evaluation Metrics: 
MSE, MAE, Gini Index.
