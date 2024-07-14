# Diabetes Prediction Model

This project involves building a machine learning model to predict the likelihood of diabetes based on various health metrics. The dataset used contains information such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age of individuals.

## Project Overview

The project consists of the following steps:

1. **Importing Libraries & Loading the Dataset**:
   - Python libraries like pandas, numpy, and sklearn are used.
   - The dataset (`diabetes.csv`) is loaded and its structure is inspected.

2. **Exploratory Data Analysis (EDA)**:
   - Basic statistical analysis and visualization of the dataset.
   - Checking for missing values, data types, and distribution of variables.
   - Understanding the balance of the target variable (`Outcome`: 0 for non-diabetic, 1 for diabetic).

3. **Data Preprocessing**:
   - Scaling numeric features using `StandardScaler` to ensure all features have the same scale.
   - Splitting the dataset into training and testing sets (`X_train`, `X_test`, `Y_train`, `Y_test`).

4. **Model Training**:
   - Using Support Vector Machine (SVM) for classification.
   - Training the model on the training data (`X_train`, `Y_train`).

5. **Model Evaluation**:
   - Evaluating the trained model on the test data (`X_test`, `Y_test`).
   - Measuring accuracy as the primary metric.

6. **Conclusion**:
   - Summary of findings and potential areas for improvement.
     
## ## Dataset

The dataset (`diabetes.csv`) contains 768 rows and 9 columns.

Columns:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age in years
- **Outcome**: Class variable (0 or 1) indicating diabetes status

## Results

The SVM model achieved an accuracy of 0.81 on the test set.


   
   
   
   
