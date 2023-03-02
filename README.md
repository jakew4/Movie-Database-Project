# Movie Database Project

* Coding Dojo Data Science Project 3
* Author: Jacob Wang
* 2/28/2023

## Business Problem: For this project, you have been hired to produce a MySQL database on Movies from a subset of IMDB's publicly available dataset. Ultimately, you will use this database to analyze what makes a movie successful and will provide recommendations to the stakeholder on how to make a successful movie.

![moviesjawn](https://user-images.githubusercontent.com/112730629/222327496-49913c4a-9836-4d31-8885-887707a7071d.png)


## Methods: 
* Cleaned IMDB movie data by addressing null values and filtering data based on stakeholder specifications.
* Extracted additional movie data, including financial data and moving ratings using The Movie Database (TMDB) API and constructed a MySQL Database after combining the data from IMDB and TMDB. 
* Utilized the MySQL database and several hypothesis testing methods to answer key stakeholder questions about what makes a movie succesful. 


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



