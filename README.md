# Recommendation System with PySpark

The problem we solve in this project is a so-called collaborative filtering problem, which creates a recommendation system to predict a user's rating of a movie based on the ratings of all users.

![image](https://user-images.githubusercontent.com/66040216/115104281-c02bd000-9f57-11eb-9c4c-c633b3489f5a.png)

We have at our disposal a RDD "ratings" of the type (userID, movieID, rating).

The data comes from the "The MoviLens Datasets" database :

F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems

Two methods have been proposed :
* ALS from MLlib library
* Gradient descent algorithm
