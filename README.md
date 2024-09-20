# Movie Recommendation System

### What are Recommendation Systems? 📺
A recommendation system is a subclass of information filtering system, that seeks to predict the "rating" or "preference" a user would give to an item. It filters the data using different algorithms and recommends the most relevant items to users. It first captures the past behavior of a customer and based on that, recommends products which the users might be likely to buy. 

Some applications include:
* playlist generators for videos and music services like Netflix, YouTube and Spotify
* product recommendations for services such as Amazon
* content recommendations for social media platforms such as Facebook and Twitter

### How do Recommendation Systems work?
1. Data Collection
2. Data Storage
3. Filtering the data - Content-based filtering and Collaborative filtering

**Content-based filtering**: Users or items have profiles describing their characteristics and the system would recommend an item to a user if the two profiles match.  
**Collaborative filtering**: Recommendations are provided to users based on historic users' preference for items (clicked, watched, purchased, liked, rated, etc.)  

<p align="center">
  <img width="460" height="300" src="https://github.com/user-attachments/assets/29329ad3-e511-4f0f-bcc2-ae620f37f8ab">
</p>

### Building a Movie Recommendation System using KNN 
In this project, I've used nearest-neighbor-based method to build a movie recommendation system. Nearest-neighbor systems are based on the similarity between pairs of items or users.  
Cosine similarity is often used for measuring the distance:  
![image](https://github.com/user-attachments/assets/ac4aabe6-6f84-462c-bd94-0137c92ad110)

See the [code](https://github.com/Minautee/Movie-Recommendation-System/blob/a73242a35a5c552c8e8713533c5e732a3a35f626/movie_recommendation.ipynb) above to get a comprehensive understanding of how the recommendation system suggests movies based on my liking and suggest similar 5 movies to users who have also watched the same movie.
