# TMDB Movies Dataset Exploration
My submission for Udacity's second project investigating a TMDB movie data set of the data analyst nanodegree.

## Introduction
The Movie Database was selected for this project and it contains about 10,000 movies and information related to each movie such as the cast, genre, title, revenue. The steps taken in this project are inspecting the dataset, cleaning the dataset, analyzing the dataset, visualizing the dataset, and answering the following questions:

1. What properties are associated with popular movies?
2. Do movies with a higher budget receive better vote average?
3. Do movies with a lower budget receive lower revenue?

## Conclusions
In conclusion, movies with high popularity have a higher revenue and higher budget than movies with a low popularity, and movies with a high budget have a high revenue, but even though movies with a low budget have lower vote count they still have a vote average close to movies with a high budget. Note that the dataset was not explored to its fullest, maybe genres contribute to the popularity of a movie, or the cast contributes to the revenue of the movie.

## Limitations
The dataset used in this analysis had more than 50% rows with 0 values in three columns: popularity, revenue, and budget, which affected the accuracy of the graphs because when the bar charts were graphed the bars had a height of 0. Therefore, I had to drop those rows and treat them as missing data to get better visualization of the data.
