# Movies-ETL
## Project Overview
Within the scope of the Amazing Prime Hackathon, this project will create an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data. It then performs the appropriate transformations and loads the data into an existing PostgreSQL database.
For this analysis, we used the following breakdown:

1. Write an ETL function to read three data files,
2. Extract and transform the Wikipedia data,
3. Extract and transform the Kaggle and rating data,
4. Load the data to a PostgreSQL Movie Database.
### ETL_function_test.ipynb
1. Data is extracted from the website in JSON and CSV formats.
2. Data is transformed into Pandas data frames.
3. JSON file requires extra step – loading file first and then transforming into data frame.
### ETL_clean_wiki_movies.ipynb


1. In the function extract_transform_load the transformation process of wiki movies data 

### ETL_clean_kaggle_data.ipynb
Function extract_transform_load gets new tasks for cleaning Kaggle data .
### ETL_create_database.ipynb
The function in its final step connects to the database by sqlalchemy library and to_sql method.
Complete ETL process can be executed with a single function extract_transform_load call.
