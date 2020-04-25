### MOVIE_PROJECT ###

*For this project we asked the following questions:*
1. What genre and maturity rating pair is "best"?
2. What are some top directors for that pair?
3. What is the correlation between box office profit and high ratings of a movie?

Data: we scrape IMDB the top 100 movies of a year sorted by popularity for the past ten years. 

To answer the first question we determine what it means to be a "best" pair. 
By "best" pair we mean a tuple (G,RM) where G denotes genre and MR denotes maturity pairing such that (G,RM) is in the intersection of at least two groups of three:
best box office profit, best popularity (determined by average skewness), best rating/scores from imdb and metacritic. 

To answer our second question we determine for such pairs the directors from our list of movies and determine which directors movies had best box office profit and rating. 

To answer our third question we normalize imdb score, metascore and box-office profit and draw a scatter plot to see if there is a correlation. 

All visualizations are made by matplotlib and seaborn
