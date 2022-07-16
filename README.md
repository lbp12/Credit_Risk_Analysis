# Credit Risk Analysis
## Overview
In this analysis we are comparing different models to predit an individuals credit risk. This analysis evaluates each models performance of accuracy.

## Results
Naive Random Oversampling-<br>
The accuracy score for this model is 64%, the precision for high credit risk is at 1% while the recall is 62%.The precision for low credit risk is 100% and the recall is 67%.<br>
![naive_random_oversampling](https://github.com/lbp12/Credit_Risk_Analysis/blob/main/Images/naive_random_oversampling.png)<br>
<br>
SMOTE Oversampling-<br>
The accuracy score for this model is 62%, the precision for high credit risk is at 1% while the recall is 57%.The precision for low credit risk is 100% and the recall is 66%.<br>
![smote_oversampling](https://github.com/lbp12/Credit_Risk_Analysis/blob/main/Images/smote_oversampling.png)<br>
<br>
Undersampling-<br>
The accuracy score for this model is 52%, the precision for high credit risk is at 1% while the recall is 60%.The precision for low credit risk is 100% and the recall is 43%.<br>
![undersampling](https://github.com/lbp12/Credit_Risk_Analysis/blob/main/Images/undersampling.png)<br>
<br>
SMOTEEN Combination Sampling-<br>
The accuracy score for this model is 61%, the precision for high credit risk is at 1% while the recall is 68%.The precision for low credit risk is 100% and the recall is 54%.<br>
![smotten_combination_sampling](https://github.com/lbp12/Credit_Risk_Analysis/blob/main/Images/smoteen_combination_sampling.png)<br>
<br>
Balanced Random Forest Classifier-<br>
The accuracy score for this model is 79%, the precision for high credit risk is at 3% while the recall is 70%.The precision for low credit risk is 100% and the recall is 87%.<br>
![balanced_random_forest_classifier](https://github.com/lbp12/Credit_Risk_Analysis/blob/main/Images/balanced_forest_random_classifier.png)<br>
<br>
Easy Ensemble Classifier-<br>
The accuracy score for this model is 93%, the precision for high credit risk is at 9% while the recall is 92%.The precision for low credit risk is 100% and the recall is 94%.<br>
![easy_ensemble_classifier](https://github.com/lbp12/Credit_Risk_Analysis/blob/main/Images/easy_ensemble_sampling.png)<br>
<br>
## Summary
We reviewed 6 different machine learning models to predict credit risk. The first four models all had a similar accuracy, precision and recall rates. The last two models had a higher precision rate with Easy Ensemble having the highest at 93%. The Easy Ensemble Classifer is the suggested model to use because it had the highest rate of accuarcy as well as precision and recall for both high and low credit risk.
