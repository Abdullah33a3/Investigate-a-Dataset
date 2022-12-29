# Investigate-a-Dataset

## Introduction

This project is about analyzing a database that contains data of more than 10,000 movies. The database is called The Movie Database (TMDb). The columns, or features, in this database are described as follows:

* id : A unique identifier for each movie in the database.
* imdb_id : A unique identifier for the movie on Internet Movie Database (IMDb), the world's most popular and authoritative source for movie, TV and celebrity content.
* popularity : A numerical index representing the popularity of the movie.
* budget : The amount of money spent on the movie.
* revenue : The total revenue of the movie.
* original_title : The title of the movie before translation or adaptation.
* cast : The group of actors who made up the movie.
* homepage : A link to the homepage for the movie website.
* director : The movie's director.
* tagline : The tagline of the movie.
* keywords : Keywords that are associated with the movie.
* overview : A brief description of the movie.
* runtime : Total running time of the movie in minutes.
* genres : Category of the movie (Action, Drama, .. etc).
* production_companies : The companies that produced the movie.
* release_date : The date on which the movie was released to the public.
* vote_count : Number of voters.
* vote_average : The average rating of the movie.
* release_year : The year on which the movie was released.
* budget_adj : Movie's budget in terms of US dollar value in 2010.
* revenue_adj : Movie's revenue in terms of US dollar value in 2010.

This database can be explored in many ways. There are many insights that can be derived from it. However, in this proejct, the exploration will be constrained around the following research questions:

- RQ1: Which year had the highest movie releases?
- RQ2: In which month were most movie releases of all time?
- RQ3: What are the most popular movie genres of all time?
- RQ4: What are the 10 most profitable movies of all time?
- RQ5: How do budget and runtime affect the popularity of the movie?
- RQ6: How does the popularity of the movie affect revenue, profit, vote count and average vote?

## Results
From our investigation, we can conclude that:

* The number of movie releases increases over the years. Year 2013 has the highest number of movie releases.
* September and Octorber have the highest number of movie releases among all months of all time.
* Drama and Comedy are the most popular genres.
* Avatar, Start Wars and Titanic are the most profitable movies.
* There is a positive correlation between the budget invested on the movie and the popularity of the movie. Movies with higher budget tend to be more popular.
* Runtime has an impact on the popularity of the movie. Most popular movies have runtime between 110 and 140 minutes (around 2 hours). People do not prefer to watch long movies and very short movies as per the dataset.
* More popular movies tend to earn more profit.
* More popular movies tend to have more number of voters.
* There is a weak correlation between popularity and average vote. If the movie is popular, that does not necessarily mean that it is highly rated.
