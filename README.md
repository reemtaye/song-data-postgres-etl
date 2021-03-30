# song-data-postgres-etl
 Creating ETL to process json song data and log files with python & postgres

## Description of project
The request is to create a star schema data model in postgres and load song data to the model via python ETL. Song data is stored in song and log json files in the data folder.   
  
**This repository contains**: 
1. etl.py: 
2. sql_queries.py:  
3. create_tables.py: 
4. etl.ipynb: a notebook used for initial prototyping and testing of the code  

**Dependencies:**
1. Postgres 
2. Python 3.9.2

## Data Model

## Creating Tables

## How to run the ETL
1. Create the tables by running:   
	python create_tables.py
2. db credentials must be passed as a system argument when you  
	'python etl.py <uid> <pw>'
## 

##