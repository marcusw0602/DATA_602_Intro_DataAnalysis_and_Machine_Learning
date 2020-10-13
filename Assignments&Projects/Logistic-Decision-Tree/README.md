# Cardiovascular Prediction: Will you be diagnosed with heart complications?

## Overview

Can we tell by looking at a person's medical history that they can develop CVD, yes! But can we also use that history/information and predict whether or not a person that does not have the disease will develop it? That will be answered today. In this project, I compare logistic regression with Decision Tree classification to accurately predict if a person will become positive or negative for CVD.

## Goals

In this project, I will attempt to complete the following below:
<ol>
<li><b>Explore CVD Features in relation to themselves and CVD:</b> Examine features of toxic versus edible North American gilled mushrooms.</li>
<li><b>Model comparison:</b> I will be comparing two very common used classification models for accuracy: Logistic Regression and Decision Tree Classification.</li>
</ol>

## Motivation and Background

Can we tell by looking at a person's medical history that they can develop CVD, yes! But can we also use that history/information and predict whether or not a person that does not have the disease will develop it? That will be answered today. There are also a number of underlying determinants of CVDs or "the causes of the causes". These are a reflection of the major forces driving social, economic and cultural change – globalization, urbanization and population ageing. Other determinants of CVDs include poverty, stress and hereditary factors.

In this report, I am pretending to be a data scientist that works for the CDC in Atlanta, GA. I was given the task to predict negative and positive cases of CVD using certain health measurements from those that were either tested negative or positive for the disease. In hopes to detect CVD in patients based on their medical levels reaching a certain threshold.

A person can either positive for CVD or be negative. The somewhat challenging portion is taking unique health readings from each case and predict if they will develop the disease. This I will try to do using both a logistical regression model and Decision Tree classifier to see which model has the best accuracy in predictions.

## Data Details

<a href=https://www.kaggle.com/sulianova/cardiovascular-disease-dataset>Cardiovascular Dataset</a>

This dataset contains 70000 entries corresponding to 13 columns of health factors that contribute to CVD.

## Features
- AGE:  integer (years of age)
- WEIGHT: integer (kg)
- GENDER: categorical (0: female, 1: male)
- AP_HIGH: systolic blood pressure, integer
- AP_LOW: diastolic blood pressure, integer 
- CHOLESTEROL: categorical (1: normal, 2: above normal, 3: well above normal)
- GLUCOSE: categorical (1: normal, 2: above normal, 3: well above normal)
- BMI: integer

## Target
- CARDIO_DISEASE:  categorical (0: no, 1: yes)

## Table of Contents

<ol>
  <li><a href=https://github.com/marcusw0602/DATA_602_Intro_DataAnalysis_and_Machine_Learning/blob/master/Assignments%26Projects/Logistic-Decision-Tree/Cardio.csv>Dataset</a>. Local copy of the original dataset from Repository.</li>
  <li><a href=https://github.com/marcusw0602/DATA_602_Intro_DataAnalysis_and_Machine_Learning/blob/master/Assignments%26Projects/Logistic-Decision-Tree/Summary.ipynb>Summary/Report</a>: Jupyter Notebook including a detailed abstract on problems in assignment, code relevant to project, and visualizations supporting the completion of the project. </li>
  <li> <a href=https://github.com/marcusw0602/DATA_602_Intro_DataAnalysis_and_Machine_Learning/blob/master/Assignments%26Projects/Logistic-Decision-Tree/code.ipynb>Code:</a> Used to clean, preprocess/report, and model the data for the final project output. </li>
</ol>

## Conclusion
When creating the two models I am seeing better performance in identifying positive and negative case of CVD in the Decision Tree classifier than that of the logistic regression. 

For the Decision tree model all three precision, recall, and f1-score precentages are better than that of the logistic model. However with this this being a disease and a leader in american deaths we would want the accuracy for predicting positive and negative case to be significantly higher. We would want the accuracy in the threshold of 95-97% then that of 73-74% with about a +20% giving the wrong predictions. 

I do believe that we can certainly improve this model and dataset to include certain food groupings and other health factors that are contributors to this disease that strengthen our predictions.  

## Limitation and later works

There were no limitations as far as modeling the data using the Decision Tree and Logistic Regression. I would say that for later works I would be very interested in breaking the dataset apart and modeling the predictions in women and men seperate. As seen in the report women have a tremendous amount of cases than men along with a significant amount of positive case to add. 

<br>
<pre>
Contributors : <a href=https://github.com/marcusw0602>Demarcus Wirsing</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda
Libraries    : pandas, numpy, matplotlib, seaborn, sklearn
</pre>
