# Movies-ETL by Kieran Persaud

## Overview of the Movies-ETL Challenge
Amazing Prime Video is a platform for streaming movies and tv shows. They have decided to hold a Hack-a-Thon, and Britta, a member of the Amazing Prime Team, has been tasked with preparing the datasets. Britta has to create an automated pipeline that takes movie and ratings data from Wikipedia and Kaggle, performs the appropriate transformations, and loads the data into existing tables. In the Challenge, I create one function that takes in three files —Wikipedia data, Kaggle metadata, and the MovieLens rating data— and perform the ETL process by adding the data to a PostgreSQL database.

## Resources
**Data Sources:** ```wikipedia-movies.json```, ```movies_metadata.csv``` (Kaggle Data), ```ratings.csv``` (MovieLens rating data)

**Software:** PostGreSQL 11, pgAdmin 4, Anaconda 4.10.1, Pandas, json, numpy, re, time and sqlalchemy Libraries, PythonData kernel; Jupyter Notebook

## Deliverables
1. The ```ETL_function_test.ipynb``` file
2. The ```ETL_clean_wiki_movies.ipynb``` file
3. The ```ETL_clean_kaggle_data.ipynb``` file
4. The ```ETL_create_database.ipynb``` file
5. The Resources folder with the ```wikipedia-movies.json```, ```movies_metadata.csv```, ```movies_query.png```, and ```ratings_query.png``` files.
