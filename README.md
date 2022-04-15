# Movies-ETL

## Project Overview

* Extract large data set from Kaggle
* Transform the data into a usable dataset
* Load DataFrames into PostgresSQL

## Project Cadence

* Created an ETL pipeline from raw data to a SQL database
* Extracted data from disparate sources using Python
* Cleaned and transformed data using Pandas
* Used regular expressions (Regex) to parse data and to transform text into numbers
* Loaded data with PostgreSQL and verify in PgAdmin

## Project Extracts

### Wikipedia Movies JSON file, starting with 193 Columns:

![image](https://user-images.githubusercontent.com/96931376/163490690-d55b9c8d-cdfa-4370-b9f6-8ce7ed7cfeee.png)

### Kaggle Movie Metadata, 24 columns: 

![image](https://user-images.githubusercontent.com/96931376/163490759-b6b63c21-1d4e-4fa2-95f7-363aa1840dc2.png)

### Kaggle Ratings data, 2602489 rows by 4 columns:

![image](https://user-images.githubusercontent.com/96931376/163490887-76c119a3-be01-4fdb-aa34-053f8f7e3b26.png)

## Project Transformation

### Wikipedia Movies transformed, 22 columns:

![image](https://user-images.githubusercontent.com/96931376/163490986-07aecfcd-b3cb-4b35-9783-aa479c37fe88.png)

### Wikipedia Movies, making the column names more succinct and uniform, 7033 rows of data:

![image](https://user-images.githubusercontent.com/96931376/163491136-7c362345-9403-4521-acd6-8d8d31597987.png)

### Wikipedia Movies merged with Kaggle Movies data, all column names and row counts, 6052 rows:

![image](https://user-images.githubusercontent.com/96931376/163491294-a95b7522-f8e8-41c9-8067-1e1fe566f90d.png)

### Merged Movies with Kaggle ratings, all of the column names and row counts, 6052 rows: 

![image](https://user-images.githubusercontent.com/96931376/163491377-39505a18-d343-4cf3-917e-1df75e06840f.png)

## Project Loading

### Creating the Movie Database

#### Sending the data to PostgresSQL

![image](https://user-images.githubusercontent.com/96931376/163497195-d1401794-d865-4b15-9656-b8cbd6cdcb12.png)

### Verifying the data in PgAdmin

#### Movies Query

![image](https://user-images.githubusercontent.com/96931376/163497223-7fcb4efe-55af-4a84-9bc9-21563b7094ce.png)

#### Ratings Query

![image](https://user-images.githubusercontent.com/96931376/163497239-a653f4f4-08d9-4b7b-8b50-f9cea4ece5bd.png)

## Project Summary

A JSON file and 2 Kaggle files were extracted, then transformed, and joined. A movies and ratings file were loaded into a database for the hack-a-thon event.
