<a id='intro'></a>
## Introduction

### Dataset Description 
This data from Kaggle and you can download it from <a href="https://www.kaggle.com/deepak525/investigate-tmdb-movie-">Kaggle dataset</a>

This dataset contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.
we have here ['id', 'imdb_id', 'popularity', 'budget', 'revenue', 'original_title','cast', 'homepage', 'director', 'tagline', 'keywords', 'overview','runtime', 'genres', 'production_companies', 'release_date','vote_count', 'vote_average', 'release_year', 'budget_adj','revenue_adj']

I think we don't need ['homepage','tagline','overview','imdb_id','keywords','budget_adj','revenue_adj','production_companies','popularity','cast','vote_count']

we'll use ['budget', 'revenue'] to get the profit and cost of movies, the financial part, ['genres'] column to determine which one is the most common...etc, column ['release_date'] to deal with time and year, column ['vote_average'] to determine which had high, and low vote.

### Question(s) for Analysis

    Q1: Is there a correlation between runtime and average vote?

    Q2: What is the most common genre? and in the top 100?

    Q3: Which genre costs the much? and which doesn't?

    Q4: Is there a correlation between cost and revenue in the top 100?

    Q5: What is the lowest budget movie in every year for the past 10 years?

    Q6: What is the highest profit movie on the list?

