# Movies_recommendation_system
<h1>Team Name</h1> : Steep Walkers

<h1>Dataset</h1> : Movies and Ratings

<ul><h1>Team Members:</h1>
  <li>Arvind Nachiappan<li> 
  <li>Jeffery</li>
  <li>keerthana</li>
</ul>
<h1>About dataset:</h1>
<ol>
<h3>fields present in our Movies dataset</h3>
    <li>movieId</li>
    <li>title of the movie</li>
    <li>genres of the movie</li>
</ol>
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
  
  
