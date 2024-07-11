This python application using jupyter notebookm compares the results of k-nearest neighbors, logistic regression, decision trees, and support vector machines classification models using dataset related to the marketing of bank products over the telephone.

The analysis leverages a telephone bank marketing dataset and evaluates four classification algorithms: K-Nearest Neighbors, Logistic Regression, Support Vector Machines, and Decision Trees. Model performance is assessed using metrics like precision-recall curves and confusion matrices to identify the model with the most accurate prediction capability.

Dataset Summary for bank-full.csv
Features: 17
Data Points: 6316
Target Variable:
Name: y
Type: categorical (nominal)
Description: client subscribed to term deposit (yes/no)
Imbalanced: True
**Numerical Features:**
age
balance
previous
campaign
pdays

**Categorical Values**

Features:
Feature 2
Feature 6
Feature 7
Feature 8
Feature 9
Feature 10
Feature 11
Feature 12
Feature 13
Feature 14
Feature 15
Feature 16

Data Quality:
Missing Values: None (no NaN values)
Duplicates: None (no duplicates observed)
-----------------
**On this notebook:**

# We are working on a binary classification problem, related to predicting customer response (e.g., 'yes' or 'no' to a marketing offer).
# I explored data visualization to understand relationships between features like age, job, balance, and the target variable 'y'.
# I compared the performance of four machine learning models: KNeighborsClassifier, Logistic Regression, Support Vector Machine, and Decision Tree.
# GridSearchCV was used for hyperparameter tuning to optimize each model for the 'roc_auc' metric.
# Confusion matrices were generated to visualize the performance of each model in terms of true positives, false positives, true negatives, and false negatives.
# A precision-recall curve was plotted to compare the trade-off between precision and recall for the different models.
# - Certain features (e.g., balance, age) might have predictive power for the target variable.
# - The choice of model and hyperparameters significantly impacts performance.
# - You can assess which model might be most suitable based on the desired balance between precision and recall.

------------------------
**Precision and Recall Analysis**

Model - Precision (%) - Recall (%)
KNN - 73 - 41
Logistic Regression - 67 - 49
SVC - 63 - 56
Decision Tree - 64 - 54
