# Movie-Recommendation-System
The objective of this recommendation system is to provide satisfactory movie recommendations to users while keeping the system user friendly i.e. by taking minimum input from users. It recommends the movies based on metadata of the movies and past user ratings. Metadata is used to find similar movies as per user preference and then find most relevant movies based on past user ratings.
Movies recommendation list is based on similarity between the movie given by user to other movies and this list is further divided into clusters and produces recommendation by filtering movies in 3 stages which are as follows:
1. **Content based filtering:**
Filter movies based on similarity between Credits, Genres and Keywords
2. **Content based filtering:**
Filter movies based on similarity between movies from previous list and movies in user's history
3. **Collaborative filtering:**
Movies are divided into clusters based on vote count and average votes. Cluster with most average votes is recommended to user.

[PROJECT DEMO](https://drive.google.com/file/d/1BiajPPiXkJAKvxRbUaElQ2E8wMjwXdAE/view?usp=sharing)

## Data Description

This dataset contain 26 million ratings from 270,000 users for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages.
* [Dataset link](https://drive.google.com/open?id=1bZhqdGm27sEcRo4cY15Chk65Oj5ROWRk)
* [Dataset Source](https://grouplens.org/datasets/movielens/)

## Technologies Used

### Web Technologies
* Html
* Css
* JavaScript
* Flask

### Machine Learning Library:
* pandas
* numpy
* difflib
* AST
* scikit-learn

### Requirements:
* Python 3.6
