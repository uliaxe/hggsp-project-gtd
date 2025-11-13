# Analyse des Données de Conflit en Irak et Syrie (2013-2019)

Ce projet applique des méthodes d'analyse de données (Data Science) pour étudier les dynamiques du conflit en Irak et en Syrie, en se concentrant sur la période 2013-2019.

**Note importante :** Ce projet est une analyse académique et technique. Il n'exprime aucune opinion politique et n'a pas pour but de commenter la nature des acteurs impliqués, mais d'analyser quantitativement leurs modes d'action.

## 1. Contexte Académique

Ce travail s'inscrit dans le cadre du programme de spécialité **Histoire-Géographie, Géopolitique et Sciences Politiques (HGGSP)** de Terminale.

Il vise à explorer l'Axe 1 du **Thème 2 : "Faire la guerre, faire la paix"**, qui étudie :
> "Le modèle de Clausewitz à l'épreuve des « guerres irrégulières » : d'Al Qaïda à Daech."

**Objectif :** Utiliser les données pour analyser l'évolution d'un acteur non étatique (l'État Islamique, désigné "Islamic State" dans la source) afin de caractériser la nature de ses actions (guerre conventionnelle vs. guerre irrégulière/terrorisme) à travers son implantation territoriale et ses modes opératoires.

## 2. Source des Données

* **Source :** [ACLED (Armed Conflict Location & Event Data Project)](https://acleddata.com/)
* **Période :** 1er janvier 2013 - 31 décembre 2019
* **Zone :** Irak et Syrie
* **Filtre :** Événements impliquant l'acteur "Islamic State".

## 3. Méthodologie

Le projet (contenu dans les notebooks Jupyter ou scripts Python) suit 3 axes d'analyse :

1.  **Analyse Temporelle :**
    * Visualisation de l'évolution du nombre d'événements et de victimes dans le temps pour identifier les phases d'émergence, d'apogée ("proto-État") et de déclin.

2.  **Analyse Spatiale :**
    * Cartographie des événements (nuages de points et *heatmaps*) pour visualiser l'évolution du contrôle territorial et des "points chauds" du conflit.

3.  **Analyse des Modes d'Action :**
    * Analyse de la typologie des événements (ex: "Battles", "Explosions/Remote violence", "Violence against civilians").
    * Visualisation de l'évolution de la *proportion* de ces tactiques pour observer le passage d'une logique de conquête à une logique de guérilla.

## 4. Outils Techniques

* **Langage :** Python
* **Librairies principales :** Pandas (manipulation), Matplotlib / Seaborn (visualisation), Geopandas (analyse spatiale).

---
