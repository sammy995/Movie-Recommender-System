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

## ------------------------------------------------------------------------------------------------------------------
The app.py file contains code for a movie recommendation system built using the Streamlit framework. The system recommends similar movies based on a user-selected movie. It uses a pre-trained model to compute the similarity between movies and fetches movie posters using the TMDB API. Users can select a movie from a dropdown list and click on a "Recommend" button to get five recommended movies with their posters displayed in a grid layout. The code uses Pandas library to load movie data and pickle to load pre-trained models. The app provides an easy-to-use interface for users to discover new movies that they might be interested in watching based on their preferences.


Used: TMDB 5000 movies dataset : tmdb_5000_credits.csv, tmdb_5000_movies.csv

Used: Stemming, stopwords removal, Vectorization of tags, bagofwords 
