# Movies_recommendation_system
<h1>Team Name</h1> : Steep Walkers

<h1>Dataset</h1> : Movies and Ratings

<ul><h1>Team Members:</h1>
  <li>Arvind Nachiappan</li> 
  <li>Jeffery</li>
  <li>keerthana</li>
</ul>
<h1>About dataset:</h1>

<h3>fields present in our Movies dataset</h3>
<ol>
    <li>movieId</li>
    <li>title of the movie</li>
    <li>genres of the movie</li>
</ol>
<h3>fields present in our ratings dataset:<h3>
 <ol>
    userId
    movieid
    ratings
    timestamp
 </ol>
    
 The field movieId is available in both the datasets which helps us to perform merge so that we can find the maximum rated movie among all movies
 
Implementation:
  <h5>there are several ways to recommend a movie but in this project we implemented the recommendation based on the content of the movie</h5> 
  
  <p>This type of recommendation systems, takes in a movie that a user currently likes as input. 
  Then it analyzes the contents of the movie to find out other movies which have similar content. 
  Then it ranks similar movies according to their similarity scores and recommends the most relevant movies to the user.</p>
  
  <ul>
  <li> first we performed split on every geners get a view on all genres that are available</li>
  <li> then we used word cloud to display all the geners that are available</li>
  <li> we sorted out the number of people who voted and the maximum rating given to a movie</li>
  <li>then we displayed the top 20 movies based on the highest rating they have secured</li> 
  <li>then we displayed the top 20 movies based on the number of people voted</li>
  <li>we used tfidvectorizer which converts the text into a vectors that can be implemented as an input</li>
  <li>atlast we used linear kernel method</li>
  </ul>
    

  
  
