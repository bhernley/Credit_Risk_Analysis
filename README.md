# Credit_Risk_Analysis

# Overview

The purpose of this analysis is to  utilize Machine Learning statistical algorithms to make predictions of credit risk based on data provided. In this challenge, we focused on Supervised Learning models due to the data being labled. The models used and compared were the following:

- Naive Random Oversampling
- SMOTE Oversampling
- Undersampling
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier
- EasyEnsembleClassifier

# Results

### Naive Random Oversampling

 * Accuracy Score of 64.4%
 * "High Risk" precision rate was only 1% with the recall at 70% giving this model an F1 score of 2%.
 * "Low Risk" had a precision rate of 100% and recall at 59%.

### SMOTE Oversampling

 * Accuracy Score of 64.9%
 * "High Risk" precision rate was only 1% with the recall at 70% giving this model an F1 score of 2%.
 * "Low Risk" had a precision rate of 100% and recall at 59%.

### Undersampling

 * Accuracy Score of 64.9%
 * "High Risk" precision rate was only 1% with the recall at 72% giving this model an F1 score of 2%.
 * "Low Risk" had a precision rate of 100% and recall at 57%.

### Balanced Random Forest Classifier

 * Accuracy Score of 93.2%
 * "High Risk" precision rate was only 9% with the recall at 92% giving this model an F1 score of 16%.
 * "Low Risk" had a precision rate of 100% and recall at 94%.

### Easy Ensemble AdaBoost Classifier

 * Accuracy Score of 93.2%
 * "High Risk" precision rate was only 9% with the recall at 92% giving this model an F1 score of 16%.
 * "Low Risk" had a precision rate of 100% and recall at 94%.

# Summary

After comparing the models, it would appear that either of the 2 classifier models would work best.  This is consistant with the general acceptance that classifier models are more appropriate with predicting a two outcome scenario, such as high risk/low risk.
