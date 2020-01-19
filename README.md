# Hit-Song-Prediction-using-NLP

![](http://jouchihchang.int-des.com/wp-content/uploads/2017/10/hit-song-science.jpeg)

The project aims at developing a model using that can predict whether a song is going to be hit or not based on song lyrics and metadata.

### Approach
This project follows the following approach:
  1. Scrape ~150 playlists of current decade songs using Spotify and Last.fm API
  2. Clean data using NLTK
  3. Use LDA to put songs under different topics(Topic Modeling)
  4. Get the sentiment score for each songs
  5. Use RandomForest Classifier to predict whether a song will be hit (get more than 100k listeners) or not 
  6. Present the perfect recipe for a hit song 

### Sample Result
Recipe for a hit breakfree song:
  * A healthy portion of loudness
  * Generous serving of energy
  * A pinch of sentiment to taste
  * Avoid  acousticness and instrumentalness, for the dish to come out in the best possible way!
