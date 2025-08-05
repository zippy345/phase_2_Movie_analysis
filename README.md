# phase_2_Movie_analysis
## Step 1: Business Understanding
A company wants to start a new movie studio,they want to identify which types of films perform best at the box office in order to make informed decisions about what movies to produce.
### Project Objective:
To explore factors such as genre, budget, release date, ratings, and cast that affect movie success such as (profit, revenue).
### Business Questions:
* Which movie genres generate the highest revenue and profit?
* Which top 10 region have high production of movie production?
* Which actors, directors, and studios are most commonly associated with successful films?
* How does release timing (month/season) affect box office performance?
* Do movie ratings correlate with profitability?
* What combination of factors predicts a hit movie?
## Step 2 : Data Understanding
### Data Sources Overview
We use datasets from either of:
* IMDb
* The Numbers
* Box Office Mojo
* Rotten Tomatoes
* TheMovieDB
### Each dataset contains information such as:
* Movie title, genre, budget, revenue, profit
* Ratings, cast, director, release date
* Studio or production company
## Step 3 : DATA PREPARATION
### Cleaning Steps:
* Check if the datas have duplicates and handle them
* Handle missing values(drop, fill or replace them with unknows)
* Format date fields into consistent formats and (extract month/year/season) if necesarry
* Check on outliers and remove them if necessary.
### Feature engineering:
* Create new columns: profit = gross - budget, ROI = profit / budget, release_month
* Group actors/directors/studios by frequency/performance
##  Step 5 : EDA ANALYSIS
### Univariate analysis
* plot a bar that contains count of genres and retrieve top 10 genres.
* plot a time trend of the movie production yearly
* plot seasonal time trend of the movie production
* plot the top 5 languages used in movie production
# NB// here is the tableau dashboard [link](https://public.tableau.com/app/profile/wawira.muriithi/viz/Phase2movieproject/Moviesummary)
