## JOB-A-THON
Analytics Vidhya presents JOB-A-THON: 12th Edition, where 75,000+ candidates have participated in job roles in over 100+ companies

### Problem Statement - 
Build a regression model to predict energy for given test data and perform RMSE evaluation metric

### Document Structure -
```
/
|__assets/
|     |__sample_submission.csv
|     |__test.csv
|     |__train.csv
|
|__main.ipynb
|__readme.md
|__submission.csv
```
### Solution -
To solve above problem statement. I used XGBoostRegressor, XGB stands for Extreme Gradient Boosting 
XGBoost is an effective method for developing supervised regression models. The objective function includes a loss function as well as a regularisation term. It describes the difference between actual and predicted values, i.e. how far the model results differ from the actual values. Reg:linear is the most commonly used loss function in XGBoost for regression problems. Ensemble learning entails training and combining individual models (referred to as base learners) to produce a single prediction, and XGBoost is one of the ensemble learning methods. XGBoost anticipates having base learners that are uniformly bad at the remainder, so that when all predictions are combined, bad predictions cancel out and better predictions add up to form final good predictions.

