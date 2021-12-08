# dcs-phase1-project

README.md
A file called README.md at the root of the repository directory, written in Markdown; this is what is rendered when someone visits the link to your repository in the browser
This file contains these sections:
Overview
Business Understanding
Include stakeholder and key business questions
Data Understanding and Analysis
Source of data
Description of data
Three visualizations (the same visualizations presented in the slides and notebook)
Conclusion
Summary of conclusions including three relevant findings



<img src="Images/logo.png">

# <center>Microsoft Movie Studio</center>

# Overview
***
This project's goal is to explore movie analytics to provide actionable insights for Microsoft's new Movie Studio. My goal for this project was to help aid Microsoft in creating a baseline structure which will assist them in deciding what factors are important to take into consideration when producing films! 

I carried out exploratory analyses on datasets containing information about movie titles, ratings, genres, gross income, and directors to create a selection of business models for Microsoft's consideration.

My analyses show that movies under the genres Action, Family, and Mystery, on average, have a higher gross box-office income. But, as far as movie ratings go, Drama and Non-Fiction movies tend to, on average, get higher ratings. This tells us that while Action/Family/Mystery movies generally make more money in the box-office, they are not perceived as well by critics.

My analyses also explores movie ratings (G, PG, PG-13, R, NR) and the distribution of total movies made through each category, as well as how well, on average, they are perceived by critics. This data shows that R rated movies are made at a much higher rate and on average are rated 'Fresh' on Rotten Tomatoes more often than any other movie rating

As a bonus, I have explored the Top 10 Movie Directors by the number of films they have directed and analyzed their average movie rating. This has shown that Stephen Spielberg has both made the highest number of movies, as well as has the highest average ratings. This tells us that he would be a excellent director to partner with.

# Business Problem
***
Questions I will be Analyzing:
* What is the distribution of movie ratings and number of movies produced based on genres?
* What movie genre, on average, makes the most amount of money in the box office?
* What is the distribution for number of movies made by movie rating (G, PG, PG-13, R, or NR), and what percent of them get good ratings? 

* Who would an ideal director be to get involved in a movie project?
***

The answers to these questions will allow Microsoft to decide what genres they should focus on as far as how well its perceived by critics and how much money it makes in the box office. It would also provide insight into what movie ratings would follow how the movie industry is trending.

# Data Understanding
---
The data used in this project was gathered from IMDB, Rotten Tomatoes, and Box Office Mojo

* ```imdb_title_basics```: IMDB data consisting of title ID, primary title name, original title name (if fireign or known by something else), start year, runtime minutes, and a string of genres separated by a comma
* ```imdb_title_ratings```: IMDB data consisting of title ID, average rating, and number of votes

* ```rt_movie_info```: Rotten Tomato data consisting of ID (which correlates to a unique movie), synopsis, rating, genres, Director, and other data that was not used for the purpose of this project

* ```rt_reviews```: Rotten Tomato data consisting of ID (many reviews per movie ID), rating, fresh/rotten, and other data not used for the purpose of this project

* ```bom.movie_gross```: BOM data consisting of movie title, studio, domestic gross, foreign gross, year

***


<img src="Images/movie_ratings_by_genre.png">
<img src="Images/movie_gross_by_genre.png">
<img src="Images/freshness_by_movie_rating.png">


# Conclusion
***

This analysis leads to three recommendations for movie productions:
1. Action or Family based on gross box-office income
2. Documentary or Biography based on viewer/critic ratings
3. R rated movie based on overall critic response

(Bonus would be to get Steven Spielberg to direct the movie, fortunately he directs a lot of Action/Sci-Fi movies, so this correlates to high gross box-office income as well)


# Next Steps
***

Further Questions to Consider?

* Who are some up of the top up and coming actors? People who have had a recent increase in roles and are expected to continue to thrive

* How have the popularities of genres changed over time? Number of movies for each genre over time? Ratings of each genre over time?


