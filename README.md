Fraud Transaction Detection
This project aims to classify fraudulent transactions in a simulated dataset using Python. The dataset contains 183 .pkl files, each representing transaction details such as transaction ID, customer ID, terminal ID, transaction amount, and a fraud label.

Key Features:
Simulated Fraud Scenarios:

Transactions above 220 are flagged as fraudulent.
Random terminal selections are marked fraudulent for 28 days.
A random customer has 1/3 of their transactions marked fraudulent, with amounts multiplied by 5.
Data Processing:

Cleaned and preprocessed the dataset to ensure it's ready for analysis.
Used Pandas for data manipulation and Matplotlib for data visualization.
Machine Learning Models:

Developed multiple models to predict whether a transaction is fraudulent or not, including:
Logistic Regression: A simple baseline model for binary classification.
Decision Tree Classifier: Used for capturing non-linear relationships between features.
Random Forest Classifier: An ensemble model improving accuracy by aggregating the results of multiple decision trees.
Support Vector Machine (SVM): Used for finding the optimal hyperplane to separate fraudulent and non-fraudulent transactions.
Gradient Boosting Machine (GBM): A powerful ensemble model that builds trees sequentially, improving accuracy and handling imbalanced data.
Evaluation Metrics:

Evaluated models based on accuracy, precision, recall, F1-score, and the confusion matrix to ensure high classification performance and minimize false positives/negatives.
Technologies Used:
Python
Pandas
Scikit-learn (for machine learning models)
Matplotlib (for data visualization)
Project Goals:
To build an efficient fraud detection system capable of identifying fraudulent transactions in large datasets.
To apply machine learning algorithms to solve real-world problems like financial fraud detection.


Regards,
Taniya Johnson
