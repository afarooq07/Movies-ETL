# Movies-ETL

## Scope  
In this challenge, the task is to performance movie analysis using functions to load Wikipedia data, Kaggle metadata, and the MovieLens rating data, perform the ETL analysis addand finally addi the data to a PostgreSQL database.

<br />

The challenge consists of three deliverables (as described in module 8 challenge):
- Deliverable 1: Write an ETL Function to Read Three Data Files
- Deliverable 2: Extract and Transform the Wikipedia Data
- Deliverable 3: Extract and Transform the Kaggle data
- Deliverable 4: Create the Movie Database

<br />

## Resources
- **Data Source:** The following file are avialable under Resources folder:
  -  movies_metadata.csv (please note that this file was too large to upload to Github)
  -  wikipedia-movies.json
  -  ratings.csv (please note that this file was too large to upload to Github, I kept getting an error. Hence I was unable to make it available under Resources folder)
- **Code file:**
  -  ETL_clean_wiki_movies.ipynb
  -  ETL_clean_kaggle_data.ipynb
  -  ETL_create_database.ipynb
  -  ETL_function_test.ipynb
- **Images:**: these are available in the same folder as the code files
  -  movies_query.png
  -  ratings_query.png

<br />

## Notes/Issues:
- For deliverable 2, I cleaned and updated movies_df dataframe using the same column name rather than creating new ones for the following:
  - Budge
  - Box office
  - Release date
  - Running time
- I was unable to upload the following files to the repor because of file size was over the limit error:
  - movies_metadata.csv
  - ratings.csv 
- Count of movies table in postgres shows 6051 for me (as shown in movies_query.png) instead of 6052 mentioned in the challenge, I was not able to investigate the difference of 1 record due to lack of time
- Git pull overwrote all the work and I lost the code files. Ihad to restore the files and upload via github instead of git bash
