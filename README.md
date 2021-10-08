# Module-17-credit-risk-analysis
LendingClub, a peer-to-peer lending company plans to predict credit risk using machine learning to provide a quicker, more reliable loan experience. Predicting good loan candidates should lead to lower default rates.

Several machine learning models from the imbalanced-learn and scikit-learn libraries were used to predict credit risk. Each model is evaluated by calculating the balanced accuracy score, a confusion matrix, and printing a classification report.

## Conclusion

The data provided through LendingClub was imported and cleaned, and saved as a Pandas DataFrame. Null rows and columns were dropped and strings were converted to numerical data for evaluation. The data was separated into 90 features with the target variable “loan status” valued as low_risk (shown as 1) or high_risk (shown as 0). The function train_test_split was then used to split the data into training and testing sets. Several models were tested, and the results are as follows:
