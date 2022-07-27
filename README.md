# Movies-ETL

## Project Overview

Within the scope of the Amazing Prime Hackathon, this project will create an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data. It then performs the appropriate transformations and loads the data into an existing PostgreSQL database.
For this analysis, we used the following breakdown:

1. Write an ETL function to read three data files,
2. Extract and transform the Wikipedia data,
3. Extract and transform the Kaggle and rating data,
4. Load the data to a PostgreSQL Movie Database.

## Purpose

The purpose of the project is to prepare the movie datasets for use in the hackathon by using the ETL (Extract, Transform, Load) process. The data is stored in the database after being cleaned and proccessed for use.

## Results

In this project three datasets were collected:

1. wikipidea-movies.json
2. movies_metadata.csv
3. ratings.csv

The datasets were all cleaned programatically in jupyter notebooks using pandas and other related libraries. Once they were cleaned, and relevant data was kept, they were merged together to form a single movie dataframe. The dataframe was then uploaded to our database as a table along with the processed ratings dataframe. The tables are ready to be used for the hackathon and using SQL we can query the database to extract information from the tables.

## Summary

Data cleaning and processing was the main objective of the project. Messy data was collected from different sources and turned into usable and relevant data through the ETL process mentioned before. The data is now ready to be extracted from the database and used in the hackathon.# Movies-ETL
