# Système de recommandation

Le problème que nous résolvons dans ce projet est un problème dit de filtrage collaboratif, qui permet de créer un système de recommandation permettant de prédire l’évaluation d’un film par un utilisateur en se basant sur les évaluations de l’ensemble des utilisateurs.

![image](https://user-images.githubusercontent.com/66040216/115104281-c02bd000-9f57-11eb-9c4c-c633b3489f5a.png)

Nous avons à notre disposition un RDD "ratings" du type (userID, movieID, rating). 

Les données sont issues de la base de données "The MoviLens Datasets" :
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems

Deux méthodes ont été proposées : 
* ALS de la librairie MLlib
* Algorithme de descente de gradient
