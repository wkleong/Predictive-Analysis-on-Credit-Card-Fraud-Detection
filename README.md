# Predictive-Analysis-on-Credit-Card-Fraud-Detection

# Introduction
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
It is also extremely important for credit card companies to detect and predict future fraud transactions that are genuine before being reported by unhappy customers.

# Data
Weblink is https://www.kaggle.com/mlg-ulb/creditcardfraud/home
About 143MB with 284,555 rows and 32 columns.
Data is clean as it has being processed by PCA where 28 of the features have been numerically transformed. Time contains the seconds elapsed between transactions, and Amount is the amount per transaction.

# Objectives
The project objective is to evaluate the performance of NaÃ¯ve Bayes, Decision Tree and Random Forests models on predicting credit card fraud, in terms of Accuracy, CPU time and Negative Predict Value.


# Steps taken.
Initially, Random Forest(RF) was used to train on 75% of the data and after running it on single CPU at peak swapping memory of about 8G and had run more than 12 hours, it was infeasible to train the RF in a reasonable and allowable timeframe.

Multiple CPUs were used to parallelized the models training processes for speedup so that we can observe the overfit and underfit ph if exist.

The training of the Naive Bayes and Decision Tree models were done on 80% of the data.
However, the training for Random Forest models were seperated into 10% of the data on runs with 4 cores and then 80% on 1 core.

# Final Model Selection.
Lastly, performance parameter like Accuracy and Negative Predicted Value were used to select the appropriate model for Predictive Analysis.

Please kindly comment if any.
Thank you very much.
