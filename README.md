# Movies-ETL
Module 8 - ETL - Extract, Transform, and Load

For this challenge, we will continue to work with Amazing Prime.    This project will include creating an automated pipeline that will take in new data, perform transformationas and loads that data into a table.    We will utilize three files:   Wikipedia data, Kaggle metadata, and MovieLens.    This information will then be added to a SQL database.

# Deliverable 1
For this deliverable the following was created:

- ETL function that reads in the files
- Convert Wikipedia JSON file to a Pandas DataFrame
- Use functions to do the following:
    - Convert Kaggle Metadata file to a Pandas DataFrame
    - Convert the MovieLens rating data to Pandas DataFrame

# Deliverable 2
For this deliverable a wiki_movies_df DataFrame is created by using try-except block, list comprehension, regular expressions.    In addition the following columns are created:   box office, budget, release date, and running time.   At the end a new DataFrame is created.

# Deliverable 3
The extraction and transformation of the Kaggle metadata using the ETL function does the following: cleaning of the Kaggle metadata, merging of the two dataframes. After merge the duplicate columns are dropped, columns renamed, counts are cleaned, and empty values are filled with zero.    

# Deliverable 4
In this deliverable we replace the current data in the SQL database based on our new DataFrame.   In addition, elapsed time to add the data to the database will be displayed.
