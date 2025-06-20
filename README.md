# InternPe_AI_ML_Project_1
Diabetes Prediction with ML


## Project 1: Diabetes Prediction with ML
<br>

**Dataset**: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
<br>

(In particular, all patients in this dataset are females at least 21 years old of Pima Indian heritage) 



This project is part of my internship at InternPe, where I implemented Support Vector Machine Classifier to predict whether a patient is diabetic or non-diabetic based on various features such as a;
<br>
:) Pregnancies
<br>
:) Glucose
<br>
:) BloodPressure
<br>
:) SkinThickness
<br>
:) Insulin
<br>
:) BMI
<br>
:) DiabetesPedigreeFunction
<br>
:) Age 
<br>

**Project Overview :**
<br>
The goal of this project is to build a classification model that accurately predicts whether a patient is diabetic or non-diabetic based on various factors (as i mentioned above). 
<br>

**Tools Used :**
<br>
**Python** : For scripting and implementation.
<br>
**Google Colab** : For writing and running the code in a Jupyter Notebook environment.
<br>

**Libraries Used** :
<br>
**numpy**: For numerical computations.
<br>
**pandas**: For data manipulation and preprocessing.
<br>
**scikit-learn**: For building and evaluating the linear regression model.
<br>

**Implementation Steps** :
<br>
(1) **Data Preprocessing**: 
<br>
:) Handled missing values, if any.
<br>
:) Performed data exploration.
<br>

(2) **Feature Engineering**:
<br>
**Feature Scaling:** Standardized the dataset to ensure model accuracy and consistency.
<br>

(3) **Model Selection:**
<br>
:) Implemented a Support Vector Machine (SVM) classifier for its efficiency in handling classification problems.
<br>

(4) **Evaluation**:
<br>
:) Used metrics like Accuracy score , Confusion matrix and prepare a detailed classification report to evaluate model performance.
<br>

**Results**:
<br>
:) Achieved an **accuracy score** of 79.15% on training data and 72.08% on test data.
<br>
:) Generated a **confusion matrix** : [[83, 17], [26, 28]].
<br>
:) Produced a detailed **classification report:**
<br>
   **Precision:** 0.76 (class 0), 0.62 (class 1)
<br>
**Recall:** 0.83 (class 0), 0.52 (class 1)
<br>
**F1-Score:** 0.79 (class 0), 0.57 (class 1)
<br>
**Overall Accuracy:** 72% on test data.
