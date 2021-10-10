# Credit-card-fraud-detection

**Dataset from Kaggle: https://www.kaggle.com/mlg-ulb/creditcardfraud**

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. It contains only numerical input variables which are the result of a PCA transformation. 

There are a total of 31 columns of features i.e. V1,V2.....V28 , time, class and amount. 

This code used Isolation forest algorithm as outlier detection method which gave us the accuracy over 99%.

To learn about Isolation forest and its commands to use on datasets, refer to http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html
