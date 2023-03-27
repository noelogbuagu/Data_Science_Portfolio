# File Descriptions

## get_data

    A webscraper built using Selenium and Pandas in python. This scraper performs the following tasks:

    - navigates to the toronto real estate market page on [REALTOR.ca](https://www.realtor.ca/).
    - filters results for only houses.
    - collects specific information about each listing on the page.
    - handles pagination automatically to prevent manual intervention.
    - creates a dataframe to store listing information

## get_data_singular
    
    This scraper does everything in the original scraper but is not as robust.
    Manual intervention is needed to go from page to page because I could afford services that resolve captchas.

## notebook

    A jupyter notebok of all the code used to process and analyze the data. 
    It also contains all the code used to build, train and evaluate the model for predicting house prices.

## listings*

    All .CSV files that contain data from the webscraper.
    This data is what is used in notebook.ipynb