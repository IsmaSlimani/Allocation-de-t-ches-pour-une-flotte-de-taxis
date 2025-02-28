# Allocation de tâches pour une flotte de taxis

Ce projet s’inscrit dans l’étude et la mise en œuvre de méthodes décentralisées pour l’allocation de tâches dans des flottes de taxis autonomes. 
Le problème abordé consiste à gérer l’affectation dynamique de trajets, générés aléatoirement dans un environnement 2D, à un ensemble de taxis. 
L’objectif principal est d’optimiser cette allocation de manière à minimiser la distance totale parcourue par l’ensemble de la flotte.
L'environnement crée repose sur une architecture orientée objet en Python, où sont représentés l’espace de travail, les taxis, ainsi que les tâches à réaliser. 
Nous avons développé un algorithme d’allocation de tâches basé sur des permutations ainsi qu'une approche gloutonne pour optimiser la répartition des trajets entre les taxis, en cherchant à minimiser le coût total de déplacement.
Nous avons ensuite appliqué des Distributed Constraint Optimization Problems (DCOP) pour résoudre le problème d’affectation des
tâches. Cette approche permet de modéliser le problème sous une forme décentralisée et
d’exploiter des algorithmes de résolution distribuée tels que DSA et MGM.
Enfin, nous avons mis en place de protocoles de négociation à travers des mécanismes d’enchères permettant aux taxis de s’attribuer les tâches de manière autonome.
L’objectif final est d’analyser les performances des différentes approches mises en
œuvre et de les comparer expérimentalement, en mettant en avant leurs avantages et
leurs limites dans des scénarios variés.
