# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

This code employs different techniques to train and evaluate models on credit card risk using imbalanced-learn and scikit-learn. The goal is to assess which methods of machine learning will work best for assessing credit card risk. 


## Results:
  
### Naive Random Oversampling
- balanced accuracy score: .657
- precision score: .99
- recall score: .60

![Naive Random Oversample](https://github.com/K3Rob/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Images/NaiveRandomOver.PNG)

### SMOTE Oversampling
- balanced accuracy score: .662
- precision score: .99
- recall score: .69

![SMOTE Oversampling](https://github.com/K3Rob/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Images/SMOTEOver.PNG)

### Undersampling
- balanced accuracy score: .662
- precision score: .99
- recall score: .40

![Undersampling](https://github.com/K3Rob/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Images/Undersample.PNG)

### Combination (Over and Under) Sampling
- balanced accuracy score: .545
- precision score: .99
- recall score: .57

![Combination (Over and Under) Sampling](https://github.com/K3Rob/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Images/CombinationOverUnder.PNG)

### Balanced Random Forest Classifier
- balanced accuracy score: .788
- precision score: .99
- recall score: .91

![Balanced Random Forest Classifier](https://github.com/K3Rob/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Images/BalancedRandomForrest.PNG)

### Easy Ensemble AdaBoost Classifier
- balanced accuracy score: .925
- precision score: .99
- recall score: .94

![Easy Ensemble AdaBoost Classifier](https://github.com/K3Rob/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Images/EasyEnsembleAdaBoostClassifier.PNG)


## Summary:

While all of the models did well on precision the recall was best on the Easy Ensemble AdaBoost Classifier. The confusion matrix shows it has the best accuracy, minimizing the number of incorrect classifications of any of the other models. The F1 confirms this at .97 only the Balanced Random Forest Classifier appears to do nearly as well.

