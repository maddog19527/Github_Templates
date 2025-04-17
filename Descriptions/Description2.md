# CS675_Project_2
Project #2 for CS675-Introduction to Data Science

## Project Overview

-I was asked to clean and prepare a dataset of telemarketing information provided by UC Irvine's Machine Learning Repository, with the ultimate goal of predicting a customer's likelihood of subscribing to a Term Deposit (purchasing a product sold over the phone). I was then asked to apply various Classification Models to the data, determine efficacy using metrics, and hypertune the models to improve performance.

## Contents

bank-additional-full.csv - initial dataset

clean.csv - one-hot encoded dataset, used for 

labeled.csv - label-encoded dataset, used for

Data_Cleaning.ipynb - EDA, Data Cleaning and Feature Importance information

Model_Performance.ipynb - Initial model fitting and performance evaluation, hypertuning 

## Dataset information

Source: [Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)

Features: 

Target: Yes or No to subscription

## Data Cleaning

-Handled values labeled 'unknown'

-Normalized Data

-Reduced Dimensionality of features demonstrating signficiant multicollinearity

-Determined prescriptive features

## Model Performance

-Organized data into sets with one-hot encoded features, and sets with label-encoded features, in order to optimize their performance.


Models Used:

-Logistic Regression

-Decision Tree

-Random Forest

-K-Nearest Neighbors

-XGBoost

-Naive Bayes


Evaluation Metrics:

-Precision

-Recall

-Accuracy

-F1 Score

## Metrics

Best Performing Model:



Libraries used:

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)](#)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](#)
[![plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)](#)
