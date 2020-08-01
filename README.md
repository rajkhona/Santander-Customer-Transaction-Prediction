# Santander Customer Transaction Prediction
Problem Statement

In this challenge, Santander invites Kagglers to help them identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted. The data provided for this competition has the same structure as the real data they have available to solve this problem.

The data is anonimyzed, each row containing 200 numerical values identified just with a number.

In the following we will explore the data, prepare it for a model, train a model and predict the target value for the test set, then prepare a submission.

*Note: I have attched link to the competition from where one can download the dataset Since, the size of the dataset is large.
(https://www.kaggle.com/c/santander-customer-transaction-prediction/data)

Folder Structure:

1. Dataset Information
   
   1.1 Train.csv: Training dataset. 
   
   1.2 Test.csv: validation dataset.

2. Notebook Information
   
   2.1 Santander_EDA_Transformation.ipynb: This notebook comprises of Exploratory Data Analysis, and Data transformation.
   
   2.2 Algorithm_Implementation.ipynb: This notebook comprises of algorithm implementation namely Logistic Regression, and focuses on improving model's performance by handling        imbalanced dataset using SMOTE technique. Notebook also includes algortihm evaluation metrics to check how they are performing.
   
3. Model Information:
   
   3.1 Logistic_model.sav: Logistic Regression model.
   
   3.2 SMOTE_Logistic_model.sav: Applying SMOTE technique to balance data and implementing Logistic Regression model on transformed dataset.
