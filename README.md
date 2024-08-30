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

  Univariate              Bivariate                  Multivariate
|----------------------|-------------------------|------------------------|
![](Screeshot(72).png) | ![](Screenshot(71).png) | ![](Screenshot(69).png)|

### Findings:

- Out of 276 adults, 110 bought bikes. Out of 614 young adults, 332 bought bikes, and only 39 out of 110 youths bought bikes.
- Adults and Youths with lower average incomes bought bikes while young adults with higher average incomes bought bikes.
- It was observed that there were fewer children in the families of bike buyers compared to non-buyers. 

### Interactive Dashboard 
![](dashboard.png)

You can interact with the dashboard [here](BikeProject.xlsx).

## Conclusion and Recommendations

From the dataset, many questions could still be answered. As for this analysis, here are my recommendations based on the findings:
1. GTE Bikes' marketing campaigns should  be targeted at adults with low incomes, and young adults with high incomes.
2. The chance of bike sales is high if low-income adults and high-income young adults with children are targeted in the campaign.
3. It is recommended that the cost of marketing to people between 30 years and below should not be too high because they averagely earn lower income compared to adults and young adults. Moreover, out of 110 youths surveyed, only about 35% of them bought bikes.


 Problem Statement: understand the Target Customers for the marketing team to plan a strategy
2. Context: Your boss wants you to identify the most important shopping groups based on income, age and the mall shopping score
3. He wants the number of ideal groups with a label for each
