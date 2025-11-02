This repository contains a self-practice machine learning classification model implemented in Python using Scikit-learn. The project uses the Diabetes Classification dataset to predict whether a person is diabetic or not based on features such as Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age. The target variable is Outcome (0 for non-diabetic, 1 for diabetic).



The model implemented in this project is the K-Nearest Neighbors (K-NN) Classifier, which predicts the class of a data point based on the majority class of its nearest neighbors. The model achieved an accuracy score of 0.799 (79.9%) on the test dataset, showing a slight improvement compared to Logistic Regression. This indicates that the K-NN algorithm is able to capture more complex, non-linear relationships in the data, making it a better fit for this dataset. Future experiments could include tuning the number of neighbors (K) or testing other distance metrics to further enhance performance.

