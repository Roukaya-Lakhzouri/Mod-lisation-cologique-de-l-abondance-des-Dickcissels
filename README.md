# Modélisation écologique de l’abondance des Dickcissels

Ce projet vise à modéliser l’abondance des oiseaux Dickcissels en fonction de variables environnementales telles que le climat (clTma), la productivité végétale (NDVI) et la couverture du sol (grass). Il s’inscrit dans une démarche d’analyse statistique pour mieux comprendre les facteurs influençant la répartition de cette espèce, dans un objectif de conservation écologique.

## Contenu du projet

Le projet est structuré en plusieurs chapitres dans un rapport PDF contenant l’ensemble du code R et des analyses.

### 📊 Chapitre 1 – Statistiques descriptives
Analyse exploratoire des variables `abund`, `clTma`, `NDVI` et `grass`. Calcul des tendances centrales (moyennes, médianes), écart-types, visualisations (histogrammes, boxplots), et détection des valeurs aberrantes.

### 📈 Chapitre 2 – Analyse en Composantes Principales (ACP)
Réduction de dimension pour identifier les relations entre les variables explicatives. L’ACP permet de mettre en évidence les axes principaux de variation dans les données, facilitant leur interprétation.

### 📉 Chapitre 3 – Régression linéaire multiple
Modélisation de la variable cible `abund` à l’aide des variables prédictives `NDVI`, `grass` et `clTma`. Comparaison de modèles, estimation des coefficients, interprétation des effets individuels et évaluation de la performance du modèle.

## 🧰 Outils utilisés

- Langage : **R**
- Méthodes statistiques : Analyse descriptive, ACP, Régression multiple
- Visualisation : ggplot2, graphiques base R
- Rapport généré en : **PDF** avec code inclus

## 📄 Rapport

Le rapport complet avec toutes les analyses et le code R est disponible dans le fichier :  
📁 `rapport_Dickcissel.pdf`

## 📌 Objectifs pédagogiques

- Comprendre les relations entre variables environnementales et abondance animale
- Appliquer des méthodes statistiques classiques à un jeu de données réel
- Visualiser et interpréter les résultats dans un contexte écologique



