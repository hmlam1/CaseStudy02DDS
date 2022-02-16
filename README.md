# DDS-Case-Study-2: Company Culture and Employee Attrition 

## Introduction to the Project
Identify top three factors that contribute to job turnover and discern job role specific trends as well as relevant observations backed by statistical analysis. Utilize binary logistic regression to obtain AIC of the model containing the aforementioned top factors in addition to Naïve Bayes and linear regression to deploy prediction models for attrition and monthly salary.

## Executive Summary
Employee retention is a crucial cost-effective measure for businesses in addition to a host of nonfiscal benefits such as morale, productivity, and cultural impact. My partner and I identified overtime, years in current role, and job involvement as the top drivers of attrition (AIC 665, 150 points lower than other models ran). Of the 71% employees who do not work overtime, 90% stay. However, of the 29% employees who do work overtime, 32% leave. It appears companies that mandate overtime could potentially lose one third of their workforce. Furthermore, 22% employees leave the company within their first 3 years if they retained the same role in that duration. We noted a negative correlation between attrition rate and job involvement. Employees who self-rate their work as *very uninvolved* have a 47% attrition rate and just *uninvolved* goes down to 18%. Conversely, 87% of employees who feel their work is *involved* stay and significantly goes up to 91% when their work is *very involved*. We also observed a negative correlation between salary and attrition rate. This trend intuitively made sense to us but is there a confounding factor? We looked at job satisfaction level for each job role, particularly the highest self-rated level of dissatisfaction, and discovered a positive correlation between salary and job dissatisfaction. Thus salary is the biggest driver of attrition among job roles, despite their satisfaction of the job itself. Lastly, we conducted Naïve Bayes to predict attrition rate and obtained 86% accuracy, 61% sensitivity, 91% specificity, and .04 p-value.. We predicted monthly income using linear regression using total working years, job level, and job role. The model resulted in an adjusted R^2 of 95% and 1007 RMSE. Added variable plots were shown to illustrate the predictors' strong linear relationship with the response and each other. Both models were validated using a split train/test split.

## Contents
1. RMD with supporting codes and analysis
2. Knitted HTML of RMD
3. Datasets: Raw data, attrition test, salary test, attrition prediction, salary prediction
4. Presentation slides
5. [Link](https://smu.zoom.us/rec/play/g8rvMppOoDlz6wd68edFJ3d3KKcOpzB2oUVZTa65NleSaWX0Bg17VPd_GoRrGq1zKjWo6wvvh2_GvjGS.mSQlFoOsMm_04Lto) to recorded presentation
6. [Link](https://lam-hien.github.io/) to GitHub website
