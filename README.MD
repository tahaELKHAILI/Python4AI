# TP — Implémentation d’un Mini Réseau de Neurones avec NumPy

**but:** ce TP a pour objectif d’introduire, à l’aide de NumPy et Matplotlib, les bases de l’implémentation d’un mini réseau de neurones from scratch.
Dans une première partie, il s’agit d’implémenter et de visualiser plusieurs fonctions d’activation (ReLU, Sigmoid, Tanh, LeakyReLU, puis Softplus et ELU), en produisant :

    un tracé comparatif des fonctions sur une même figure,
    une grille de sous-figures pour visualiser chaque fonction séparément.

Dans une deuxième partie, il s’agit d’implémenter un mini réseau de neurones 2 → 3 → 1 en NumPy pour apprendre la fonction XOR, en détaillant :

    la propagation avant,
    la fonction de perte,
    la rétropropagation des gradients,
    l’entraînement par descente de gradient,
    puis l’extension à un dataset XOR bruité avec données perturbées et labels erronés.

Enfin, le TP vise à évaluer le modèle appris à l’aide de métriques de classification telles que :

    Accuracy
    Precision
    Recall
    F1-score
    Matrice de confusion
    Courbe ROC et AUC

## Objectifs pédagogiques
A l’issue de ce TP, l’étudiant devra être capable de :
* implémenter des fonctions d’activation
* manipuler les produits matriciels NumPy
* comprendre les shapes des matrices
* implémenter un réseau de neurones 2 → 3 → 1
* implémenter la backpropagation
* entraîner un modèle pour apprendre XOR
* évaluer un modèle avec accuracy, precision, recall, F1
* analyser un modèle avec matrice de confusion et ROC curve
* comprendre l’effet du bruit dans les données

## Pré-requis
* Python 3.x
* Bibliothèques : numpy, matplotlib, scipy


