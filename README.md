# Movie Database Project

* Coding Dojo Data Science Project 3
* Author: Jacob Wang
* Last updated: 3/6/2023

## Business Problem: Design a MySQL database on Movies from a subset of IMDB's publicly available dataset. Utilized the database to analyze what makes a movie successful and provided recommendations to the stakeholder on what makes a successful movie.

![moviesjawn](https://user-images.githubusercontent.com/112730629/222327496-49913c4a-9836-4d31-8885-887707a7071d.png)

## Data: 
* IMDB: https://datasets.imdbws.com/
* TMDB: https://www.themoviedb.org/

Column Name | Description
---|---
tconst | alphanumeric unique identifier of the title
averageRating | weighted average of all the individual user ratings
numVotes | number of votes the title has received
titleId | a tconst, an alphanumeric unique identifier of the title
title | the localized title
region | the region for this version of the title
language | the language of the title
attributes | Additional terms to describe this alternative title, not enumerated
titleType | the type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc)
primaryTitle | the more popular title / the title used by the filmmakers on promotional materials at the point of release
originalTitle | original title, in the original language
startYear | represents the release year of a title. In the case of TV Series, it is the series start year
endYear | TV Series end year. ‘\N’ for all other title types
runtimeMinutes | primary runtime of the title, in minutes
genres | includes up to three genres associated with the title




## Methods: 
* Cleaned and filtered IMDB movie data based on stakeholder specifications.
* Extracted additional movie data, including financial data and movie ratings using The Movie Database (TMDB) API and constructed a MySQL Database after combining the data from IMDB and TMDB. 
* Utilized the MySQL database and several hypothesis testing methods to answer key stakeholder questions about what makes a movie successful. 
  * Hypothesis Testing Methods:
    * One-Way ANOVA Tests
    * Tukey's Pairwise Multiple Comparisons Test
    * 2-Sample T-Test    


## Results: 

![movieRevByRating](https://user-images.githubusercontent.com/112730629/222327877-07a8f235-cb33-4459-9253-91f559deed11.jpeg)
* Movie revenues are indeed affected by their MPAA rating.
* Movies that are rated G and PG are the highest grossing, followed by PG-13 and R.

![movRevbyRuntime](https://user-images.githubusercontent.com/112730629/222328542-6fc0c2c7-0d47-43d3-946c-5bc2986a0312.jpeg)
* Movies that are longer than 2.5 hours typically earn more revenue than those that are not.

![movBudgetsOverTime](https://user-images.githubusercontent.com/112730629/222328629-5ee910f6-0882-4307-b7e8-7bc068f40a6f.jpeg)
* From the years 2000-2012, movie budgets slowly decreased. 

## Recommendations:
* Movie makers should try to create movies that can be rated G or PG. These films tend to earn more revenue, perhaps because they can be viewed by a broader audience. 
* Movies that are over 2.5 hours have historically earned more revenue than those that were not. 



