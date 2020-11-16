# Realizing the importance of how to cluster e-commerce data to help understand the consumer

## Overview

Online retail is a transnational data set which contains all the transactions occurring between January 12, 2010 - September 12, 2011 for a store in the United Kingdoms. The company mainly sells unique all-occasion gifts. I will be pretending to be a data scientist who was hired by a global retail marketing company to analyze consumer data of this UK store, so that the company can create enriching marketing campaigns to attract more customers into buying their gift items. 

## Goals

Within the assignment, I will try to complete a segementation based on Customer's RFM. So that the company can efficiently target their customer base better in this I will complete the following actions below:
<ol>
  <li><b>Data Prep/Analyze:</b> Cleaning and aggregating the dataset so that it will not contain any missing, null, and outlier values.</li>
  <li><b>Data Vizualization:</b> You will see how the data columns stacks up to one another to bring out and answer question that are created from the vizualizations.</li>
  <li><b>Feature Engineering:</b> I will create add-ons to the data set from the pre-existing information to strengthen the machine learning model.</li>
  <li><b>Create/Establish Clustering model:</b> Here I am creating a clustering model and then comparing that models attributes against the labels to see which clusters need to be focused more on.</li>
</ol>

## Table of Contents

<ol>
  <li><a href=https://github.com/marcusw0602/DataAnalysis-and-Machine-Learning/blob/master/Assignments%26Projects/Clustering/OnlineRetail.csv.zip>Dataset</a>. Local copy of the original dataset from Repository.</li>
  <li><a href=https://github.com/marcusw0602/DataAnalysis-and-Machine-Learning/blob/master/Assignments%26Projects/Clustering/Clustering%20ML.ipynb>Summary/Report</a>: Jupyter Notebook including a detailed abstract on problems in assignment, code relevant to project, and visualizations supporting the completion of the project. </li>
  <li> <a href=https://github.com/marcusw0602/DataAnalysis-and-Machine-Learning/blob/master/Assignments%26Projects/Clustering/Code.ipynb>Code:</a> Used to clean, preprocess/report, and model the data for the final project output. </li>
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


## Conclusion
We can see that the data in the summary is fairly balanced with the number of orders made by customers except for the few outliers that we do have. These outliers can be seen with the bars that break out of the normal trend of not passing 2k-3k orders made.Also the top 5 customer that order items are from the UK.

From what you can see from the report, you have the most money spent per customer but with this being shown there are more outliers given an a lower amount of data that is in a normal range you can see that when the amount spent goes over 50k you can detemine this to be an outlier. Lastly, when comparing the top 5 orders to top 5 money spent there is only one match and that is.

- 14911 EIRE with 5675 orders and $143,825.06 spent

Below you will see the number of orders that have been place from the 1st Dec 2010 - 9th Dec 2011. In the bar graph you can see that there is a trend occurring every 2 to 3 months where the number of orders are rising and failing. If there is more to investigate would to see why there is a consistent rise and fall in throughout the year.

We can see here after looking at the cluster zero, one, and two that the customer that fail into the cluster 2 does not need to be focused on to grow the sales of the store. But what needs to happen is that the store will have to focus more on the customer who fall into the clusters of 0 and 1 becasue both clusters compared to cluster 2 did not report as well on the amount of spend and how often they bought an item. From this we will have to create some marketing strategies to target this specific customer to spend more and become more frequent when buy our items. More inmportantl customer from cluster 1 as they are the news customers to the store.

## Limitation and later works

What I would like to see and try later is that what does the data look like when we take out the the UK data and just leave the rest of the world. I would further the comparison between what a cluster chart with UK data and cluster chart without UK data looks like so that we can focus on bring the numbers in other countries up more than UK. 

<br>
<pre>
Contributors : <a href=https://github.com/marcusw0602>Demarcus Wirsing</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda
Libraries    : pandas, numpy, matplotlib, seaborn, sklearn
</pre>
