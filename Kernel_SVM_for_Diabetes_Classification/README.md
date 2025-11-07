This repository contains a self-practice machine learning classification model implemented in Python using Scikit-learn. The project uses the Diabetes Classification dataset to predict whether a person is diabetic or not based on features such as Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age. The target variable is Outcome (0 for non-diabetic, 1 for diabetic).



The model implemented in this project is the Kernel Support Vector Machine (SVM), which uses the Gaussian RBF kernel to capture complex, non-linear relationships within the dataset. The kernel trick enables the model to behave as if it maps data into a higher-dimensional space without actually performing the transformation, allowing efficient and accurate separation of non-linear patterns. The model achieved an accuracy score of 0.805 (80.5%) on the test dataset - performing better than the Logistic Regression, K-Nearest Neighbors (K-NN), and linear SVM models. This demonstrates how the RBF kernel improves the model’s ability to generalize and capture subtle relationships in medical data.

