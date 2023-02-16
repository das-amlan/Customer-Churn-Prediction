# Customer-Churn-Prediction

This project is aimed at predicting customer churn using machine learning algorithms. The analysis uses several models, including Logistic Regression, Decision Tree Classifier, ** Random Forest Classifier (which achieved the best result with 84% accuracy) **, Support Vector Machine (SVM), and Artificial Neural Network.

## Dataset
The analysis is based on a publicly available dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The dataset contains information about customers of a telecommunications company, including demographic information, services used, and whether they churned or not.

## Libraries Used
- pandas
- NumPy
- Matplotlib
- seaborn
- scikit-learn
- TensorFlow
- Keras

## Steps
The project is divided into the following steps:

- Importing required libraries
- Loading the dataset
- Exploratory Data Analysis
- Processing Data for Modeling
  - Handling missing values
  - Removing irrelevant data
  - One-hot encoding for columns with categorical data
  - Scaling data
  - Handling imbalanced data using the `SMOTE` method
- Test Train Split
- Modeling and Evaluation
Each step is explained in detail in the notebook.
