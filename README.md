**Fraud Transaction Detection**

This project aims to classify fraudulent transactions in a simulated dataset using Python. The dataset consists of 183 .pkl files, each containing transaction details such as transaction ID, customer ID, terminal ID, transaction amount, and a fraud label.

->**Key Features**

+**Simulated Fraud Scenarios:**

**High-Value Transactions:** Transactions above 220 are flagged as fraudulent.
**Terminal-Based Fraud**: A random terminal’s transactions are marked fraudulent for 28 days.
**Customer-Based Fraud**: A random customer has 1/3 of their transactions marked fraudulent, with amounts multiplied by 5.

+**Data Processing**:
Cleaned and preprocessed the dataset to ensure it is ready for analysis.
Utilized Pandas for data manipulation and Matplotlib for visualizations.

+**Machine Learning Models**

The following machine learning models were implemented to predict whether a transaction is fraudulent:

**Logistic Regression**
A simple baseline model for binary classification.

**Decision Tree Classifier**
Captures non-linear relationships between features and fraud labels.

**Random Forest Classifier**
An ensemble method that aggregates the results of multiple decision trees to improve accuracy.

**Support Vector Machine (SVM)**
Finds the optimal hyperplane separating fraudulent from non-fraudulent transactions.

**Gradient Boosting Machine (GBM)**
Builds trees sequentially to correct errors from previous models, improving overall accuracy, particularly with imbalanced data.

**Evaluation Metrics**:
Accuracy, Precision, Recall, F1-score, and Confusion Matrix were used to evaluate model performance and balance the detection of fraud with minimizing false positives and false negatives.


+**Technologies Used:**
Python
Pandas
Scikit-learn (for machine learning models)
Matplotlib (for data visualization)

+**Project Goals:**
To build an efficient fraud detection system capable of identifying fraudulent transactions in large datasets.
To apply machine learning algorithms to solve real-world financial fraud detection problems.

Regards,

Taniya Johnson
