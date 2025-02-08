Description
This script focuses on training and evaluating multiple machine learning classifiers on a dataset. It fetches data from the UCI Machine Learning Repository, preprocesses it, trains various models, and evaluates their performance using key metrics.

Key Functionalities:
Dataset Handling:

Fetches the Phishing Websites dataset from the UCI Machine Learning Repository using the ucimlrepo library.
Separates the data into features (X) and target (y).
Data Preprocessing:

Splits the dataset into training and testing sets using train_test_split.
Scales the features using StandardScaler for improved model performance.
Model Training:

Trains a variety of classifiers, including:
Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machines (SVM)
Multi-Layer Perceptron (MLP)
Random Forest
AdaBoost
Decision Tree
Linear Discriminant Analysis (LDA)
Model Evaluation:

Evaluates each classifier using the following metrics:
Accuracy Score: Measures overall correctness.
Precision: Proportion of true positive predictions.
Recall: Proportion of actual positives identified.
F1 Score: Harmonic mean of precision and recall.
Classification Report: Provides a detailed breakdown of model performance.
Output Comparison:

Outputs the evaluation results for each model, allowing comparison of their effectiveness on the dataset.
Libraries Used:
pandas and numpy: For data manipulation and handling.
sklearn (scikit-learn):
Preprocessing: Standard scaling of features.
Classifiers: Includes multiple machine learning algorithms.
Metrics: For performance evaluation.
ucimlrepo: To fetch datasets from the UCI Machine Learning Repository.
Applications:
Model Selection: Identify the best-performing classifier for a specific dataset.
Performance Comparison: Understand the strengths and weaknesses of different models.
Phishing Detection: Use the trained model to predict phishing websites.
