# Examen du cours "Systèmes distribués"

Barème : 
- 10 points pour les réponses aux questionnaires
- 5 points pour la parallélisation du programme OpenMP
- 5 points pour le notebook Dask

## Evaluation théorique : questionnaire à rendre à la fin de l'examen

Un questionnaire papier vous a été distribué.
Certaines questions peuvent vous aider pour compléter les codes C et Python et d'autres nécessitent d'avoir fait les exercices partiques.

## Evaluation pratique

Créer un dossier examen : /work/C3/formation-isae/login/examen.
Mettre dans ce répertoire tous les fichiers nécessaires pour compiler et éxecuter votre code OpenMP ainsi que votre notebook Dask.

### Programme de réduction d'un tableau à paralléliser avec OpenMP

Le programme contenu dans le fichier reduction_tab.c est extrait d’un code de chimie.
Utiliser un terminal et les scripts vus dans le BE OpenMP pour compiler et exécuter le programme.

Il s’agit de réduire un tableau tridimensionnel en un vecteur. Le but de ce TP est de paralléliser avec des directives OpenMP ce noyau de calcul.
1. Analyser le statut des variables et adapter le code source de façon à paralléliser la boucle la plus externe en k.
2. Comparer les performances obtenues sur TREX en fonction du nombre de threads d’exécution 

| Nombres de threads | Temps "elapsed"  | Accélération =(temps elapsed mono / temps "elapsed" //) |
| ------ | ------ |------- |
|     mono (avant la parallélisation)   |        |    1    |
|       1 |        |        |
|       2 |        |        |
|       3 |        |        |
|       4 |        |        |

 

### Notebook Jupyter

Les questions sont intégrées dans le texte du notebook à exécuter avec le kernel Pangeo.
