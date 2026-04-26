# Aide à la Décision - Analyse Multicritère

## Description du Projet
Ce projet a été réalisé dans le cadre du module **Fondamentaux Mathématiques pour l'Aide à la Décision**. L'objectif est d'évaluer et de classer différents pays en fonction de 11 critères de risque mondiaux (Changement climatique, Cybersécurité, Crises économiques, etc.). 

L'étude se base sur des concepts mathématiques de théorie de la décision pour transformer des données brutes en un classement qualitatif.

**Membres du groupe :**
* Magomed Tsitsiev
* Kishan Patel
* Amaury Vecchiatto

## Méthodologie Implémentée
Le projet explore deux approches majeures de l'aide au choix :
* **Dominance au sens de Pareto** : Analyse des propriétés de la relation de dominance (réflexivité, symétrie) pour identifier les alternatives non dominées.
* **Méthode ELECTRE** : Utilisation de relations de surclassement avec des seuils de concordance et de non-veto pour classer les pays dans des catégories de performance allant de **A (Excellente)** à **E (Faible)**.

## Structure du Projet
* **Projet.ipynb** : Notebook principal contenant les algorithmes de tri, les fonctions de calcul de dominance et les résultats.
* **Rapport.pdf** : Document détaillant le raisonnement mathématique, les propriétés des relations et l'interprétation du classement final.
* **README.pdf** : Consignes et objectifs originaux du projet.
* **data/** : Dossier contenant le dataset source.
    * **Pays_projet.csv** : Données des pays avec leurs scores sur les 11 critères de risque.

## Installation
Le projet nécessite Python et les bibliothèques suivantes :
```bash
pip install pandas numpy matplotlib mip
