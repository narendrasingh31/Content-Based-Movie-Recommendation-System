# Content-Based-Movie-Recommendation-System
Content movie recommendation system using machine learning (scikit-learn)

## Overview:
We are going to build a model that takes a movie title as an input and output a list of the 5 most similar movies. Firstly, for this we need a mechanism to identify the index of a movie in our metadata DataFrame, given its title.

It turns out that there are (mostly) three ways to build a recommendation engine:

1. Popularity based recommendation engine.
2. Content based recommendation engine.
3. Collaborative filtering based recommendation engine.

But we are going to implement a Content based recommendation system using the scikit-learn library.

## Popular movies:
![image](https://user-images.githubusercontent.com/104161233/176396416-0e8cf30a-6807-47e1-88c8-540c95d9c0c0.png)

## What is Cosine Similarity and How does it work?
Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space.

It is a numerical value, ranges between 0 to 1 which helps to determine how much two items are similar or close to each other on a scale of 0 to 1. This similarity score is obtained by measuring the similarity between the text details of both of the items.

![image](https://user-images.githubusercontent.com/104161233/178241828-5661c990-4a6d-4e19-99c6-e3eafb51ec9d.png)

More about Cosine Similarity : [Understanding the Math behind Cosine Similarity](https://www.machinelearningplus.com/nlp/cosine-similarity/)

## Conclusion:
In this movie recommendation system, we build a recommender model while taking the inputs of the user and recommended 5 similar movies.

