# Movies-ETL

## Overview
In this project we are going to perfom the ETL (extract, transform and load) process in 3 differente databases, so we can organize the data and create a new and better databases, dropping wrong and duplicate data and keeping only the useful information. We are going to use Jupyter notebook, Pandas, SQL and PgAdmin to handle the Wikipedia, Kaggle and MovieLens data.

## Summary
* In ETL_function_test.ipynb file we create a function to read three data files and creates three separate DataFrames.
* In ETL_clean_wiki_movies.ipynb we transformed the Wikipedia data using the ETL process and merged it with the Kaggle metadata in the movies_df.
* In ETL_clean_kaggle_data.ipynb we merged the MovieLens rating data with the movies_df DataFrame to create a new DataFrame that includes the ratings, using ETl to avoid duplicate columns.
* ETL_create_database.ipynb we send our DataFrames to SQL databases

