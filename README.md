# Module 17 Challenge - Credit Risk Analysis

## Overview of the Analysis

The purpose of the analysis is to use 
different machine learning models to predict credit risk for FinTech (financial technology) firms. The credit card credit dataset contains data from 2019 Q1 and is provided by LendingClub.

## Results

### Random Sampling

The balanced accuracy score is 65%.  The imbalanced classification report shows high-risk precision at 1% with recall (sensitivity) with f1 at 2%. The low-risk class number is high giving it a 100% precision and recall of 65%.

![RandomBalancedAccuracy](Resources/RandomBalancedAccuracy.png)

![RandomImbalancedClass](Resources/RandomImbalancedClass.png)


### COMBO - Over and Under Sampling

The balanced accuracy score is 64% (rounded).  The imbalanced classification report shows high-risk precision at 1% with recall (sensitivity) with f1 at 2%. Similar to Random Sampling. The low-risk class number is high giving it a 100% precision and recall of 545%.

![Redo-ComboAccuracy](Resources/Redo-ComboAccuracy.png)

![Redo-ComboClassif](Resources/Redo-ComboClassif.png)


### Ensemble/Random Forest

The balanced accuracy score is 79%. The highest of all the models. The imbalanced classification report shows high-risk precision at 3% with recall (sensitivity) with f1 at 71%. The low-risk class number is high giving it a 100% precision and recall of 88%.

![EnsembleBalancedAccuracy](Resources/EnsembleBalancedAccuracy.png)

![EnsembleImbalancedClass](Resources/EnsembleImbalancedClass.png)


### SMOTE

Similar to Random Sampling, the balanced accuracy score is 64%.  The imbalanced classification report shows high-risk precision at 1% with recall (sensitivity) with f1 at 2%. The low-risk class number is high giving it a 100% precision and recall of 65%.

![SMOTEBalancedAccuracy](Resources/SMOTEBalancedAccuracy.png)

![SMOTEImbalancedClass](Resources/SMOTEImbalancedClass.png)


### Undersampling

The balanced accuracy score is 52%. The imbalanced classification report shows high-risk precision at 1% with recall (sensitivity) with f1 at 1%. The low-risk class number is high giving it a 100% precision and recall of 46%.

![Redo-UndersamplingAccuracy](Resources/Redo-UndersamplingAccuracy.png)

![Redo-UndersampImbalance](Resources/Redo-UndersampImbalance.png)


### AdaBoost

The balanced accuracy score similar to Undersampling, SMOTE and Random Sampling is also 64% with . The imbalanced classification report shows high-risk precision at 1% with recall (sensitivity) with f1 at 1%. The low-risk class number is high giving it a 100% precision and recall of 63%.

![AdaBoostBalancedAccuracy](Resources/UndersampleBalancedAccuracy.png)

![AdaBoostImbalancedClass](Resources/UndersampleImbalancedClass.png)


## Summary

Most of the models are not preferred since the precision score for high-risk is low at 0.01. Models AdaBoost, Undersampling, SMOTE had the same accuracy score at 64%, Random slightly higher at 65% and OverSampling the lowest at 51%. The Ensemble/Random Forest had the highest precision at 79% with recall/sensitivity at 71% for high-risk and 88% for low-risk. Precision was low for high-risk at 3% with only 71% recall and f1 of 6%. 

