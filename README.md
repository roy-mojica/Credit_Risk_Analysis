# Credit Risk Analysis
Credit Risk Analysis using supervised machine learning models

## Overview of the analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

## Results: 
### The balanced accuary scores and classification report for all six machine learning models

For all six of the machine models below, we started by coverting our string values into numerical onces, and splitting the data into 'training' and 'testing' datasets.

- Naive Random Oversampling
  - Balanced Accuracy Score: 0.634096
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/naive_random_oversampling.PNG">
  
- SMOTE Oversampling
  - Balanced Accuracy Score: 0.655019
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/smote_oversampling.PNG">
  
- Undersampling
  - Balanced Accuracy Score: 0.520525
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/undersampling.PNG">
  
- Combination Sampling (Over and Under)
  - Balanced Accuracy Score: 0.624175
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/combination.PNG">
  
- Balanced Random Forest Classifier
  - Balanced Accuracy Score: 0.787767
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/brfc.PNG">
  
- Easy Ensemble AdaBoost Classifier
  - Balanced Accuracy Score: 0.925427
  <img src="https://github.com/roy-mojica/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/images/eeabc.PNG">

## Summary: 
Balanced Accuracy is the average of sensitivity and specificity with a min = 0 and max = 1; this score is most accurate the closer its value is to 1. Out of the 6 models we worked with in this analysis, we can see that "Easy Ensemble AdaBoost Classifier" has the highest balanced accuracy score at 0.925427.

F1 score tells us what percent of positive predictions were correct. If we look at the F1 score for all 6 models above we will see that the F1 score for "Easy Ensemble AdaBoost Classifier" is the higest as well at 0.97. F1 score is a weighted harmonic mean of precision and recall such that the best score is 1.0 and the worst is 0.0.

We can therfore recommend using the "Easy Ensemble AdaBoost Classifier" model for our data.
