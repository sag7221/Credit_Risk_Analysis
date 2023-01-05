# Credit_Risk_Analysis
Implementing imbalanced class algorithms and evaluating the credit risk with metrics

## Overview
Credit risk analysis is an inherently unbalanced classification problem as you normally come across good loans far exceeding risky loans. But due to the risk associated with okaying a bad loan, we need to make sure our algorithm has a high sensitivity to bad loans.

Here we are trying this out using different Supervised unbalanced Machine Learning algorithms and then we shall analyse which works well or does not work well or is ok for our problem statement.

### Results
Below are the list of all 6 machine learning models with their corresponding balanced accuracy scores and precision and recall values.

* Naive Random Oversampling
![Random Oversampling](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/Random_Oversampling.png)
* SMOTE Oversampling¶
![SMOTE Oversampling](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/SMOTE_Oversampling.png)
* Undersampling using ClusterCentroids method
![ Undersampling with Cluster_Centroids](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/Cluster_Centroids.png)
* SMOTEENN (Combination of both oversampling and undersampling)
![ SMOTEENN](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/Combination_SMOTEEN.png)
* Balanced Random Forest Classifier
![ Random_Forest_Classifier](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/Random_Forest_Classifier.png)
* Easy Ensemble AdaBoost Classifier
![ AdaBoost Classifier](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/AdaBoost_Classifier.png)





