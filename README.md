# Credit_Risk_Analysis
## Overview 
This project analyzed which supervised machine learning model could accurately predict credit risk. In order to complete this taskthe following methods were used: Naive Random Oversampling, SMOTE Oversampling, Cluster Centroid Undersampling, SMOTEENN Sampling, Balanced Random Forest Classifying, and Easy Ensemble Classifying.

## Results 
###Naive Rancom Oversampling
- Accuracy Score: 67.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 66% 
- Recall Low Risk: 69% \
![naiverandomoversampling](https://github.com/juliacho22/Credit_Risk_Analysis/blob/main/resources/naiverandomoversampling.PNG) 

###SMOTE Oversampling
- Accuracy Score: 68.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 70% 
- Recall Low Risk: 66%\
![smoteoversampling](https://github.com/juliacho22/Credit_Risk_Analysis/blob/main/resources/smoteoversampling.PNG) 

###Cluster Centroid Undersampling
- Accuracy Score: 52.2%
- Precision High Risk: 0%
- Precision Low Risk: 100%
- Recall High Risk: 61% 
- Recall Low Risk: 44%\
![clustercentroidundersampling](https://github.com/juliacho22/Credit_Risk_Analysis/blob/main/resources/clustercentroidundersampling.PNG) 

###SMOTEENN Sampling
- Accuracy Score: 68.1%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 76% 
- Recall Low Risk: 60%\
![smoteennsampling](https://github.com/juliacho22/Credit_Risk_Analysis/blob/main/resources/smoteennsampling.PNG) 

###Balanced Random Forest Classifying
- Accuracy Score: 64.8%
- Precision High Risk: 56%
- Precision Low Risk: 100%
- Recall High Risk: 30% 
- Recall Low Risk: 100%\
![balancedrandomforestclassifying](https://github.com/juliacho22/Credit_Risk_Analysis/blob/main/resources/balancedrandomforestclassifying.PNG) 

###Easy Ensemble Classifying
- Accuracy Score: 92.3%
- Precision High Risk: 6%
- Precision Low Risk: 100%
- Recall High Risk: 91% 
- Recall Low Risk: 94%\
![easyensembleclassifying](https://github.com/juliacho22/Credit_Risk_Analysis/blob/main/resources/easyensembleclassifying.PNG) 

## Summary
Since the goal of the analysis is to find the best model that can detect whether a loan is at high risk, the model with least amount of high risk loans is the best fit. The models that scored the highist risks were: 
* Easy Ensemble Classifying (91%)
* SMOTEEN Sampling (76%) 
* SMOTE Oversampling (70%)

It is also important to take into consideration the recall rate for low risk because it whos how many low risk loans are flagged as high risk. The models that scored the highest were: 
* Balanced Random Forest Classifying (100%) 
* Easy Ensemble Classifying (94%)

Additionally, the highest accuracy scores were shown by the following models: 
* Easy Ensemble Classiyfing (92.3%)
* SMOTE Oversample (68.2%)
* SMOTEEN Sampling (68.1%)

Based on these results, the most recommended model to use for predicting high risk loans is the Easy Ensemble Classifying model.

