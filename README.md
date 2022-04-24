# Credit-Risk-Supervised-Learning
## Overview:
### Background:
We were given a data set from LendingClub. The data contains multiple variables of continuous and categorical datatypes. . The goal is to prepare the data to be used in predictive models to determine whether or not a client is high risk or low risk. Since Credit Risk is inherently unbalanced, the use of oversampling and undersampling is authorized.
### Purpose:
To prepare the data the first portion of each coding portion will encode the categorical data for each of the models. The next step is to split the data into X and Y sets, then split the X and Y sets into testing and training sets. Finally we can feed the training sets to create the models and review them with the testing sets. Reviewing being the breakdown of the different metrics of how to models predict.
## Results:
- Logistic Regression Naive Random Oversampling
- Logistic Regression with SMOTE Oversampling
- Logistic Regression with Cluster Centroids Undersampling
- Logistic Regression with Combination Sampling
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier
## Summary:
It would appear that the best model based on the scores is the Easy Ensemble Adaboost Classifier since it has the highest score for balanced accuracy .93 while maintaining a high f1 score of .96. The model has shown itself to be most effective with the testing set. Further research could be done such as using the XGBoost with over/undersampled data.
