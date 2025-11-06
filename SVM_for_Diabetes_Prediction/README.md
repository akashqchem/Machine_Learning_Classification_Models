This repository contains a self-practice machine learning classification model implemented in Python using Scikit-learn. The project uses the Diabetes Classification dataset to predict whether a person is diabetic or not based on features such as Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age. The target variable is Outcome (0 for non-diabetic, 1 for diabetic).



The model implemented in this project is the Support Vector Machine (SVM) Classifier, which separates data into classes by finding the best possible boundary (or hyperplane) that maximizes the margin between them. Using a linear kernel, the model achieved an accuracy score of 0.779 (77.9%) on the test dataset. While the accuracy is similar to Logistic Regression, this result shows that the data has both linear and non-linear patterns that could be explored further. Future experiments could include testing non-linear kernels such as RBF or polynomial to better capture complex relationships in the dataset.

