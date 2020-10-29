# Kaggle Insurance Challenge Using Various Classification Models
 
#### by Shawn Oppermann

## Repository Contents

Report: <a href=https://github.com/sopper1/Kaggle-Insurance-Challenge-Using-Various-Classification-Models/blob/master/notebooks/report.ipynb>Technical Notebook </a>

## README Contents

[Overview](https://github.com/sopper1/Kaggle-Insurance-Challenge-Using-Various-Classification-Models#overview)

[Data](https://github.com/sopper1/Kaggle-Insurance-Challenge-Using-Various-Classification-Models#data)

[Motivation and Background](https://github.com/sopper1/Kaggle-Insurance-Challenge-Using-Various-Classification-Models#motivation-and-background)

[Future Work](https://github.com/sopper1/Kaggle-Insurance-Challenge-Using-Various-Classification-Models#future-work)

[Project Specifications](https://github.com/sopper1/Kaggle-Insurance-Challenge-Using-Various-Classification-Models#project-specifications)

## Overview

A Kaggle client that provides health insurance is interested in providing vehicle insurance to the same customers. To this end, the client wants a model to predict whether a health insurance customer would be interested such an offer. This projects briefly goes through the process of training two classification models, Logistic Regression and Random Forest Sampling.

## Motivation and Background

In class, I have recently learned about Logistic Regression Models. To my surprise, abstraction makes it very easy to apply almost any model to an applicable dataset. For this reason, I decided to compare the performance of both Logistic Regression Models and a model I'm not familiar with, Random Forest Sampling. The hope is that I can understand the pros and cons of using each of these models in a real-world problem.

## Data

The data as available for download at https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction#.

### Data Contents
   * train.csv - dataset that includes whether the customer was interested in vehicle insurance
   * test.csv - dataset for predicting the customer's interest
   * sample_submission.csv - a sample csv that would be submitted to the competition on Kaggle
   
This project will only be concerned with train.csv, which contains 381109 entries. Kaggle describes the data as follows:

![train.png](https://github.com/sopper1/Kaggle-Health-Insurance-Cross-Sell-Prediction/blob/master/images/train_desc.png)

## Future Work

In the future, I would like to do more research on Random Forest modeling and test this same data set with more types of classification models. I would also like to look further into sklearn's hyper parameters for each model.

## Project Specifications

### Publishing
    - Contributor: Shawn Oppermann
    - Start date: 10/27/20

### Usage
    - Language: Python
    - Tools/IDE: Anaconda, Jupyter Notebook
    - Libraries: pandas, numpy, matplotlib, sklearn, seaborn

### Data Source
    - Kaggle "Kaggle Health Insurance Cross Sell Prediction" dataset posted by Anmol Kumar
    https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction#