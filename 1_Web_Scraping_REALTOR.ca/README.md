# File Descriptions

## get_data

    A webscraper built using Selenium and Pandas in python. This scraper performs the following tasks:

    1. navigates to the toronto real estate market page on [REALTOR.ca](https://www.realtor.ca/).
    2. filters results for only houses.
    3. collects specific information about each listing on the page.
    4. handles pagination automatically to prevent manual intervention.
    5. creates a dataframe to store listing information

## get_data_singular
    
    This scraper does everything in the original scraper but is not as robust.
    Manual intervention is needed to go from page to page because I could afford services that resolve captchas.