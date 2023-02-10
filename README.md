# Credit_Risk_Analysis
# Overview
We are given credit card dataset from LendingClub.  The goal will be to evaluate credit risk by running over and undersampling data, and to use machine learning models to predict the credit risk.

## Results
Random Oversampling

![image](https://user-images.githubusercontent.com/111592990/218218087-e9d5b7d0-8dcb-444a-99d4-71b404be49eb.png)

•	Accuracy Score is 63%

•	Precision Score is 99%

•	Recall Score is 68%

# Smote Oversampling

![image](https://user-images.githubusercontent.com/111592990/218218272-a7c9b227-35b4-4eff-b401-7b72bff37ff2.png)

•	Accuracy Score is 63%

•	Precision Score is 99%

•	Recall Score is 63%

# Cluster Centroids

![image](https://user-images.githubusercontent.com/111592990/218218334-95173d8f-a98b-4115-aca5-934a52fe3f98.png)
 
•	Accuracy Score is 52%

•	Precision Score is 99%

•	Recall Score is 45%


# SMOTEENN

![image](https://user-images.githubusercontent.com/111592990/218218564-49fdf3be-2e72-42a0-9ae4-8f6d6f03e762.png)

•	Accuracy Score is 64%

•	Precision Score is 99%

•	Recall Score is 58%
# Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/111592990/218218653-6315a66c-3020-4b9f-8d56-b3a039697a56.png)


•	Accuracy Score is 78%

•	Precision Score is 99%

•	Recall Score is 91%

# Easy Ensemble Adaboost Classifier

![image](https://user-images.githubusercontent.com/111592990/218218742-02404005-db86-43a4-ac0c-89419c2f2f5d.png)

•	Accuracy Score is 93%

•	Precision Score is 99%

•	Recall Score is 94%

# Summary
All of the models had strong precision scores.  In terms of accuracy, the only model that had above 90% was Easy Emsemble AdaBoost Classifier.  For the recall scores, two models (Random Forest Classifier & Easy Ensemble) produced a recall score above 90%
I would recommend Easy Ensemble Adaboost Classifier as the best model to use.  It provided the highest overall accuracy, precision, and recall scores.




