# Song_Recommender
Building a song recommender based on what's popular right now (Billboard's Hot 100) or finding similar songs using machine learning.

The song recommender system is based on audio features of songs. It uses Spotify's Web API to fetch audio features of songs and applies clustering techniques to group similar songs together. The song recommender system works as follows:  

- fetch audio features of songs using Spotify Web API  
- apply feature engineering techniques (e.g., PCA) to reduce dimensionality and identify important features  
- apply clustering algorithms (e.g., K-means) to group similar songs together  
- receive input of a seed song from the user  
- recommend similar songs based on the cluster of the seed song  

## Technologies  
Spotify Web API  
Scikit-learn  
NumPy  
Pandas  
Matplotlib  
