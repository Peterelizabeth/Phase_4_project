# Phase_4_project
## MOVIE RECOMMENDATION SYSTEM
The dataset used for this project (ml-latest-small) contains 100836 ratings and 3683 tag applications across 9742 movies. The selected users had rated at least 20 movies. We used the movies and ratings dataset. The movies dataset contains;
- MovieId
- title
- genres

In addition, the ratings dataset contains;
- movieId
- userId
-rating
The dataset can be found here:'https://grouplens.org/datasets/movielens/latest/'

## Problem Statement 
In the context of the given dataset, our objective is to enhance movie recommendations for users. Our aim is to provide more accurate and perconalized movie recommendations to users based on their preferences and behavior.

## Approaches Used:
The project employs collaborative filtering and content-based filtering approaches to design a recommendater system. Collaborative filtering relies on user-item interactions. It is assumed that users would use items used in the past as their future preferences based on their ratings. To find similar movies, we used K nearest neighbors algorithm to find the movies which are similar by selecting 10 nearest movies.
The content based filtering approach helps address cold start problem in our model by recommending items based on their characteristics and how well they match a user's preference. In this case, we calculated similarity score based on the movies' genre to predict the most similar movies.

## Stakeholders
The success of this project will be great benefit to different users:
- E-commerce platforms - boost sales and customer loyalty.
- Content streaming services - retain subscribers.
- Movie and entertainment services - users of movie streaming platforms such as Netflix and Spotify to receive movies and album recommendations based on their watching habits and preferences.

## Conclusion
Creating a movie recommendation system would improve user experience by offering personalized movie suggestions based on personal preferences.
