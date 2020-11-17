
# Credit_Risk_Analysis

## Overview
The goal of this assignment was to read in a large dataset, clean and filter it, and use various training models to predict credit risk.

## Results
### Random Oversampling
Accuracy: 0.65
![stats](https://raw.githubusercontent.com/si1ver1/Credit_Risk_Analysis/main/images/randomOversampling.jpg)
### SMOTE Oversampling
Accuracy: 0.65
![stats](https://raw.githubusercontent.com/si1ver1/Credit_Risk_Analysis/main/images/smoteOversampling.jpg)
### Undersampling (ClusterCentroids)
Accuracy: 0.51
![stats](https://raw.githubusercontent.com/si1ver1/Credit_Risk_Analysis/main/images/undersampling.jpg)
### Combination (SMOTEENN)
Accuracy: 0.64
![stats](https://raw.githubusercontent.com/si1ver1/Credit_Risk_Analysis/main/images/combination.jpg)
### Balanced Random Forest Classifier
Accuracy: 0.79
![stats](https://raw.githubusercontent.com/si1ver1/Credit_Risk_Analysis/main/images/balancedRandomForest.jpg)
### Easy Ensemble
Accuracy: 0.93
![stats](https://raw.githubusercontent.com/si1ver1/Credit_Risk_Analysis/main/images/easyEnsemble.jpg)

## Summary
According to the data above the Easy Ensemble is the best model for our credit loans. It has a high accuracy rate of 93%. The precision, recall, and f1 score are all above 0.9 meaning almost no low_risk credit loans are missed. While the precision and f1 score are low for high_risk it has high recall which means we have a low number of false negatives.