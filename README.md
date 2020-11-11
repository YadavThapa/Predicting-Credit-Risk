## Predicting-Credit-Risk

# Project Overview

The Chief Data Scientist Jill wants to develope the supervised machine learning using classification model to analyse and predict the Credit analysis for the unbalanced data. 

# Business Objective
The main objective of this project is to help Jill by collecting, preparing , cleaning  and proecssing the unbalanced data, training and testing the data with model validation. And final objective is deploy the supervised machine learning for classification model in to the project. 

To support the Jill, we are going to develope different machine learning algorith with oversampling, undersampling and mixed model techniques.


## Results with logistic classifier
1. The Naive Random Oversampling techinques with implementation of logistic regression classifier gives us 66 % of prediction accuracy with recall value for high risk, low risk as 74 %, 58 % and precision value with 1% and 100% and overall 99% for loan_status.

2. Similarly, the SMOTE oversampling technique with logistic classifier provides us 65.37 % of over prediction model accuracy with recall value for 62% and 68 % for high risk and low risk  and precision value with 1% and 100 % for high risk and low risk loan_status.

3. The ClusterCentroids Sampling techniques with implemention of logistic regression classifer gives us 54.4 % of prediction accuracty with recall value 67.41% and 41% and overall 42%. Similarly this model gives us 1% and 100% for precession value and overall values 99% for loan_status.

4. The combined Random Over Sampling+ Random Under Sampling(mixed model- SMOTTEN techniques) with logistic classifier provides us 64.47 % accuracy model with precession values 72% and 57% for high risk and low risk loan status and precision value with 1% and 100% for the high risk and low risk loan status.


## Summary(a)
 From the above analysis, we came to conclussion the random oversampling techinques( Naive Random Oversamplings with 66% and SMOTE with 65.37 %) are better than ClusterCentroid undersampling with 54.4% prediction accuraccy.
 
The combined effect of undersample and oversample techniques also gives us better prediction model.( SMOTTEN with 64.47 % of accuracy).


## Results with Ensemble classifier

1. The Balanced Random Forest Classifier algorithm provides us 88.25 % of prediction accuracy with 67% and 88 % with the recall values and 3% and 100% with the precision values for the high_risk and low_risk.

2. Similarly, Easy Ensemble AdaBoost Classifier algorithm provides us 94.76% of prediction accuracy with 90% and 95% recall value and 8% and 100% for the precision values for the loan_status.

## Summary(b)
From the above comparative analysis, we came to conclusion that Easy Ensemble AdaBooast Classifier algorithm are far better than Balanced Random Classifier algorith interms of prediction accuracy with recall values.


# Conclussion

From the above comparative analysis of six supervised machine learning algorithms ( from Oversampling, Undersampling, Mixed- Model) against Ensembles techniques(Balanced Random Forest Classifier andEasy Ensemble AdaBoost Classifier), the ensemble clasifier are seem to be more accurate with high recall values.

Hence we should give first priory to Ensemble techniques over others classifier.
