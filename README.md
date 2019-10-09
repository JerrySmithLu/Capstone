# Customer Segmentation Report - Arvato Financial Solutions
[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

## Table of Contents:
1. [Project Motivation](#projectmotivation)
2. [Project Summary](#projectsummary)
3. [Process Dataset](#files)
4. [Future Improvement](#futureimprovement)
5. [Guide](#Guide)

## Project Motivation:
This capstone project with challenge is provided by Arvato Financial Solutions for the Udacity Data Science Nanodegree Program. Arvato provides several datasets which contain customer demographics data and mail-order customer info. But in this project, I try to solve 2 business questions:
1. How to help Arvato‘s customer which is a mail-order company to acquire new potential customers more efficiently?
2. How to make customer dataset more consistent and effective for data analysis?

To solve these business issues, I provided 2 solutions:  
1. For question2, we have to clean up customer features and its data by Unsupervised learning model, and check the relationship between the demographics of the company’s existing customers and the general population of Germany. There are several major steps: remove unwanted observasions, fix structural errors, filter unwanted outliers, handle missing categories, handle missing data, handle data transformation etc. Finally, it can make our data more effective and consistent. 
2. For question1, after cleaning up all customer features and data transformation, I create a supervised learning model to analyze customer behaviors and predict potential customers. In the  

## Project Summary:
This capstone project is provided by Arvato Financial Solutions for the Udacity Data Science Nanodegree Program. 

This capstone project contains three parts:

1. **Customer Segmentation Report**
This customer demographics are analyzed by unsupervised learning techniques to describe the relationship between the demographics of the company's existing customers and the general population of Germany and compare parts of the general population that are more likely to be part of the mail-order company's main customer base. 

2. **Supervised Learning Model** 
Based on the customer demographics analysis, we build a supervised learning model that predicts whether or not it will be worth it to include that person in the campaign.

3. **Kaggle Competition**
we test the supervised learning model in competition through Kaggle to make predictions on the campaign data and see how it measures up to the other solutions.

## Dataset Files: 

Arvato provides five data files for this project. The last file was re-defined by the user. As part of the terms and conditions of Arvato, the files cannot be shared in this repository. However, they can be described below.

1. `Udacity_AZDIAS_052018.csv` 
Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).

2. `Udacity_CUSTOMERS_052018.csv` 
Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).

3. `Udacity_MAILOUT_052018_TRAIN.csv` 
Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).

4. `Udacity_MAILOUT_052018_TEST.csv`
Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

5. `DIAS Attributes - Values 2017.xlsx` 
It contains a summary of properties and its category defintion for each feature created.

6. `DIAS Attributes - Values 2017_New.csv` 
It contains the category defintion for each feature created and its categorization types(numeric, ordinal, category......).
 
## Future Improvement
In supervised learning model, now I used sklearn pipeline and GradientBoostingRegressor model to train and test customer dataset. But its accuracy of prediction is not good and it can reach about 80%. I think I can use deep learning on customer dataset. We know the knowledges of Deep Learning is better and it’s been applied to some fields(NLP, Image Recognition etc.). For the data transformation, we can use median or gaussian function to replace missing data.  
## Guides

1. The Jupyter notebook "Arvato Project Workbook.ipynb" is for exploration. An HTML file has been provided as another means to check the notebok.

3. the file `competition_submission.csv` which is created in "Arvato Project Workbook.ipynb" is for to Kaggle competition. [competition](https://www.kaggle.com/c/udacity-arvato-identify-customers).
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

