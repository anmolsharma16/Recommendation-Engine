# Recommendation-Engine

The objective of this recommendation system is to provide satisfactory movie recommendations to users while keeping the system user friendly i.e. by taking minimum input from users. It recommends the movies based on metadata of the movies and past user ratings. Metadata is used to find similar movies as per user preference and then find most relevant movies based on past user ratings. This recommender system produces recommendation by filtering movies in  stages which are as follows:

Content based filtering: 
-Filter movies based on similarity between Credits, Genres and Keyword story
-Used Cosine Similarly to detect similar movies.

Collaborative filtering:
-Movies are divided into clusters based on vote count and average votes. 
-Cluster with most average votes is recommended to user.
-Used Pearson's Correlation to detect similarity among movies.
