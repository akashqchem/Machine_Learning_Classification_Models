This repository contains a self-practice machine learning classification model implemented in Python using Scikit-learn. The project uses the Diabetes Classification dataset to predict whether a person is diabetic or not based on features such as Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age. The target variable is Outcome (0 for non-diabetic, 1 for diabetic).



The model implemented in this project is the Naive Bayes Classifier, which applies Bayes’ Theorem to estimate the probability of a person belonging to each class based on their medical features. The Gaussian Naive Bayes approach was used, as the dataset contains continuous numerical values. The model achieved an accuracy score of 0.772 (77.2%) on the test dataset. Although its accuracy is slightly lower compared to other models like Logistic Regression, K-NN, SVM, and Kernel SVM, this model demonstrates how a simple probabilistic method can make fast and interpretable predictions without requiring feature scaling or complex parameter tuning.

