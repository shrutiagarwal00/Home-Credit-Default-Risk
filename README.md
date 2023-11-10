# Applied Machine Learning Capstone: Home-Credit-Default-Risk

Problem Statement:
Taking loans has been a crucial part of many of our lives. Whether it's for education, or buying a new house or supporting a business, people prefer taking a loan over spending liquid cash. However, sometimes people have a disadvantage in obtaining loans due to nonexistent or low credit history. Home Credit is a financial provider that is trying to make borrowing a positive experience and ensure that clients capable of repayment are not rejected. In this study, we try to utilize alternative data such as transactional history in order to predict the client’s repaying ability and thus allow people with repayment ability to obtain the loan they need.

Dataset:
We found the Home Credit Default Risk dataset on kaggle. It includes seven additional sources of data pertaining to the task, which we may use to improve our model.
application (test/train): static data for all applications where the training data contains TARGET while test doesn’t.
bureau: client’s previous credits from other financial institutions.
bureau_balance: monthly balance of previous credits in Credit Bureau.
POS_CASH_balance: Monthly balance snapshots of previous POS and cash loans that the applicant had with Home Credit.
credit_card_balance: Monthly balance snapshots of applicant’s previous credit cards.
previous_application: client’s previous applications for Home Credit loans.
installments_payments: Repayment history for the previously disbursed credits in Home Credit related to loans

Project Plan:
We intend to perform the following steps:

EDA:  Exploring the data to understand the variables, looking for missing values and visualizing the distribution of variables.
Feature Engineering: Working with missing values, encoding variables, and engineering features through different techniques (for example creating interaction terms, PCA)
Model Selection: We will explore ML techniques like XGBoost, LGBM, ANN. Using hyperparameter tuning, we’ll look for the best parameters to fit and train the models.
Feature Importance: By calculating a score for all the input features for a particular model, we will analyze which features have the highest impact on the model predictions.
Model Evaluation: Using confusion matrix and ROC curve, we’ll look for the best model to generate predictions for our problem.
