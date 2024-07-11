**On this notebook:**
# We are trying to predict customer response (e.g., 'yes' or 'no' to a marketing offer) using ML predicting model
# I explored data visualization to understand relationships between features like age, job, balance, and the target variable 'y'.
# I compared the performance of four machine learning models: KNeighborsClassifier, Logistic Regression, Support Vector Machine, and Decision Tree.
# GridSearchCV was used for hyperparameter tuning to optimize each model for the 'roc_auc' metric.
# Confusion matrices were generated to visualize the performance of each model in terms of true positives, false positives, true negatives, and false negatives.
# A precision-recall curve was plotted to compare the trade-off between precision and recall for the different models.
# - Certain features (e.g., balance, age) might have predictive power for the target variable.
# - The choice of model and hyperparameters significantly impacts performance.
------------------------
**Precision and Recall Analysis**

Model - Precision (%) - Recall (%)
KNN - 73 - 41
Logistic Regression - 67 - 49
SVC - 63 - 56
Decision Tree - 64 - 54
