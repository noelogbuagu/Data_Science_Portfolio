# Predicting Bankruptcy in Poland

## Overview

This project aims to explore and analyze data collected by a team of Polish economists studying bankruptcy. The main objective of this project is to build a model that can predict whether a company will go bankrupt or not using machine learning algorithms such as Random Forest and Gradient Boosting. 
    
## The Data

The data used in this project was sourced from [here](https://archive.ics.uci.edu/ml/datasets/Taiwanese+Bankruptcy+Prediction#). The dataset was stored in JSON format and is compressed into a gzip file. The data consists of financial data from compaies in Poland. 


## Notebook

The notebook contains code that accomplished the following:
    
- Building a classification model to predict whether a business will go bankrupt or not, given its financial figures.
- Opening and working with compressed files using Python and Pandas.
- Addressing imbalanced data using resampling techniques.
- Working with ensemble classification algorithms like RandomForestClassifier and GradientBoostingClassifier.
- Evaluating a model using new classification metrics like precision and recall.
- Creating a Python module. 

## Final_Model.pkl

This is the saved final model at the end of the project. The model has been made available for use and any comments would be welcome.

## Predictor.py

This is a module that can be imported to test new data. It consists of 2 functions. A wrangle function and a make_prediction function. The former processes the data and the latter makes a prediction using final_model.pkl.

## DataDictionary.md

This the data dictionary for the data in the compressed JSON file.

