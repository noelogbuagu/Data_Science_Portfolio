# Earthquake Damage in Okhaldhunga

## Overview

    This project involves building a classification model to predict building damage for the district of Okhaldhunga in Nepal based on the Nepal 2015 Earthquake.

    Focus Points:

    1. Creating and Quering an SQL database using SQLAlchemy.
    2. Building a logistic regression model classification.
    3. Building a decision tree model for classification.
    4. Comparing Model Performance.
    5. Developing an interactive dashboard based on the model.


## .zip file

    The compressed file contains all the .csv files used to create the tables for the database. The .csv files can be found [here](https://www.kaggle.com/code/ar89dsl/predicting-building-damage-from-earthquakes/input?select=ward_vdcmun_district_name_mapping.csv).


## data_wrangling.ipynb

    This notebook contains the code used to create the database and its tables. It also includes a preliminary exploration of the database. Before finally importing the desired query into a pandas dataframe.

## nepal_earthquake.db

    This is the database created in the data_wrangling notebook. It was created with sqlite3.

## notebook.ipynb

    This is the main notebbok for the project. It contains all the code used to prepare, import, explore and split the data.

    It also contains all the code used to build and evaluate the classification model. Also, the interactive dashboard for the model.