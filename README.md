
# In this notebook, I explore the classification of breast cancer

 ### About this Dataset
Description:

Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.

The key challenges against it’s detection is how to classify tumors into malignant (cancerous) or benign(non cancerous).


for data visualization I used seaborn library


# In this notebook I use
*  Logistic Regression
*  GradientBoosting
*  KNN
*  Support Vector Machine Classifier
*  Gaussian Naive Bayes Classifier
*  Random Forest Classifier


### Using GridSearchCV I picked up the most suitable parameters for classification algorithms

# the estimates that the models showed


LogisticRegression Accuracy score : 0.9883 ROC-AUC score : 0.9874
GradientBoostingClassifier Accuracy score : 0.9591 ROC-AUC score : 0.9544
KNN Accuracy score : 0.9591 ROC-AUC score : 0.9511
SVC Accuracy score : 0.9883 ROC-AUC score : 0.9841
Naive Bayes Accuracy score : 0.9357 ROC-AUC score : 0.9292
RandomForestClassifier Accuracy score : 0.9708 ROC-AUC score : 0.9636

