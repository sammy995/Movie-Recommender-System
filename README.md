## Movie Recommender System
#### A function is defined to recommend similar movies based on a given movie title.
## Overview: 

This project uses two CSV files of Movies and Credits and merges them into one DataFrame using the movie titles as a key. 
The important columns selected for analysis are genre, ID, keywords, title, overview, cast, and crew. 
The code performs feature engineering by cleaning and transforming these columns. 
The Data is pre-processed, by removing null values and duplicates. 
The text data is further processed by converting the strings into lists, removing stop words, stemming, and then vectorizing the tags. 
Finally, the cosine similarity between the movies is calculated and stored in a pickle file along with the final DataFrame and dictionary of movies. 
A function is defined to recommend similar movies based on a given movie title.


Used: TMDB 5000 movies dataset : tmdb_5000_credits.csv, tmdb_5000_movies.csv

Used: Stemming, stopwords removal, Vectorization of tags, bagofwords 
