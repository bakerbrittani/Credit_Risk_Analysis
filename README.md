# Credit_Risk_Analysis

## Overview of Analysis
Using undersampling, oversampling, combination and ensemble models to find the best model, we will help predict credit card risk. The results below will outline all 6 different methods used.  

## Results
### Random Oversampler
Overall accuracy score of 67%, not an excellent model to use for credit card risk assessment.

![CleanPic](/Images/NaiveRndmOversample.png)

### Smote Oversampler
Overall accuracy score of 64%, not an excellent model either.

![smote](/Images/SmoteOversample.png)

### Cluster Centroids Undersampler
Overall accuracy score of 69%, not a good model to use for credit card risk assessment still.

![pic](/Images/ClusterUndersample.png)

### Smoteenn Combo Sampler
Overall accuracy score of 70%, the best out of all over and undersampling models, but still not a good model to use for accurate credit card risk assessment.

![pic](/Images/SmoteenCombo.png)

### Balanced Random Forest Classifier
Overall accuracy score of 70%, comparable to the Smoteenn combo model and still not a great predictor of risk. 

![pic](/Images/BalancedRandomForestClassifier.png)

### Easy Ensemble Classifier
Overall accuracy score of 92%, the best out of all models would be a decent model to use for credit card risk assessment. 

![pic](/Images/EasyEnsembleClassifier.png)

## Summary
The best performing model for the credit risk assessment is the easy ensemble classifier. Other models that were untested may be better predictors, however of the 6 sampled here no other models were above 90%.
