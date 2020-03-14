# Kaggle Titanic Competition
This notebook is about prediting the mortality ie survival of passengers of the Titanic for Kaggle. It contains a quick but still complete data science life cycle from data cleaning, feature engineering to model selection and prediction. It comprises a train-validation-test split set-up and is based on pipes to prevent data leakage. The score on validaton is 83 Percent so far, so that it would rank among top approaches in the competition.
## Data Cleaning 
Here, only three variables contain missings. Cleaning is based on standard median inputing (for continuous) and most frequent (categorical). However, a regression based approach to imputation for age is explored too.
## Feature engineering
Particularly, it tackles 
- the names and titles of passengers and 
- the number of relatives.
It starts the exploration of cabin and fare.
## Model Selection
First, logistic regression is explored and its hyperparameters are tweaked. Then, the same is done for Random Forest and finally XGboost. 
