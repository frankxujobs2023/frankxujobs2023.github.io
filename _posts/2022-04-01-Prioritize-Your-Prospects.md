---
title: "Prioritize Your Prospects"
mathjax: true
layout: post
categories: media
---

Suppose you are a manufacturer, you plan to sell your products to retail stores, how would you decide which retail stores to connect first given the huge amount of retail stores in US?
> A good solution is utilizing machine learning techniques to build up a prioritization model and generate a score for each retail store.
> The end goal of this solution is to maximize your potential revenue/profits by saling your products to the best retail stores.


To generate a **prioritization score** for each retail store, you need following things：
## 1. Retail store information and data 
[Dun & Bradstreet (D&B)](https://www.dnb.com/) data, [Dashmote](https://dashmote.com/) data, and Google public data.
> **Dun & Bradstreet** is a global company that provides business intelligence products to clients through its database and analytics software. The products are used in improving business profits, marketing, and risk management.
>
> **Dashmote** is a leading data democratization platform for food, beverage, manufacture, sales & marketing.

## 2. Feasible model to use - Classification
> **Classification**: The score is the likelihood of being an attractive prospect/customer/retail store.
> 
> **Training data**: Two types of retail stores - Customers and Non-customers.
> 
> **Customers**: Retail stores who have done business with you.
> 
> **Non-Customers**: Those never done business with you and existed for a long time.
> 
> **Testing data**: Those new retail stores. 
> 
> **Output**: You don't know weather the new retail stores would do business with you, but the prioritization model will calculate the likelihood.
> 
> **Strategy**: You just need to connect with those new retail stores with high score.  

### 2.1 The most influential features in an exmaple are as follows:

![prospects](/assets/prospects2.JPG1)

### 2.2 The F1 score for classifiation model in an example is **95.4%**.
> You can attempt various classifiers like Xgboost, Randomforests, Catboost, Adboost, etc and ensemble them in a stacked structure.

## 3.  Feasible model to use - Regression
> **Regression**: The score is the predicted transaction amount (dollor) or prodcut volume.
>
> **Output**: The prioritization model will anticipate the transaction amount (dollor) or prodcut volume of a new retail store. 
> 
> **Strategy**: You just need to connect with those new retail stores with high predicted transaction amount (dollor) or prodcut volume. 
> 
> **Advantage**: The advantage of regression is that it will prvide the transaction and revenue forecasting.

### 3.1 The most influential features in an exmaple are as follows:

![prospects](/assets/prospects3.JPG1)

### 3.2 The MAPE score for Regression model in an example is **5%**.
> You can use various metrics to measure the regression accuracy like R-square, MAPE, RMSE, etc.

## 4. Ultimate Conlusion
> You should run both classification models and regression models and prioritize those new retail stores with high likelihood of being attrctive customers from **classification** and high transaction or products volume predicted by **regression**.
