# CIS5367-ML-Model-Presentation-II-

In this part of our project we have developed a two machine learning models.The first recommends recipes to customers using the ALS Collaborative filtering method. In collaborative filtering we are using past rating by customers for differnet recipes in the form of a matrix. We use matrix factorization to find two other matricies that when multiplied give us a matrix equivalent to the the one with the past ratings. In addition we will also acheive the "missing values" which are the estimated ratings for products by a customer. We can use these predictions to recommend a recipe to a given customer.

The second model is based on cosine similarity using K-Nearest-Neighbours, where K values is 5 and the algorithm we chose was brute with the help of content based collaborative filtering. This produces recommendations for the different customers.

In all we noticed that these both these models perform well.
