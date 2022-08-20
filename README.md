# Data Moedling with Postgres

## Purpose 
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app. They'd like to create a Postgres database with tables designed to optimize queries on song play analysis.

This project to create a database schema and ETL pipeline for this analysis. We will test the database and ETL pipeline by running queries given to you by the analytics team from Sparkify and compare your results with their expected results.

## How t orun the Python scripts
'python create_tables.py' # to create the tables in the database 
'python etl.py' # to run the ETL pipeline 

## What files are includeed i the repository
**create_tables.py 
The python file to create the tables in the database 

***
**etl.py
The pytone file to run the ETL pipeline for the entire datasets 

***
**etl.ipynb
The notebook to develop ETL processes for each tabl

***
**test.ipynb
The notebook for testing to confirm the records were successfully inserted into each table

***
**sql_queries.py
The pythin file that contains all the sql queries, and is imported into the other python files and notebooks

## Data Schema

[Data Schema](schema.png)