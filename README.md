# Gaussian_Process_Optimization
Projet de Statistique bayésienne autour de l'article:
* Jasper Snoek, Hugo Larochelle, and Ryan P Adams. "Practical Bayesian optimization
of machine learning algorithms". In Advances in neural information processing systems, 2012.

Pour utiliser le noteboook, ci-joint il faut avoir les packages de Python disponibles suivants sur son ordinateur:
- numpy
- matplotlib
- sklearn
- scipy
- warnings

Dans le cas où il faut installer ces packages, il suffit d'ouvrir une commande du système (en ayant spécifié le répertoire
de Python préalablement) ou la commande d'anaconda (anaconda prompt) et d'y exécuter la ligne "pip install + le nom du package"
ou "conda install + le nom du package", afin d'installer les packages manquants. Si le package est déjà installé, une ligne 
sur l'invite de commande va alors vous l'indiquer en éxécutant la ligne précédente.

Pour exécuter notre notebook, il suffit de compiler chaque partie de Python du notebook dans l'ordre (de haut en bas).

Le but de ce notebook est de trouver les hyperparamètres optimaux de divers algorithmes de machines learning (ici disponibles sur sklearn) en fonction des données disponibles (le datasets). Pour cela on utilise de l'optimisation bayésienne qui, en fonction des données, optimisera de façon différente plusieurs algorithmes de machine learning.
Dans ce notebook, on peut de visualiser plusieurs cas de machine learning (SVM et SGD) avec des différents types de datasets.

Voir le notebook pour plus de détails sur l'étude et l'implémentation en Python.
