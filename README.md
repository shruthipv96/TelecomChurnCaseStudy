# Telecom Churn Case Study
---
## Case study assignment by IIIT Bangalore and Upgrad
---
> - Solving this assignment will give an idea of analysing the dataset and build a model to predict the telecom customers who might churn.
> - Developed as part of the Machine Learning Module required for Executive Post Graduate Program in Machine Learning and AI - IIIT,Bangalore.
---

## Table of Contents
* [General Information](#general-information)
* [Methodology](#methodology)
* [Repository contents](#repository-contents)
* [Conclusion](#conclusion)

## General Information
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to **predict which customers are at high risk of churn**. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.

In this competition, your goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage.

**Objective:**

The main goal of the case study is to build ML models to predict churn.
- It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
- It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.
- Recommend strategies to manage customer churn based on your observations.

## Methodology
1) Reading and Understanding the Data
2) Data manipulation and cleaning
3) Visualising the Data
4) Data Preparation
5) Feature Engineering
6) Building model

## Repository contents
| File | Description |
|:-----|:------------|
| Python notebook | It contains the complete detailed code along with necessary output to solve the problem. |
| README.md | This file briefs about the project. |
| data_dictionary.csv | Defintion of the attributes. |
| train.csv | It contains the training dataset. |
| test.csv | It contains the unseen test dataset. |
| sample.csv | It contains the format to submit the results obtained on unseen test dataset on Kaggle platform. |
| TelecomChurnCaseStudy_ShruthipVenkatesh_Submission.csv | It contains the prediction obtained on unseen test dataset. |
| Final_Score.png | Image which shows the score obtained on the unseen test data |

## Conclusion

From EDA and the feature importance analysis, we can derive the following important predictors for churn detection:
1) Local incoming calls minutes in month 8 
2) Local outgoing calls minutes in month 8
3) Last day recharge amount in month 8
4) Roaming outgoing calls
5) Roaming incoming calls
6) Average revenue per user
7) Maximum recharge amount
8) Total incoming call minutes
9) Total outgoing call minutes
10) Total recharge amount
11) STD incoming calls
12) STD Outgoing calls
13) Age on Network
14) Total number of recharges


**Strategies to manage customer churn:**

Below are few strategies to avoid people churn based on the above predictors,

| Observation | Action |
|:----------|:-------|
| Increase in incoming calls, decrease in outgoing calls | Customer might be facing issues to make calls due to poor network coverage, hence might churn. Connect with the customer to get a feedback of the service and resolve the queries  |
| Decrease in average revenue per user | Connect with the customer to get a feedback of the service to understand if they are happy about the service else provide promotion gifts |
| Increase in roaming services | Due to the high roaming rates, customers might churn when they have more roaming usage. Provide attractive offers on roaming rates |
| Decrease in total and maximum recharge amount and number of recharges | Due to high recharge amount, customers might churn. Provide attractive offers along with recharge like caller tune service, OTT subscription etc. |
| Increase in STD calls | Due to the high STD rates, customers might churn when they have more STD usage. Provide attractive offers for STD calls |
| New customers | New customers tend to churn, hence provide them with additional benefits |


## Contact
Created by [@shruthipv96] - feel free to contact me!
