# Aide à la Décision - Analyse Multicritère
## Description du Projet
Ce projet a été réalisé dans le cadre du module **Fondamentaux Mathématiques pour l'Aide à la Décision**. L'objectif est d'évaluer et de classer différents pays en fonction de 11 critères de risque mondiaux (Changement climatique, Cybersécurité, Crises économiques, etc.).
**Membres du groupe :**
* Magomed Tsitsiev
* Kishan Patel
* Amaury Vecchiatto
## Méthodologie Implémentée
Le projet s'appuie sur deux piliers mathématiques détaillés dans le rapport :
* **Dominance au sens de Pareto** : Analyse des relations de dominance entre les alternatives.
* **Méthode ELECTRE** : Utilisation de relations de surclassement (seuils de concordance et de non-veto) pour classer les pays dans des catégories allant de **A (Excellente)** à **E (Faible)**.
## Structure du Projet
* **analyse_indicateurs_pays.ipynb** : Le notebook principal contenant l'intégralité du code. Les cellules sont marquées par **#Numero X** pour correspondre aux questions du sujet.
* **Rapport.pdf** : Document expliquant les choix méthodologiques, les calculs mathématiques et l'interprétation des résultats.
* **data/** : Dossier contenant le dataset source.
    * **donnee_pays.csv** : Données brutes (scores des pays sur 11 critères).
## Installation
Le projet nécessite Python 3 et les bibliothèques suivantes :
```bash
pip install pandas numpy matplotlib mip
```
## Instructions de Lancement
Pour exécuter le projet et voir les résultats :

1. **Préparation** : Placez impérativement le fichier `donnee_pays.csv` dans le même dossier que le fichier  `analyse_indicateurs_pays.ipynb`
2. **Lancement** : Ouvrez un terminal dans le dossier du projet et lancez l'interface :
```bash
jupyter notebook analyse_indicateurs_pays.ipynb
```
3. **Exécution** : Une fois le notebook ouvert, exécutez les cellules dans l'ordre (du haut vers le bas).
   * Note : Chaque question est identifiée par un commentaire en haut de cellule (ex: `#Numero 1`).
4. **Visualisation** : Les classements par catégories (A, B, C, D, E) et les graphiques s'afficheront directement sous les cellules de code.
