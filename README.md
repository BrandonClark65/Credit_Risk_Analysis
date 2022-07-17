# Credit Risk Analysis

## Overview

### Background
Credit risk is a largely unbalanced classification problem. Far more good loans exist than risky loans, so it is important to have the proper model when determining good vs bad credit risk.
### Purpose
The purpose of this analysis is to use a credit card credit dataset from LendingClub to compare models:
- RandomOverSampler
- SMOTE
- ClusterCentroids
- SMOTEENN
- BalancedRandomForestClassifier
- EasyEnsembleClassifier
  
## Results
- Random Oversampler
  - Balanced Accuracy Score: 0.657
  - Precision: 0.01
  - Recall: 0.71
- SMOTE
  - Balanced Accuracy Score: 0.662
  - Precision: 0.01
  - Recall: 0.63
- ClusterCentroids
  - Balanced Accuracy Score: 0.544
  - Precision: 0.01
  - Recall: 0.69
- SMOTEEENN
  - Balanced Accuracy Score: 0.545
  - Precision: 0.01
  - Recall: 0.69
- BalancedRandomForestClassifier
  - Balanced Accuracy Score: 0.789
  - Precision: 0.03
  - Recall: 0.70
- EasyEnsembleClassifier
  - Balanced Accuracy Score: 0.932
  - Precision: 0.09
  - Recall: 0.92

## Summary
