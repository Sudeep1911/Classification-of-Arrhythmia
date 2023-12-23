# Classification-of-Arrhythmia

This project focuses on the classification of cardiac arrhythmias using machine learning techniques. The dataset used in this project is sourced from the UCI Machine Learning Repository and comprises 452 examples spread across 16 classes. The goal is to predict whether a person is suffering from arrhythmia and, if so, classify it into one of the 12 available groups.

Dataset Overview

Number of Instances: 452
Number of Classes: 16
Features: 279, including age, sex, weight, height, and other patient-related information

Data Preprocessing

The dataset undergoes thorough preprocessing, including handling missing values, imputing mean values, and addressing outliers. Additionally, exploratory data analysis (EDA) is conducted to understand the distribution of instances across different classes.

Machine Learning Models

Several classification models are employed to predict arrhythmias based on the preprocessed dataset:

K-Nearest Neighbors (KNN)
Logistic Regression
Decision Tree Classifier
Support Vector Machine (SVM)
Random Forest Classifier
Artificial Neural Networks (ANN)
Evaluation Metrics
Evaluation of the models is based on key metrics such as accuracy and recall score. Special emphasis is given to recall score, considering the importance of correctly identifying individuals with arrhythmia.

Results

The project provides a comparative analysis of different models, showcasing their training and testing accuracy. Additionally, Receiver Operating Characteristic (ROC) curves are plotted for a more comprehensive understanding of the model performance.

Conclusion

The Logistic Regression model demonstrates the highest recall score, indicating its effectiveness in identifying instances of arrhythmia. The Random Forest Classifier also exhibits strong accuracy. The choice of the optimal model may depend on specific requirements and trade-offs between precision and recall.
