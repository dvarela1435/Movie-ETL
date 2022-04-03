# Movie-ETL

## Overview

Extracted data from 2 Resources. 
- Wikipedia-movies.json
- 2 CSV files from Kaggle Dataset pulled from MovieLens

Trasnformed the data into a usable format
  - cleaned up the data from wikipedia Movies
  - removed duplicate rows and some rows with NAN
  - Parse the data to make it more readable
  - Cleaned the Kaggle data

Merged the wikipedia movies data with Kaggle data
  - dropped columns that are redundant or duplcated.
  - Used the columns with more cleared information

Loaded the movied database created by merged files into PgAdmin

The following shows how many rows loaded into the database.

![movies_query.png](/resource/movies_query.png)




![ratings_query.png](/resource/ratings_query.png)

 
