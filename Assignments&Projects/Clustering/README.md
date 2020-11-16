# Realizing the importance of how to cluster e-commerce data to help understand the consumer

## Overview

Online retail is a transnational data set which contains all the transactions occurring between January 12, 2010 - September 12, 2011 for a store in the United Kingdoms. The company mainly sells unique all-occasion gifts. I will be pretending to be a data scientist who was hired by a global retail marketing company to analyze consumer data of this UK store, so that the company can create enriching marketing campaigns to attract more customers into buying their gift items. 

## Goals

Within the assignment, I will try to complete a segementation based on Customer's RFM. So that the company can efficiently target their customer base better in this I will complete the following actions below:
<ol>
  <li><b>Data Prep/Analyze:</b> Cleaning and aggregating the dataset so that it will not contain any missing, null, and outlier values.</li>
  <li><b>Data Vizualization:</b> You will see how the data columns stacks up to one another to bring out and answer question that are created from the vizualizations.</li>
  <li><b>Feature Engineering:</b> I will create add-ons to the data set from the pre-existing information to strengthen the machine learning model.</li>
  <li><b>Create/Establish Clustering model:</b> Here I am creating two clustering models and then comparing boths succession rates to determine the best model to use.</li>
</ol>

## Dataset Details
<a href=https://github.com/marcusw0602/DataAnalysis-and-Machine-Learning/blob/master/Assignments%26Projects/Clustering/OnlineRetail.csv.zip>E-commerce retail dataset</a>: This dataset contains 541909 rows of data and 8 columns of attributes. 

#### Data attribute information
- InvoiceNo: Invoice number 6-digit integral number, Object.
- StockCode: Product code 5-digit integral number, Object.
- Description: Product name, Object.
- Quantity: The quantities of each product per transaction, int64.
- InvoiceDate: Invice date and time, int64.
- UnitPrice: Unit price, int64.
- CustomerID: Customer number, Object.
- Country: Country name, Object. 

## Table of Contents

<ol>
  <li><a href=https://github.com/marcusw0602/DataAnalysis-and-Machine-Learning/blob/master/Assignments%26Projects/Clustering/OnlineRetail.csv.zip>Dataset</a>. Local copy of the original dataset from Repository.</li>
  <li><a href=https://github.com/marcusw0602/DataAnalysis-and-Machine-Learning/blob/master/Assignments%26Projects/Clustering/Clustering%20ML.ipynb>Summary/Report</a>: Jupyter Notebook including a detailed abstract on problems in assignment, code relevant to project, and visualizations supporting the completion of the project. </li>
  <li> <a href=https://github.com/marcusw0602/DataAnalysis-and-Machine-Learning/blob/master/Assignments%26Projects/Clustering/Code.ipynb>Code:</a> Used to clean, preprocess/report, and model the data for the final project output. </li>
</ol>

## Conclusion
## Limitation and later works

<br>
<pre>
Contributors : <a href=https://github.com/marcusw0602>Demarcus Wirsing</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda
Libraries    : pandas, numpy, matplotlib, seaborn, sklearn
</pre>
