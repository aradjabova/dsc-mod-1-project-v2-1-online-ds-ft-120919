
# MOVIE ANALYSIS


## Libraries Used
**numpy** - Used for quick math functions <br>
**pandas** - Used for working and analyzing dataframes<br>
**os** - Interface with the underlying operating system<br>
**matplotlib.pyplot** - Plot the dataframes into graphs<br>
**glob** - Generates lists of files matching given patterns<br>
**sqlite3** - Allows us to work with sql

## Project

Help Microsoft understand more about the movie industry.<br>
<br>
Analyize the data to help the understand the movie industry and create presentation about what types of movies are doing the best. <br>
<br>
Find insights to help the CEO decide on what types of movies to create


## Data Used

* IMDB
* Rotten Tomatoes
* Box Office Mojo
* The Movie DB

## Files 
* This README as a guide of the analysis
* *Exploratory Notebook* - importing and exploring all of the data given.
* *Student Data Analysis* - the complete understanding of the data and analysis.
* *Power Point PDF* - Full/easy analysis
* Video - youtube video walkthrough (not updated)

## Genres Dataframe
* Join imdb_title_ratings with the imdb_title_basics
* Join again with the tn_movie_budgets
* An inner join by titles
* Drop any of the columns that not going to use
* Create a column for profit margin calculations
* Create columns for each genre
* Crerate column for month release

## Directors Dataframe

* Join the tn_movie_budgets with imdb_title_crew
* Join with an inner merge to not have as many missing values 
* Get rid of unnecessary columns

## Popularity Dataframe

* Join the tmdb_movies with directors dataframe
* Join with an inner merge to not have as many missing values 
* Get rid of unnecessary columns and sorted

## Finance Dataframe

* Using the tn_movie_budgets 
* Clean dataframe 
* Get rid of unnecessary columns

## Data Cleaning
* Started with dropping any duplicated titles/title id
* Change all the money vales by getting rid of $ and commas <br>
* Change all the columns with the numerical values into **int** types
* Change the date column into a **datetime** type
* Drop missing values or fill missing values

## Questions Answering
**Genres**
    * What genres are the most profitable movies?
**Directors**
    * Who are the the directors of the most profitable movies?
**Popularity/Directors**
    * Which movies are the most popular?
    * Which movies are the most popular with the most votes?
    * What is the correlation between popularity and the production budget?
    * Is there a correlation between popularity and the release day?
    * Is there a correlation between popularity and the release month?    
**Finaces**
    * What are the most profitable movies?
    * What is the correlation between profit and release day?
    * What is the correlation between production budget and the profit?

