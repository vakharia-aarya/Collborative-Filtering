# Collaborative Filtering

The project uses the concepts of collaborative filtering in order to build a recommendation system. The recommendation system ranks movies according to users past history. 

Collaborative filtering works by analyzing the correlation between  different users and their preferences. The algorithm then recommends movies by the highest correlation between users. 

We calculate the correlation between users by comparing the movies.csv that contain a list of movies off of IMDB and the ratings.csv which contains user reviews for given movies.  Using this matrix we can recommend our user the movies they are most likely to watch based on preferences of other users that liked a given movie. 

Lets say a user has a strong preference towards action movies, the graph below shows how likely they are to like (y-axis) each movie (x-axis) .

![Movie preference graph](https://github.com/vakharia-aarya/Collborative-Filtering/blob/main/action_lover.png)

For the same user, the algorithm gives the top 15 movies they are likely to enjoy. 

![Top 15 recommended movies for a user](https://github.com/vakharia-aarya/Collborative-Filtering/blob/main/2020-10-02.png)
