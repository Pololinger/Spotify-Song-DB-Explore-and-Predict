### Spotify dataframe exploration, visualizations & predictions with scikit-learn


#### Part 1 - Exploring the dataframe with pandas, numpy and visualizing it with matplotlib, seaborn, and plotly

##### Please use [nbviewer](https://nbviewer.jupyter.org/) to display the interactive plotly charts for Part 1

##### 1.1 - Are all genreso on Spotify music songs in the traditional sense? 

###### Spotify has two variables that help us making a conclussion here about the 'comedy' genre

![comedy][1]

##### 1.2 - Comparing genres by popularity

![popularity][2] 

##### 1.3 - Correlation matrix for the variables


![correlation][3] 

##### 1.4 - Exploring how similar the genres are across the given variables e.g. radar chart


![radar][4] 


#### Part 2 - Predicting the genre of a song with scikit-learn's random forest, AdaBoost and MLPClassifier

##### The models perform very well for genres that are very distinct such as 'comedy' and 'opera' but less so for others. The classifier is also struggling with the high number of genres. Reducing the number of genres in the dataframe improved the performance. 


#### Part 3 - Binary classification of song popularity

##### Determined a 'popularity' threshold to spliit the dataframe into popular and unpopular. After creating a balanced sample, Random Forest produced good results.



[1]: ./assets/comedy.png
[2]: ./assets/song_popularity_by_genre.png
[3]: ./assets/correlation_matrix.png
[4]: ./assets/electro.PNG












