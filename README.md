# Movies_recommendation_system
Team Name : Steep Walkers

Dataset : Movies and Ratings

Team Members:
  Arvind Nachiappan 
  Jeffery
  keerthana
  
About dataset:
  fields present in our Movies dataset
    1.movieId
    2.title of the movie
    3.genres of the movie
  
  fields present in our ratings dataset:
    1.userId
    2.movieid
    3.ratings
    4.timestamp
    
 The field movieId is available in both the datasets which helps us to perform merge
 
Implementation:
  there are several ways to recommend a movie but in this project we implemented the recommendation based on the content of the movie 
  
  This type of recommendation systems, takes in a movie that a user currently likes as input. 
  Then it analyzes the contents of the movie to find out other movies which have similar content. 
  Then it ranks similar movies according to their similarity scores and recommends the most relevant movies to the user.
  
  we used tfidvectorizer which converts the text into a vectors that can be implemented as an input
  
  
