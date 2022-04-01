---
title: House  price prediction
date: 2022-03-21T11:11:33.776Z
summary: we use a  dataset  of KC county form Kaggle to predict the house price
  by building different kinds of  model and find the best fit model to use.
draft: false
featured: false
authors:
  - Haocheng Liao, KAIQI PENG, Wenting Yang, Danlei Wang, Yucong Chen
tags:
  - R
  - Modeling
  - Economic
categories:
  - Economic
image:
  filename: featured3
  focal_point: Smart
  preview_only: false
---
<!--StartFragment-->

Introduction

We found that there are many outliers, high leverage and influential observations that are worth removing in the data. Most of the variables are statistically significant while we fail to estimate sqft_above due to its singularities. By performing Mallows Cp and Boruta algorithm, we found that there are no variables worth removing. We test for multicollinearity using VIF, and realize that we have to remove sqft_lving. Also, it is vital to improve the model based on the result by performing the RESET test. Next, we detect heteroskedasticity for this dataset. We select the lowest AIC and BIC for model comparison. As we divide our data into the traditional training and testing samples, we are able to compare different predicted values in different cases. results of BIC, the “model_without_outliers” also performs as the best model, as it has the smallest number of the BIC value and Delta-BICc among all. This model is much better than all the others, as it carries 100% of the cumulative model weight and has the lowest BIC score. The next best-fit model carries only 0% of the cumulative model weights. Based on this comparison, we would choose the “new_reg_mod1” to use in our data analysis.

<!--EndFragment-->
