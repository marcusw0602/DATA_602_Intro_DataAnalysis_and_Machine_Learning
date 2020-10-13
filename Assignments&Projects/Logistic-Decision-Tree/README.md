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
  <li><a href=https://github.com/Lwhieldon/IstheMushroomPoisonous/blob/master/notebooks%2Bdata%2Bimages/mushrooms.csv>Dataset in Repo</a>. Local copy of the original dataset from the ICU Machine Learning Repository.</li>
  <li><a href=https://github.com/Lwhieldon/IstheMushroomPoisonous/blob/master/notebooks%2Bdata%2Bimages/labels.txt>Dataset Labels</a> A helpful text file explaining each feature label assigned to a mushroom. </li>
  <li><a href=https://github.com/Lwhieldon/IstheMushroomPoisonous/blob/master/notebooks%2Bdata%2Bimages/summaryreport.ipynb>Summary and Report</a>: Jupyter Notebook including a detailed abstract on problems in assignment, code relevant to project, and visualizations supporting the completion of the project. </li>
  <li> <a href=https://github.com/Lwhieldon/IstheMushroomPoisonous/blob/master/notebooks%2Bdata%2Bimages/code.ipynb>Code:</a> Area to perform testing of dataset, functions, and implement models before final project output. </li>
  <li> <a href=https://github.com/Lwhieldon/IstheMushroomPoisonous/blob/master/notebooks%2Bdata%2Bimages/utils.py>utils.py:</a> .py file to store functions I use throughout the project to make notebooks & summary report clean. </li>
</ol>

<br>
<pre>
Contributors : <a href=https://github.com/Lwhieldon>Lee Whieldon</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda
Libraries    : pandas, numpy, matplotlib, seaborn, sklearn
</pre>

<pre>
Assignment Submitted     : October 2020
</pre>

