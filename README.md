# Python-MBD
A IE HST course on Python

# Predicting number of bike users in Washington DC 
A regression machine learning model predicting the amount of bike sharing users in an hourly-basis.

# Methodologies:
- Imputation: A simple forward fill given the time series nature of the data and the fact that all missing values were spread out and not together in the time series.
- Dealing with Date Features: Encoded into year, month, day, hour
- Dealing with Categorical: Ordinal encoding for the weather situation feature
- Features Engineering: Created date time features such as Weekend, Workingday, peak_weekend, and peak_workingday, daylight hours, 
- Machine Learning: Train-validation split, randomized search with 5 fold cross validation, xgboost regression for an r2=.9577, mae=21.37, mse 1223.83
