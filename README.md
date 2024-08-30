# Custsomer-Segmentation
### Machine Learning Project

# GTE Rides- Bike Purchase Analysis

![](bikemen.jpg)
___
## Introduction
This project is out demonstrate some of my skills in Spreadsheet. Here, the use of "IF" function to create a new column, pivot table as well as interactive dashboard was highlighted.

**_Disclaimer_**: _The dataset and all the reports in this analysis do not represent any real company or entity. It's just for demonstration of Excel skills_.

## Problem Statement
The management of GTE Rides wanted to launch marketing campaigns for more sales. However, they noticed that age groups differed in the purchases of bikes. Therefore, they contacted a data analyst to use the already gathered data to find out how these age groups differed in purchasing bikes.
For the analysis, the problem statement is broken into specific evaluation questions:

1 How many adults, young adults, and youths bought bikes?

2 Across the age groups, how are the bike buyers and non-buyers compared in terms of  average income?

3 Who had more children between bike buyers and non-bike buyers?

## Skills/Concepts Demonstrated
Microsoft Excel was used for this analysis. The following skills were demonstrated;
- “IF” function to create a new column
- Pivot Tables and Charts
- Interactive Dashboard

## Getting the Data
The dataset was downloaded from YouTube tutorials. You can access the dataset [here](ProjectData.xlsx).
It has 13 columns and 999 rows, but only fields relevant to evaluation questions were utilized in this analysis. 

## Investigating the Data
The dataset was checked for relevance to the evaluation questions. Also, the use of the data did not breach any data-related laws.

## Preparing the Data/ Data Transformation
- “Age Group column” was created  from “Age” column using **=IF(L2>50, "Adult", IF(L2<=30,"Youth",IF(L2>=31,"Young Adult")))**
- 3 Pivot Tables were created from 4 columns: Age Group, Children, Income and Purchased Bike
- Slicers, bar chart and line chart were used to visualize the Pivot Tables and build dashboard.

## Analysis and Visualizations
Pivot Tables were created from 4 columns: Age Group, Children, Income and Purchased Bike to summarise the desired data.
To visualize the trends and patterns in the analysis, slicers, bar chart and line chart were used.

### Pivot Tables 

![](p_table.png)   | ![](p_table2.png)

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
