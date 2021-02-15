# Credit Risk Analysis
Credit Risk Analysis using supervised machine learning models

## Overview of the analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

## Results: 
### The balanced accuary scores and classification report for all six machine learning models

For all six of the machine models below, we started by coverting our string values into numerical onces, and splitting the data into 'training' and 'testing' datasets.

- Naive Random Oversampling
  - Balanced Accuracy Score: 
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/naive_random_oversampling.PNG">
  
- SMOTE Oversampling
  - Balanced Accuracy Score:
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/smote_oversampling.PNG">
  
- Undersampling
  - Balanced Accuracy Score:
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/undersampling.PNG">
  
- Combination Sampling (Over and Under)
  - Balanced Accuracy Score: 
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/combination.PNG">
  
- Balanced Random Forest Classifier
  - Balanced Accuracy Score: 
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/brfc.PNG">
  
- Easy Ensemble AdaBoost Classifier
  - Balanced Accuracy Score: 
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/eeabc.PNG">

## Summary: 
