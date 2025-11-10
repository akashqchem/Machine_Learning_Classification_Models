This repository contains a self-practice machine learning classification model implemented in Python using Scikit-learn. The project uses the Diabetes Classification dataset to predict whether a person is diabetic or not based on features such as Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age. The target variable is Outcome (0 for non-diabetic, 1 for diabetic).



The model implemented in this project is the Random Forest Classifier, an ensemble learning method that combines multiple Decision Trees to make more accurate and stable predictions. Each tree is trained on random subsets of the data and features, and the final prediction is made through majority voting among all trees. In this project, the model was trained using 150 estimators, which provided the best balance between accuracy and performance for this dataset.



The Random Forest model achieved an accuracy score of 0.798 (79.87%) on the test dataset - higher than the Decision Tree Classifier (72.7%) and comparable to other models such as Logistic Regression (77.9%), K-NN (79.9%), SVM (77.9%), Kernel SVM (80.5%), and Naive Bayes (77.2%). This result highlights the strength of Random Forest in reducing overfitting and improving generalization by averaging the predictions of multiple trees.

