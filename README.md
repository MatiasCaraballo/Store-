# Scrapes using Beautiful Soup and Requests

Scrapes the fake api Fake Store Api and transforms the data from the HTML to a json.

# Creates an dataframe for the products

Use the data from the products in the json.

# Creates an dataframe for the ratings

Use the data from the ratings in the json.


# Creates an dataframe for the categories

Use the data from the categories in the json


# Normalize the products dataframe

Removes the category and ratings columns. Creates a foreing key for each deleted column.

#Creates a database in MySql 

The user inputs their MySQL account data. Then the code creates an database named 'store' using the dataframes as tables
