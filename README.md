# Investigate-a-Dataset---TMDb-Movie-Data

The primary goal of the project is to go through the general data analysis process — using basic data analysis technique with NumPy, pandas, and Matplotlib. The movie dataset, which is originally from Kaggle, was cleaned and provided by Udacity. According Kaggle introduction page, the data contains information that are provided from The Movie Database (TMDb). It collects 5000+ movies basic move information and movie matrices, including user ratings, popularity and revenue data. These metrics can be seen as how successful these movies are. The movie basic information contained like cast, director, keywords, runtime, genres, etc.


I performed exploratory data analysis to answer the business questions asked. The following questions were asked and insights were provided through analysis and visualizations:

## Questions
1. What is the trend of the movie popularity over the years?
2. What are the budget and revenue trends over the years?
3. What are the profit and revenue trends over the years?
4. What can you deduced from the number of movies released year by year?
5A. What is the average duration of movies based on popularity ?
5B. What is the average budget of movies based on popularity?
5C. What is the average revenue of movies based on popularity?
5D. What is the average profit of movies based on popularity?
6. Which director directed most films based on popularity?
7. Which cast has appeared the most based on popularity?
8. Which genres are more successful based on popularity?
9. Which production companies are more successful based on popularity?

## Conclusions
The Investigation shows us that -
1. The popularity of movies is going upward in recent years.
2. The Budget and Revenue tends to grow year over year, this trend seems to continue.
3. The Profit and Revenue tends to grow year over year, and their trends are similar in pattern.
4. There is a huge increase in the rate of movies year by year.

Features associated with popular movies are :
Average Runtime = 107 minutes.
Average Budget = 46 Million Dollars.
Average Revenue = 148 Million Dollars.
Average Profit = 110 Million Dollars
Cast associated with high popularity movies are Robert De Niro and Nicolas Cage;
Director associated with high popularity movies are Steven Spielberg and Clint Eastwood;
Genres associated with high popularity movies are drama, comedy, and thriller;
Production Companies associated with high popularity movies are Warner Bros., Universal Pictures and Paramount Pictures.

## Limitations
Units in Budget, Revenue, and Profit columns are undefined, it might be possible different movies have different currency according to the country they are produce in.
Characterising movies based on popularity is just one factor that is taken into account.
Data Quality - Most of the values are 0 in budget, revenue and runtime column, I would assume that they are missing.
The metrics of Popularity and vote counts data is undefined.
