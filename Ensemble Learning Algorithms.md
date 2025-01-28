##### Ensemble Learning Algorithms

Ensemble methods combine multiple models to improve performance.

------

### **1. Bagging (Bootstrap Aggregating)**

- **What it does**: Combines predictions from multiple models trained on different subsets of data to reduce variance and prevent overfitting.

- Example

  :

  - **Random Forest**: A collection of decision trees that predict an output by averaging (for regression) or voting (for classification).
  - **Real-Life Use**: Predicting house prices by using different subsets of housing data to ensure a balanced prediction.

------

### **2. Boosting**

- **What it does**: Trains models sequentially, where each model focuses on correcting the errors of the previous one. Boosting reduces bias and improves accuracy.

- **Popular Algorithms**: AdaBoost, Gradient Boosting, XGBoost, LightGBM, CatBoost.

- Example

  :

  - **Fraud Detection**: Identifying fraudulent transactions by iteratively refining the model to focus on misclassified cases.
  - **Customer Churn Prediction**: Boosting improves accuracy by focusing on churn cases that are harder to classify.

------

### **3. Stacking**

- **What it does**: Combines predictions from multiple models (base models) using a meta-model to improve overall accuracy.

- Example

  :

  - **Healthcare Diagnostics**: Combining predictions from models like SVM, Decision Trees, and Logistic Regression to diagnose diseases more accurately.
  - **Ensemble for Competitions**: Commonly used in Kaggle competitions to combine the strengths of different models.

------

### **Key Difference**:

- **Bagging**: Reduces variance by averaging multiple models (independent training).
- **Boosting**: Reduces bias by improving upon previous models (sequential training).
- **Stacking**: Uses the predictions of multiple models to train a meta-model for better accuracy.