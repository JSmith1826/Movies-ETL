# Extract, Tranform, Load - Movie Data
## Overview
The purpose of this project was to create a database that holds information about popular movies released in the United States. There were two data sorces that were utilized to create the final dataset.
- Information scraped from Wikipedia in the form of a json file
- "The Movie Dataset" compiled by Kaggle.com

The data from Kaggle was provided as a set of csv files containing information about over 45,000 movies and 26 million ratings for those films from 270,000 unique users. The Kaggle data was well curated but the information from Wikipedia needed to be cleaned up significantly. Once the data was satisfactorily uniform the datasets were merged using the Internet Movie Database ID number as the key. After the merge redundant data was dropped and the new set was loaded into a SQL server using SQLAlchemy.

The data was cleaned using Python code and merged using the pandas module.