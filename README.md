# Classification-model-Machine Learning 

Diabetes Prediction Model

Overview
This project aims to build a machine learning classification model to predict whether an individual will develop diabetes within five years based on health metrics.
Diabetes is one of the most challenging chronic diseases that has a compounding factor on the general well-being of individuals.
In most cases, the disease can be averted if the risk is accurately outlined well in advance,
and healthy lifestyle changes are made. You have to create a classification model from the set of methods
we studied during the course, that can predict if someone will develop diabetes over the next 5 years.

Dataset
678 records with features like pregnancies, glucose, blood pressure, BMI, insulin, age, etc.
Target variable: Diabetes status (1 = Positive, 0 = Negative).

Objective
To develop and evaluate different machine learning classification models and determine the most effective one for predicting diabetes risk.
A written report explaining the solution, the outcomes, parameters
Implementing a well-commented, accurate classification method to solve the problem

Tools & Technologies Used
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

Methodology
Data Preprocessing – Checked for missing values, standardized features, and split dataset into training and testing sets.
Exploratory Data Analysis (EDA) – Visualized feature distributions, outliers, and correlations using histograms, box plots, and heatmaps.
Model Selection & Training – Evaluated multiple classification models, including:
Logistic Regression (Best performer)
Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Performance Evaluation – Assessed models using:
Accuracy: 78%
Precision: 74%
Recall (Sensitivity): 62%
Specificity: 87%
ROC AUC Score: 74%
Confusion Matrix

Results & Insights
Logistic Regression performed best, offering a balance of accuracy and interpretability.
Sensitivity was 62%, indicating it correctly identified 62% of individuals with diabetes.
Specificity was 87%, meaning it correctly classified 87% of non-diabetic individuals.

Files in Repository
diabetes_prediction.ipynb – Jupyter Notebook with full analysis.
Classification report for diabetes.pdf – Summary of findings and model evaluation.
data/diabetes.csv – Dataset (if shareable).





