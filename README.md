# Analyse Géopolitique de la Base de Données sur le Terrorisme Mondial (GTD)

Ce projet utilise des techniques de Data Science (analyse de données, visualisation) pour explorer les tendances géopolitiques et tactiques du terrorisme mondial de 1970 à 2019.

## 1. Contexte Académique (HGGSP)

Ce travail s'inscrit dans une démarche liant la spécialité **HGGSP (Histoire-Géographie, Géopolitique et Sciences Politiques)** et l'analyse de données.

L'objectif est d'utiliser un jeu de données quantitatives à grande échelle pour étudier concrètement des concepts clés du programme :
* Les dynamiques des **"guerres irrégulières"** et des conflits asymétriques.
* Le rôle des **acteurs non étatiques** dans les relations internationales.
* L'évolution et la **spatialisation** (géographie) des zones de conflit et de tension.

## 2. Source des Données

* **Source :** Global Terrorism Database (GTD)
* **Auteur Officiel :** National Consortium for the Study of Terrorism and Responses to Terrorism (START)
* **Accès :** [Kaggle Dataset (START-UMD/gtd)](https://www.kaggle.com/datasets/START-UMD/gtd)
* **Période :** 1970 - 2019

## 3. Axes d'Analyse

Le projet (contenu dans le notebook Jupyter) s'articule autour de trois axes d'analyse pour répondre à la problématique HGGSP.

### Axe 1 : Analyse Temporelle (Quand ?)
* **Question :** Y a-t-il une intensification du phénomène terroriste ?
* **Méthode :** Visualiser l'évolution du nombre d'incidents et de victimes (`nkill`) par an (`iyear`).
* **Objectif :** Identifier les grandes vagues, les pics d'activité et les tendances de fond.

### Axe 2 : Analyse Spatiale (Où ?)
* **Question :** Les "points chauds" (hotspots) du terrorisme se sont-ils déplacés ?
* **Méthode :** Utiliser les colonnes `latitude` et `longitude` pour créer des cartes de chaleur (heatmaps) et des nuages de points.
* **Objectif :** Visualiser la concentration géographique des incidents et son évolution par décennie (ex: 1980s vs 2010s).

### Axe 3 : Analyse Tactique (Comment ?)
* **Question :** Les méthodes et les cibles ont-elles changé ?
* **Méthode :** Analyser la fréquence des colonnes `attacktype1_txt` (type d'attaque) et `targtype1_txt` (type de cible).
* **Objectif :** Identifier si les tactiques (ex: attentats à la bombe, prises d'otages) et les cibles (ex: civils, militaires) ont évolué.

## 4. Outils Techniques

* **Langage :** Python
* **Librairies :** Pandas (manipulation), Matplotlib / Seaborn (visualisation), Geopandas / Folium (cartographie).
