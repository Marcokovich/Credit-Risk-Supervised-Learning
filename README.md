# Credit-Risk-Supervised-Learning
## Overview:
### Background:
We were given a data set from LendingClub. The data contains multiple variables of continuous and categorical datatypes. . The goal is to prepare the data to be used in predictive models to determine whether or not a client is high risk or low risk. Since Credit Risk is inherently unbalanced, the use of oversampling and undersampling is authorized.
### Purpose:
To prepare the data the first portion of each coding portion will encode the categorical data for each of the models. The next step is to split the data into X and Y sets, then split the X and Y sets into testing and training sets. Finally we can feed the training sets to create the models and review them with the testing sets. Reviewing being the breakdown of the different metrics of how to models predict.
## Results:
### Logistic Regression Naive Random Oversampling:
Balanced Accuracy Score:
![image](https://user-images.githubusercontent.com/71575748/164955800-3cb3790f-6d0a-4b15-bb72-e171b6fde8b7.png)

![image](https://user-images.githubusercontent.com/71575748/164955827-e7d061d3-99a1-4a5c-a043-a62f852fc8ab.png)


### Logistic Regression with SMOTE Oversampling:
Balanced Accuracy Score:
![image](https://user-images.githubusercontent.com/71575748/164955953-5d256b54-aace-480e-8e8c-85be237199f2.png)

![image](https://user-images.githubusercontent.com/71575748/164955997-6504169a-f05d-466c-b154-b4764a8c5542.png)


### Logistic Regression with Cluster Centroids Undersampling:
Balanced Accuracy Score:
![image](https://user-images.githubusercontent.com/71575748/164956054-9abf8b93-12a5-4f71-92fe-c03b4efab5fb.png)

![image](https://user-images.githubusercontent.com/71575748/164956061-bf11f904-9633-472b-8f7c-410a589419e6.png)


### Logistic Regression with Combination Sampling:
Balanced Accuracy Score:
![image](https://user-images.githubusercontent.com/71575748/164956087-9a7d52f5-098f-496e-a3f7-eb14ce543986.png)

![image](https://user-images.githubusercontent.com/71575748/164956095-eb7839e5-1906-439d-a2ff-73db4c6cbdb0.png)


### Balanced Random Forest Classifier:
Balanced Accuracy Score:
![image](https://user-images.githubusercontent.com/71575748/164956651-4645d864-0bb4-4596-b554-190f377e39c5.png)

![image](https://user-images.githubusercontent.com/71575748/164956657-4234e01d-956b-47dd-acf7-bfc5d52fd685.png)

### Easy Ensemble AdaBoost Classifier:
Balanced Accuracy Score:
![image](https://user-images.githubusercontent.com/71575748/164956662-9cf71cac-36b1-4cbb-823a-eade89a8faf0.png)

![image](https://user-images.githubusercontent.com/71575748/164956671-d48d06b9-6751-44a9-812e-d5d4f726241f.png)

## Summary:
It would appear that the best model based on the scores is the Easy Ensemble Adaboost Classifier since it has the highest score for balanced accuracy .93 while maintaining a high f1 score of .96. The model has shown itself to be most effective with the testing set. Further research could be done such as using the XGBoost with over/undersampled data.
