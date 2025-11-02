Machine Learning Classification Models

This repository contains a collection of self-practice machine learning classification projects developed as part of my continuous learning journey in data science. Each project applies a different classification algorithm to the same dataset to compare their predictive performance and understand how various models separate data into distinct categories. The purpose of this repository is to strengthen my understanding of classification modeling concepts, implementation, and evaluation using consistent real-world data.

Dataset Information

All models in this repository use the Diabetes Classification dataset, which aims to predict whether a person is diabetic or not based on the following medical features:

Pregnancies – Number of times the patient has been pregnant

Glucose – Plasma glucose concentration after a glucose tolerance test

BloodPressure – Diastolic blood pressure (mm Hg)

SkinThickness – Triceps skinfold thickness (mm)

Insulin – 2-hour serum insulin (mu U/ml)

BMI – Body Mass Index (weight in kg/(height in m)²)

DiabetesPedigreeFunction – Function that scores likelihood of diabetes based on family history

Age – Age of the patient

The target variable is:

Outcome:

0 → Not Diabetic

1 → Diabetic

Objectives:

1. Implement and understand different types of classification algorithms.

2. Explore the impact of feature scaling, distance metrics, and kernel functions.

3. Compare model accuracy and interpret performance using confusion matrices.

4. Analyze how linear, distance-based, and ensemble models behave on the same dataset.

Included Projects:

1. Logistic Regression: Baseline linear model achieving 77.9% accuracy.

2. K-Nearest Neighbors (K-NN): Distance-based model achieving 79.9% accuracy.

3. Support Vector Machine (SVM): (Upcoming) Linear boundary-based classifier.

4. Kernel SVM: (Upcoming) Non-linear classifier using the RBF kernel.

5. Naive Bayes: (Upcoming) Probabilistic classifier using Bayes’ theorem.

6. Decision Tree Classification: (Upcoming) Rule-based model for classifying outcomes.

7. Random Forest Classification: (Upcoming) Ensemble of decision trees for higher stability and accuracy.

Tools and Libraries:

1. Python

2. Scikit-learn

3. NumPy

4. Pandas

Learning Outcome:

1. Through these classification models, I aim to develop a practical understanding of:

2. How different classification algorithms make predictions on the same dataset.

3. The effects of feature scaling and hyperparameter tuning.

4. Evaluating model performance using metrics such as accuracy, precision, recall, and confusion matrix.

5. How complex models like Kernel SVM or Random Forest improve upon simpler ones such as Logistic Regression.

All projects are implemented in Google Colab notebooks (.ipynb) using the Diabetes Classification dataset sourced from publicly available platforms such as Kaggle, created purely for self-learning and experimentation.
