# Movie Recommender using Map-Reduce

Acadamic project from class Big Data & Distributed Programming

Implement a basic movie recommender system with Map-Reduce Framework.

Target: Given a user’s userId and a movieId the user liked. Based on the given movieId and userId, recommend top 5 movies for the given user (userId).

For example, first find out the people/other users who have also liked the given movie (movieId). Once these users are known we can get the other movies they have rated and then aggregate the rating of the other movies given by these users and give the top 5 rated movies. 

For better recommendations, other data given in the csv files like genre, tags and so on can be used. 


# Data

A dataset where there are multiple csv files. These csv files have data corresponding to movie ratings.

For example, movies.csv has 
           [movieId (some unique number), movie title, genre]
and there are other files which provide the data for what user gave what ratings to which movies and so.

Downloaded from: http://files.grouplens.org/datasets/movielens/ml-latest-small.zip

# Tool used:
Jupyter Notebook

Hadoop Map-reduce Framework

Spark
