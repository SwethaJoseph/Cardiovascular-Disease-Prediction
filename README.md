# Cardiovascular-Disease-Prediction
## Project Overview
This project aims to predict the risk of heart attacks using various machine learning algorithms. Cardiovascular disease (CVD) is the leading cause of death worldwide, making early detection and intervention crucial. The project leverages machine learning techniques to analyze patient data and identify individuals at high risk for heart attacks, facilitating timely preventative measures and treatment.

## Motivation
Heart disease is a major health issue globally, and early detection can significantly improve patient outcomes. By using machine learning algorithms, we can analyze large datasets of patient health records to identify patterns and risk factors associated with heart disease. This project aims to enhance the accuracy and efficiency of heart attack prediction, ultimately reducing mortality rates and improving healthcare delivery.

## Project Aim
The primary goal is to develop a predictive model that accurately identifies individuals at risk of heart disease and heart attacks. The project involves data preparation, exploratory data analysis, training and testing various machine learning models, and evaluating their performance based on metrics such as accuracy, F1 score, precision, and recall.

## Data Description
The dataset is taken from Kaggle and the database contains 76 attributes:
* (age): age in years
* (sex): sex (1 = male; 0 = female)
* (cp): chest pain type -- Value 1: typical angina -- Value 2: atypical angina – Value 3: non-anginal pain -- Value 4: asymptomatic
* (trtbps): resting blood pressure (in mm Hg on admission to the hospital)
* (chol): serum cholestoral in mg/dl
* (fbs): (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* (restecg): resting electrocardiographic results -- Value 0: normal -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) -- Value 2: showing probable or 
  definite left ventricular hypertrophy by Estes' criteria
* (thalachh) : maximum heart rate achieved
* (exng) : exercise induced angina (1 = yes; 0 = no)
* (oldpeak) oldpeak = ST depression induced by exercise relative to rest
* (slp) : the slope of the peak exercise ST segment -- Value 1: upsloping --Value 2: flat -- Value 3: downsloping
* (caa) : number of major vessels (0-3) colored by flourosopy
* (thall) : 3 = normal; 6 = fixed defect; 7 = reversable defect
* (output) (the predicted attribute) : diagnosis of heart disease (angiographic disease status) -- Value 0: < 50% diameter narrowing -- Value 1: > 50% diameter narrowing (in any major vessel: attributes 59 
  through 68 are vessels)

## Machine Learning Algorithms Used
* Gaussian Naive Bayes
* Random Forest
* Gradient Tree-Boosting
* CatBoost
* AdaBoost

## Methodology
* Data Pre-processing: Clean and prepare the dataset for analysis.
* Exploratory Data Analysis: Visualize and analyze the data to identify patterns and correlations.
* Model Implementation: Implement various machine learning algorithms and train them on the dataset.
* Model Evaluation: Evaluate the models based on accuracy, F1 score, precision, and recall to determine the best-performing model.

## Findings
The project analyzes the impact of various factors on heart disease, such as age, gender, chest pain type, and other clinical features. It also evaluates the performance of different machine learning models to identify the most accurate one for heart attack prediction.

## Conclusion and Recommendations
The project demonstrates the potential of machine learning in predicting heart attacks and highlights the importance of selecting the right model for accurate predictions. Future work could focus on refining the algorithms and incorporating additional data sources to improve prediction accuracy.
