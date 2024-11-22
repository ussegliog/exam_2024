# Examen du cours "Systèmes distribués"

Créer un dossier examen dans votre répertoire /work/C3/formation-isae/login.
Mettre dans ce répertoire tous les fichiers nécessaires pour éxécuter votre code OpenMP et notebook Dask.

## Programme OpenMP

Le programme contenu dans le fichier reduction tab.f90 est extrait d’un code de chimie.
Il s’agit de réduire un tableau tridimentionnel en un vecteur. Le but de ce TP est de paralléliser ce noyau de calcul sans toucher
à l’ordre initial des boucles (i.e. k,j,i).
1. Analyser le statut des variables et adapter le code source de façon à paralléliser la boucle la plus externe en k.
2. Comparer les performances obtenues en utilisant l’association thread/coeur
d’exécution par défaut sur Trex et en utilisant le mode d’association scatter.
Proposer une explication quant aux mauvaises performances de ce dernier.
3. Optimiser le code source pour le mode scatter en prenant en compte l’affinité
mémoire en langage C. Pourquoi cette troisième série d’exécutions permet-elle d’obtenir les meilleures performances ? 


## Notebook Jupyter
