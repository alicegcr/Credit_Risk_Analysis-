# Credit_Risk_Analysis
Using Machine Learning to analysis credit risk 
## Overview 

The main purpose of this project is to analyze credit risk, using the credit card credit dataset 
from LendingClub, to understand if there is any unbalanced classification problem as a good loan or 
a risk loan. To perform this analysis, six machine learning models will be used. 

## Resources 

- Data: LoanStats_2019Q1.csv
- Source: Jupyter Notebook, Machine Learning, Pandas 

## Results 

### Naive Random Oversampling

![naive_random_oversampling](png/naive_random_oversampling.png).

  * Balanced Accuracy Score: 65.3%
  * High Risk Precision: 1%
  * High Risk Recall: 63%
  * Low Risk Precision: 100%
  * Low Risk Recall: 67$


### SMOTE Oversampling

![SMOTE_oversampling](png/SMOTE_oversampling.png).

  * Balanced Accuracy Score: 65.1%
  * High Risk Precision: 1%
  * High Risk Recall: 64%
  * Low Risk Precision: 100%
  * Low Risk Recall: 66%

### Undersampling

![undersampling](png/undersampling.png).

  * Balanced Accuracy Score: 65.1%
  * High Risk Precision: 1%
  * High Risk Recall: 59%
  * Low Risk Precision: 100%
  * Low Risk Recall: 43%

### Combination (Over and Under) Sampling

![combination](png/combination.png).

  * Balanced Accuracy Score: 64.2%
  * High Risk Precision: 1%
  * High Risk Recall: 59%
  * Low Risk Precision: 100%
  * Low Risk Recall: 43%
  
### Balanced Random Forest Classifier

![balance_random_forest](png/balance_random_forest.png).

  * Balanced Accuracy Score: 78.7%
  * High Risk Precision: 4%
  * High Risk Recall: 67%
  * Low Risk Precision: 100%
  * Low Risk Recall: 91%
  
### Easy Ensemble AdaBoost Classifier

![easy_ensemble](png/easy_ensemble.png).

  * Balanced Accuracy Score: 92.5%
  * High Risk Precision: 7%
  * High Risk Recall: 91%
  * Low Risk Precision: 100%
  * Low Risk Recall: 94%
  
## Summary 
