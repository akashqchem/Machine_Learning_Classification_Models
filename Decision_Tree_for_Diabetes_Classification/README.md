This repository contains a self-practice machine learning classification model implemented in Python using Scikit-learn. The project uses the Diabetes Classification dataset to predict whether a person is diabetic or not based on features such as Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age. The target variable is Outcome (0 for non-diabetic, 1 for diabetic).



The model implemented in this project is the Decision Tree Classifier, which predicts outcomes by splitting the data into smaller groups using yes/no questions based on feature values. Each split is selected using the entropy criterion, which measures how pure or impure a split is. The model continues dividing the data until it reaches the leaf nodes, where final class predictions are made.



The Decision Tree model achieved an accuracy score of 0.727 (72.7%) on the test dataset, performing lower than other models such as Logistic Regression (77.9%), K-NN (79.9%), SVM (77.9%), Kernel SVM (80.5%), and Naive Bayes (77.2%). This lower accuracy indicates that the Decision Tree may have overfitted the training data or failed to generalize well. The results suggest that ensemble methods like Random Forest Classification could perform better by combining multiple trees for more stable and accurate predictions.

