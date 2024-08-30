# Custsomer-Segmentation
### Machine Learning Project
![](mall.jpg)
___
## Introduction

This is a data analysis project that demonstrate how my ability to perform customer segmentation on a specific group of customers. Here, I identified the best possible cluster using the KMeans unsupervised machine learning algorithm to find the univariate, bivariate, and multivariate clusters.  Once these clusters were identified, summary statistics was performed on them to identify the best  for marketing campaign.

**_Disclaimer_**: _The dataset and all the reports in this analysis do not represent any real company or entity. It's just for demonstration of Excel skills_.

## Problem Statement

The management of Nice Shoppings want to understand the Target Customers for the marketing team to plan a strategy. My own immediated boss has contacted me to identify the most important shopping groups based on income, age and the mall shopping score. He would like the number of ideal groups with a label for each to be part of the report to the management.

## My Objective: Market Segmentation

My objective in this project is to divide the target market into approachable groups. I will create subsets of a market based on demographics behavioral criteria to better understand the target for marketing activities.

## The Approach

- Perform some quick Expolratory Data Analysis (EDA)
  
- Use k-means Clustering Algorithm to create our segments

- Use summary statistics on the clusters

- Visualize

## Requirements

- Standard Python Installation

- Jupiter Notebook

  ![](note.png)

## Skills/Concepts Demonstrated

- Unsupervised Machine Learning
- Cluster Analysis
- Customer Segmentation
- Univariate, Bivariate and Multivariate Analysis

## Getting the Data
The dataset was downloaded from a website. You can access the dataset [here](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbU1OZmNSNXVubmM0M3dSS21KSXZaTWpndWkyd3xBQ3Jtc0tuUUl2dXd6b192dE1SbzZFZDJtd3dnZFN3QW1iYi05alMyU1NDc08xSDFZcTNGZGw1TldXYzBNZXVRaERIeW5LTEJiNHc4dG5xdFZxTFVwWHplMGRucEtKa0hpMHpkbTRBODJlUGJZWEo0eTdGa3FyNA&q=https%3A%2F%2Fabsentdata.com%2Fdata-analysis%2Fwhere-to-find-data%2F&v=iwUli5gIcU0).
The CSV file has 5 columns and 200 rows. 

## Investigating the Data
The dataset was checked for relevance to the evaluation questions. Also, the use of the data did not breach any data-related laws.

## Preparing the Data/ Data Transformation

The dataset was thouroughly examined before proceeding to EDA:

#### Check for null values
df.isnull().sum()

#### Check for Duplicates
df.duplicated().sum()

## EDA/Analysis and Visualizations

- Using df.describe(), statistics of the numeric values was shown

- Using sns.distplot, sns.kde, sns.boxplot, univariate analysis was on the demographical fields of the dataset

- Using sns.scatterplot, bivariate analysis of Annual Income and Spending score.

- Using sns.pairplot sns.heatmap, all the columns were used to show the relationship among the metrics.

  **Univariate**                                    

![](https://github.com/analyst-01/Customer-Segmentation/blob/main/Screenshot%20(72).png)  

**Bivariate**

![](https://github.com/analyst-01/Customer-Segmentation/blob/main/Screenshot%20(71).png)   

**Multivariate**
![](https://github.com/analyst-01/Customer-Segmentation/blob/main/Screenshot%20(69).png)  

You can get the complete project ![](https://github.com/analyst-01/Customer-Segmentation/blob/main/Untitled15.ipynb)

### Findings:

![](https://github.com/analyst-01/Customer-Segmentation/blob/main/Screenshot%20(66).png)

Based on the above cluster analysis, Cluster 2 has the highest income and highest spending score. The mean age of this cluster is 32.6 years.


## Conclusion and Recommendations
1. Target group would be Cluster 2 which has high Spending Score and high Income.
2. 59% of Cluster 0 shoppers are women. It is young cluster of average age of 25 years. Although they have low income, they follow Cluster 2 in Spending Score. Market popular items for the young people to them.



 
