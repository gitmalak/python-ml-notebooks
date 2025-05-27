# python-ml-notebooks
Mes projets en Python &amp; Machine Learning

Ce dépôt regroupe différents notebooks réalisés durant ma formation en intelligence artificielle et en apprentissage automatique. Chaque projet aborde une méthode ou un algorithme différent, avec des cas d’application concrets.

---

## 📁 Projets disponibles
# 🎧 SpotifyClustering.ipynb

Ce notebook présente un projet de clustering de chansons Spotify basé sur leurs caractéristiques audio. L’objectif est de regrouper automatiquement les chansons selon leur **humeur**, **énergie**, **popularité**, etc., à l’aide d’algorithmes de machine learning non supervisé.

## 🧠 Objectifs du projet
- Explorer un jeu de données Spotify contenant des caractéristiques musicales (tempo, valence, danceability…)
- Appliquer une méthode de **clustering** (par exemple k-means) pour regrouper les chansons selon leur profil audio
- Visualiser les clusters pour interpréter les regroupements

## 📊 Données utilisées
Le dataset contient :
- Nom de l’artiste et de la chanson
- Popularité, durée, explicite
- Caractéristiques audio : `danceability`, `energy`, `valence`, `tempo`, etc.
- Variable cible (pour analyse) : `genre` ou `mood`

## 🧪 Méthodes utilisées
- Prétraitement des données avec `pandas` et `sklearn`
- Réduction de dimension avec **PCA** *(si appliquée)*
- Clustering avec **KMeans**
- Visualisation avec `matplotlib` / `seaborn`

## 📌 Résultats
- Les chansons ont été regroupées en **X clusters** cohérents selon leurs caractéristiques audio
- Des interprétations ont été proposées pour chaque cluster

## 📁 Fichier
- `SpotifyClustering.ipynb` → notebook principal contenant l’analyse complète

## 💡 Pour aller plus loin
- Essayer d’autres méthodes de clustering (`DBSCAN`, `AgglomerativeClustering`)
- Ajouter des métadonnées textuelles (paroles, titre) pour enrichir les clusters
- Créer une playlist Spotify automatiquement par cluster

---

🔗 Projet réalisé par [Malak Nasri](https://github.com/gitmalak)
