**Project Goal:**

Credit card companies shall be able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

** Intro **

- Fraud poseses a serious threat to all most all companies.
- Examples of fraud: insurance fraud, credit card fraud, identify theft, money laundering, tax evasion, product warranty, healthcare fraud
- Detecting fraud is typically challenging because fraud cases are:
    - uncommon (minority, sometime .5% are fraudulent)
    - concealed (blendin with normal transactions)
    - changing over time (fraudsters will change activity over time to make it look like normal)
    - organized (fraudeters often work together in a network to make their activity harder to detect

**Data Set Description:**

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,315 transactions. It has 30 input features and 1 target variable. The dataset is highly unbalanced, the positive class (frauds) account for 0.173% of all transactions.

**Content:**

1. Imports [We will import required libraries where ever it is required in the code flow]
2. Load data
3. Check numerical statistics
4. Scale data
5. Prepare feature and target variable
6. Split data to training and test set
7. Import model
8. Train and Predict with model
9 .Evaluate the model


# Further Model improvement [Balancing the data using SMOTE, Hyperparameter tuning using GridSearchCV etc]
