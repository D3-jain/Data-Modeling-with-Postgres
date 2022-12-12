# Data Modeling with Postgres

In this project, a startup named Sparkify wants a Postgres database created for songs and user data. We are retrieving data in JSON format from data already provided. The data are inserted into the database schema using an ETL script.

### Project Repository
The repository consists of the following files and folders:
1. Data Folder: This folder consist of dataset provided. It has datasets withing sub-folder named song_data and log_data, song_data folder consist of JSON files for song data and log_data consist of JSON files of user activity.
2. create_tables.py: This file is used to drop and create tables for performing insert actions.
3. etl.ipynb: ETL python notebook is used to test functions and code used in ETL python script.
4. etl.py: An ETL python script to perform an automated insertion of data from datasets into the database.
5. sql_queries.py: Python script that contains all required SQL queries to drop, create, insert and select tables.
6. test.ipynb: A test python notebook used to verify functions, scripts or queries developed in other files. It also contains some sanity tests to check the quality and naming of tables in sql_queries.py

### Dataset:
The dataset contains following tables:
1. songplay_table: This is a fact table which consist of data about the played song.
2. user_table: A dimension table that contains list of users.
3. song_table: A dimension table that contains list of songs.
4. artist_table: A dimension table that contains artist information.
5. time_table: A dimension table that contains timestamp details further split into units.

### Project execution
In order to execute the project, open-up a terminal in your project folder and run the following two commands:
1. python create_table.py
2. python etl.py
