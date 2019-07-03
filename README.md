# Projet-Sio

présentation du projet : le but est de réaliser un jey de rôle permettant un jeu peu massivement multi joueur permettant 
aux étudiants du bts sio de se divertir pendant les heures de cantine mais surtout d'améliorer leurs compétences
en développement.


Les outils mis en oeuvre :

	- Git
	- Visual studio
	- mysql
	- apache

Le développement tourne autour de 3 grandes parties

	1 l'inscription en ligne 
	2 développement du jeu en lui même permettant l'exploration d'un labyrinthe
	3 la sauvegarde des personnages et du contexte du jeu 

| développement           | langages | technique de programmation                          |
|-------------------------|:--------:|:---------------------------------------------------:|
|inscription en ligne	  |php,Mysql |développement web MVC avec Code Igniter              |	
|sio crawler le jeu 	  |c#        |programmation objet tests unitaires                  |     
|sauvegarde du contexte   |c#, mysql |programmation procédural procédures stockée en mysql |
  


## L'inscription en ligne ##

site web permettant à un joueur de s'inscrire en ligne le projet prévoit le principe suivant pour l'inscription en ligne. 

![acteurFluxInscription.PNG](https://zupimages.net/up/19/27/3i31.png)



## sio crawler le jeu ##

le joueur possèdera les fonctionnalités suivant 


![acteurFluxInscription.png](https://zupimages.net/up/19/27/50a0.png)


les classes développées.

![diagrammeClassePersonnage.png](https://zupimages.net/up/19/27/i39q.png)


## Sauvegarde du context ##

La sauvegarde du contexte se fera dans la base de données.

![mcdSauvegarde.PNG](https://zupimages.net/up/19/27/c1am.png)
