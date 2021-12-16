# credit_risk_analysis_UT_DATA

## Purpose Overview

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

- Deliverable 1: Use Resampling Models to Predict Credit Risk
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
- Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)

## Results

- **Naive Random Oversampling**
  - Balanced accuracy score: 0.64
  - Precision score: 0.99
  - Recall score: 0.64
- **SMOTE Oversampling**
  - Balanced accuracy score: 0.66
  - Precision score: 0.99
  - Recall score: 0.67
- **Undersampling**
  - Balanced accuracy score: 0.52
  - Precision score: 0.99
  - Recall score: 0.46
- **Combination (Over and Under) Sampling with SMOTEENN**
  - Balanced accuracy score: 0.65
  - Precision score: 0.99
  - Recall score: 0.59
- **Balanced Random Forest Classifier**
  - Balanced accuracy score: 0.81
  - Precision score: 0.99
  - Recall score: 0.89
- **Easy Ensemble Classifier**
  - Balanced accuracy score: 0.94
  - Precision score: 0.99
  - Recall score: 0.94

## Summary

- **Naive Random Oversampling**
  * Strong precision and weak recall, model is likely not returning all relevant data points
- **SMOTE Oversampling**
  * Strong precision and weak recall, model is likely not returning all relevant data points
- **Undersampling**
  * Strong precision and very weak recall, model is likely not returning all relevant data points
- **Combination (Over and Under) Sampling with SMOTEENN**
  * Strong precision and very weak recall, model is likely not returning all relevant data points
- **Balanced Random Forest Classifier**
  * Strong precision and strong recall, model is returning more relevant results as well as a higher portion of true relevant results
- **Easy Ensemble Classifier**
  * Strong precision and strong recall, model is returning more relevant results as well as a higher portion of true relevant results

### Recomendation

We recomend the use of the **Balanced Random Forest Classifier** model or the **EEC** model based on the signifcantly higher performance of these two models.