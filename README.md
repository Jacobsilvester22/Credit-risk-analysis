# Credit-risk-analysis
## Overview 
Using the credit card credit dataset from LendingClub we oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally comparing two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.
## Results
### Random Oversampling
![Screen Shot 2022-08-17 at 5 40 49 PM](https://user-images.githubusercontent.com/101231388/185248327-43536b2e-820e-419c-ba9b-536137bc963b.png) <br>
* Balanced Accuracy: 0.648767580808264
* Precision: High - 1% Low - 100%
* Recall: High - 61% Low - 69%
### SMOTE 
![Screen Shot 2022-08-17 at 5 46 27 PM](https://user-images.githubusercontent.com/101231388/185248972-d3e02f59-1be8-49d5-9b63-640aec0d3a6c.png) <br>
* Balanced Accuracy: 0.6159507435206336
* Precision: High - 1% Low - 100%
* Recall: High - 59% Low - 65%
### ClusterCentroids Undersampling
![Screen Shot 2022-08-17 at 5 48 56 PM](https://user-images.githubusercontent.com/101231388/185249331-4c3832db-178d-4ba3-90e0-9702d6b796e2.png) <br>
* Balanced Accuracy: 0.5295947802474508
* Precision: High - 1% Low - 100%
* Recall: High - 61% Low - 45%
### SMOTEEN
![Screen Shot 2022-08-17 at 5 51 23 PM](https://user-images.githubusercontent.com/101231388/185249676-397dfa65-9018-4dfb-9dd0-32279407e5ed.png) <br>
* Balanced Accuracy: 0.6419346846030192
* Precision: High - 1% Low - 100%
* Recall: High - 70% Low - 58%
### Balanced Random Forest Classifier
![Screen Shot 2022-08-17 at 5 54 58 PM](https://user-images.githubusercontent.com/101231388/185250176-7dc222ef-15be-4cf8-9406-6f8ba94375d9.png) <br>
* Balanced Accuracy: 0.7877672625306695
* Precision: High - 4% Low - 100%
* Recall: High - 67% Low - 91%
### Easy Ensemble AdaBoost Classifier
![Screen Shot 2022-08-17 at 5 57 20 PM](https://user-images.githubusercontent.com/101231388/185250500-c2aad395-8683-4bb0-882a-1c8d33a570e9.png) <br>
* Balanced Accuracy:0.925427358175101
* Precision: High - 7% Low - 100%
* Recall: High - 91% Low - 94%
## Summary
Our first four models preformed poorly with lower precision making them unfit for credit risk analysis. Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier preformed much better. Balanced Random Forest Classifier had a balanced accuracy of 79% but the Easy Ensemble AdaBoost Classifier had a balanced accuracy of 92.5%, making that specific model the most fit for determing credit risk relative to the other five models.

