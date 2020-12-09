# Credit Risk Analysis 

## Overview 
Using the credit card credit dataset from LendingClub, a peer to peer lending services company, the goal is to resample the data using several methods including RandomOverSampler, SMOTE, ClusterCentroids and SMOTEEN to compare two machine learning models using BalancedRandomForrestClassifier and EasyEnsembleClassifier to predict credit risk.    

## Results 

### Naive Random Sampling 
![](https://raw.githubusercontent.com/asanchez116/Credit_Risk_Analysis/master/Resources/Screen%20Shot%202020-12-09%20at%2012.00.35%20AM.png)
### SMOTE Oversampling 
![](https://raw.githubusercontent.com/asanchez116/Credit_Risk_Analysis/master/Resources/Screen%20Shot%202020-12-09%20at%2012.00.45%20AM.png)
### Cluster Centroids Resampler 
![](https://raw.githubusercontent.com/asanchez116/Credit_Risk_Analysis/master/Resources/Screen%20Shot%202020-12-09%20at%2012.00.56%20AM.png)
### SMOTTEEN
![](https://raw.githubusercontent.com/asanchez116/Credit_Risk_Analysis/master/Resources/Screen%20Shot%202020-12-09%20at%2012.01.08%20AM.png)
### Balanced Random Forest 
![](https://raw.githubusercontent.com/asanchez116/Credit_Risk_Analysis/master/Resources/Screen%20Shot%202020-12-08%20at%2011.59.57%20PM.png)
### Easy Ensemble Classifier 
![](https://raw.githubusercontent.com/asanchez116/Credit_Risk_Analysis/master/Resources/Screen%20Shot%202020-12-09%20at%2012.00.14%20AM.png)
## Summary
resampling and undersampling had little effect on the logistic regression model. 
Easy Emsemble Classifier had the best F1 score for high risk between the two machine learning models. 
