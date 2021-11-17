---
title:  "Explanable Machine Learning for Heart Failure Prediction"
mathjax: false
layout: post
categories: media
---

![Block diagram](/assets/photos/Heart_failure_results.jpg)

## Introduction
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.
People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

## Objectives
The main objective of this work is to predict if a patient is at risk of having heart disease or not, based on the common features of patients with heart disease. To that end, four different methods, including **random forest**, **naïve bayes**, **kernel SVM**, and **XGBoost** are exploited and their performance is compared to find the best model for the prediction of heart disease.
Finally,  the obtained results are interpreted with **SHAP values** to see the effect of each feature on the prediction. It can help clinicians to better understand the reasons behind the prediction.


## Description of the dataset
This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets with a total of **918 observations** are combined over **11 common features** which makes it the largest heart disease dataset available so far for research purposes. The features are as the following:

1. *Age*: age of the patient [years]
2. *Sex*: sex of the patient [M: Male, F: Female]
3. *ChestPainType*: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. *RestingBP*: resting blood pressure [mm Hg]
5. *Cholesterol*: serum cholesterol [mm/dl]
6. *FastingBS*: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. *RestingECG*: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8. *MaxHR*: maximum heart rate achieved [Numeric value between 60 and 202]
9. *ExerciseAngina*: exercise-induced angina [Y: Yes, N: No]
10. *Oldpeak*: oldpeak = ST [Numeric value measured in depression]
11. *ST_Slope*: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- *HeartDisease*: output class [1: heart disease, 0: Normal]

Source of data: 
[https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/](https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/)
[https://www.kaggle.com/fedesoriano/heart-failure-prediction/](https://www.kaggle.com/fedesoriano/heart-failure-prediction/)

[Link to the code](https://github.com/alizrepo/Explainable_Heart_Failure_Predictor/blob/main/Explainable_Heart_Failure_Predictor.ipynb)
