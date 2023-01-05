# Credit_Risk_Analysis
Implementing imbalanced class algorithms and evaluating the credit risk with metrics

## Overview
Credit risk analysis is an inherently unbalanced classification problem as you normally come across good loans far exceeding risky loans. But due to the risk associated with okaying a bad loan, we need to make sure our algorithm has a high sensitivity to bad loans.

Here we are trying this out using different Supervised unbalanced Machine Learning algorithms and then we shall analyse which works well or does not work well or is ok for our problem statement.

### Results
Below are the list of all 6 machine learning models with their corresponding balanced accuracy scores and precision and recall values.

* Naive Random Oversampling
Balanced Accuracy Score: 66%
Precision for High Risk is: 1%
Recall (Sensitivity) is: 71%
![Random Oversampling](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/Random_Oversampling.png)
* SMOTE Oversampling¶
Balanced Accuracy Score: 65%
Precision for High Risk is: 1%
Recall (Sensitivity) is: 63%
![SMOTE Oversampling](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/SMOTE_Oversampling.png)
* Undersampling using ClusterCentroids method
Balanced Accuracy Score: 53%
Precision for High Risk is: 1%
Recall (Sensitivity) is: 67%
![ Undersampling with Cluster_Centroids](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/Cluster_Centroids.png)
* SMOTEENN (Combination of both oversampling and undersampling)
Balanced Accuracy Score: 64%
Precision for High Risk is: 1%
Recall (Sensitivity) is: 72%
![ SMOTEENN](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/Combination_SMOTEEN.png)
* Balanced Random Forest Classifier
Balanced Accuracy Score: 78.8%
Precision for High Risk is: 3%
Recall (Sensitivity) is: 70%
![ Random_Forest_Classifier](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/Random_Forest_Classifier.png)
* Easy Ensemble AdaBoost Classifier
Balanced Accuracy Score: 93%
Precision for High Risk is: 9%
Recall (Sensitivity) is: 92%
![ AdaBoost Classifier](https://github.com/sag7221/Credit_Risk_Analysis/blob/main/images/AdaBoost_Classifier.png)





