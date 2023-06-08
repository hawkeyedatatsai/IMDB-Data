
![image](https://github.com/hawkeyedatatsai/IMDB-Data/assets/126204698/b1e1c5f3-1f95-4586-927c-31fefffe7e68)

[image credit](https://www.themoviedb.org/about/logos-attribution)
# How to make a successful movie
 
## Business Problem
For this project, I produce a MySQL database on movies from a subset of IMDB's publicly available dataset. After that, I will use this database to analyze what makes a movie successful and provide recommendations to the stakeholder on how to make a successful movie.

## Data Dictionary
Refer to link [here](https://developer.imdb.com/non-commercial-datasets/)

## Part 1 - IMDB Data Processing
Download movie metadata from IMDB's public datasets.
The datasets can be obtained here .
Data dictionary for extracted datasets can be obtained here .
Filter the necessary information that meets the stakeholder's requirements
Files extracted include:
title.basics.tsv.gz
title.ratings.tsv.gz
title.akas.tsv.gz
title.crew.tsv.gz
title.principals.tsv.gz
name.basics.tsv.gz



## Part 2 - Extracting TMDB Data
Extract financial data and MPAA rating for the movies using TMDB's API.

## Part 3 - MySQL Database
Applying an E.T.L process from previously saved movie data. Specifically, I create a new MySQL database after preparing the data for a relational database. After that, I export database to a .sql file using MySQL Workbench.

## Part 4 - Hypothesis Testing


Please direct all communications to Henry Tsai at hawkeyedatatsai@gmail.com
