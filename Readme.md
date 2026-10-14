# checkpoint-algorithmes-tableaux

## Problème 1 : Somme des éléments distincts
Etant donnés deux ensembles, trouver la somme des éléments présents dans un seul des deux.

**Exemple :**
Série 1 : [3, 1, 7, 9]
Série 2 : [2, 4, 1, 9, 3]
Elements distincts : 7, 4, 2
Sortie : 13

**Méthode :**
- Initialiser somme = 0
- Parcourir T1, si élément pas dans T2 -> ajouter à somme
- Parcourir T2, si élément pas dans T1 -> ajouter à somme
- Utilise tableaux et boucles imbriquées

## Problème 2 : Produit Scalaire

**Q1 - Procédure dot_product :**
Calcule ps = v1 . v2
- ps : passage par référence (VAR)
- v1, v2, n : passage par valeur

**Q2 - Algorithme orthogonalité :**
Pour n paires de vecteurs, appeler dot_product et tester si ps = 0 alors orthogonaux.

**Q3 - Version fonction :**
ps <- dot_product_fonc(v1, v2, n)

**Critères respectés :**
- Tableau pour vecteur
- Boucle imbriquée
- Différents types de passage de paramètres