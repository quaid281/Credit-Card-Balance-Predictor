# Credit-Card-Balance-Predictor

In this project I will be analyzing credit card data from ..=400 training observations. 
The goal is to fit a model that can predict credit balance based on ..=9 features describing an individual, 
which include an individual’s income, credit limit, credit rating, number of credit cards, age, education level, gender, student status, and marriage status.
Specifically, I will perform a penalized (regularized) least squares fit of a linear model using ridge regression, with the model parameters obtained by batch gradient descent. 
The tuning parameter will be chosen using five-fold cross validation, and the best-fit model parameters will be inferred on the training dataset conditional on an optimal tuning 
parameter.
