# TMDb Data Analysis
## by Chukwuemeka Nwokocha

## Dataset
This is a dataset containing information on 10,000 movies collected from The Movie Database(TMDb). The Columns (and their functions) in this dataset are listed below:

id:This acts as an index for the dataset

imdb_id: The Movie's identification on IMDB

popularity: This ranks the popularity of a movie

budget: The amount spent for the movie's production,(currency: USD)

revenue: Toatal amount of money generated from the movie (currency : USD)

original_title: Official title of the movie

cast: List of Actors/Actresses that take up a role in the movie

homepage: The website for details and more information on the movie

director: The name of the movie's director

tagline: A sentence used to get someone interested in the movie

keywords: Keywords related to the movie 

overview: Brief Synopsis on the movie

runtime: Full lenght of the movie (measured in minutes)

genres: The different categories that the movie can be fit into

production_companies: The companies that produced/worked on/were involved in the movie

release_date: The Month/Day/Year that the movie was released

vote_count: Number of times the movie has been voted/rated

vote_average: Average/Mean vote the movie has received

release_year: The year in which the movie was released

budget_adj: The total budget of the movie, adjusted to the inflation and currency value of 2010 (currency : USD)

revenue_adj: The total revenue generated from the movie, adjusted to the inflation and currency value of 2010 (currency : USD)

## Wrangling
1. Duplicates were dropped
2. 'homepage', 'tagline', 'overview', 'keywords', 'cast', 'production_companies', 'director', and 'imdb_id' were dropped because they were not essential to the question being asked
3. Missing columns in the genres column were filled with 'None'

## Summary
From the investigation i derived the following conclusions:
1. There is a prevalence of low popularity and the average popularity is 0.6464455549010583
2. The profit falls between -413912431.0(USD) and 2750136650.919176(USD)
3. The average movie is 102.07086324314375 minutes long
4. The Adventure genre has the been the most profitable over time
5. The average popularity of movies has increased over time
6. Movies with high vote averages genrally have high profits
7. The 70s has the biggest average movie profit
8. In the 60s, 70s and 80s; the vote averages did not determine the movies that were the most profitable and least profitable
Additional information will be beneficial because some movies did not have their genres listed

#### Limitations:
1. Missing data: A good number of genres and directors were missing
2. A lot of data in the director cells were gibberish
