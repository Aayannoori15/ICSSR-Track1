This repository contains a classification project where multiple machine learning models were trained, tuned, and evaluated to find the best-performing approach for the dataset.

Data Splitting
The dataset was split into training and validation sets using a train–test split, ensuring that model performance was evaluated on unseen data. Cross-validation was used Logistic Regression.

Models & Training
The following models were trained and evaluated:

Logistic Regression
K-Nearest Neighbors (KNN)
Gaussian Naive Bayes
Decision Tree

Hyperparameter tuning was performed for KNN (number of neighbors) and Decision Tree (maximum depth) to improve performance and reduce overfitting.

Evaluation Metrics
Model performance was evaluated using accuracy, which was consistently applied across all models for fair comparison.

Results
Final validation accuracies:
Logistic Regression: 0.8219
Decision Tree: 0.8027
KNN: 0.8013
Gaussian Naive Bayes: 0.7360

Best Result
Logistic Regression achieved the highest accuracy (0.8219) and was selected as the best-performing model for this dataset.
