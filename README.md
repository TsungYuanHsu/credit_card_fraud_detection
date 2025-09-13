"# credit_card_fraud_detection" 

- Introduction
Imagine that you work for a financial institution and part of your job is to build a model that predicts if a credit card transaction is fraudulent or not. You can model the problem as a binary classification problem. A transaction belongs to the positive class (1) if it is a fraud, otherwise it belongs to the negative class (0).

You have access to transactions that occured over a certain period of time. The majority of the transactions are normally legitimate and only a small fraction are non-legitimate. Thus, typically you have access to a dataset that is highly unbalanced. This is also the case of the current dataset: only 492 transactions out of 284,807 are fraudulent (the positive class - the frauds - accounts for 0.172% of all transactions).

This is a Kaggle dataset. You can find this "Credit Card Fraud Detection" dataset from the following link: Credit Card Fraud Detection.

To train the model, you can use part of the input dataset, while the remaining data can be utilized to assess the quality of the trained model. First, let's import the necessary libraries and download the dataset.

- Objectives
Perform basic data preprocessing in Python
Model a classification task using the Scikit-Learn Python APIs
Train Suppport Vector Machine and Decision Tree models using Scikit-Learn
Run inference and assess the quality of the trained models

- Flow
Import libraries
Import data
Understand the data
Preprocess the data
Split data into training set and test set
Model development for decision tree and SVM
Evaluate the models