# Analyse des projets CORDIS liés au changement climatique 🌍📊

Ce projet a pour objectif de traiter et visualiser les données issues de la plateforme européenne **CORDIS** (Community Research and Development Information Service), afin d’identifier et d’analyser les projets de recherche ayant un lien avec les **changements climatiques**.

## 📁 Contenu du dépôt

### `creta_dataset.ipynb`
Ce notebook contient l’essentiel du traitement de données :
- Nettoyage et préparation des données CORDIS
- Création d’un **indicateur sémantique** mesurant le lien entre chaque projet et la thématique du changement climatique, basé sur les descriptions textuelles
- Construction du jeu de données final exploitable pour les visualisations et analyses

### `archive.ipynb`
Ce notebook présente les figures et visualisations générées à partir du jeu de données traité :
- Statistiques descriptives (répartition géographique, évolution temporelle, domaines thématiques, etc.)
- Graphiques illustrant la fréquence et la pertinence des projets liés au climat
- Analyse comparative des financements en fonction du score climatique

## 🛠️ Technologies utilisées

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn, SenteceTransformer (https://sbert.net/)
- Jupyter Notebooks

## 📦 Données

Les données utilisées proviennent de la base **CORDIS** (https://cordis.europa.eu/), récupérées en format CSV via leur interface ou leur API.  
Elles contiennent des métadonnées de projets financés par l’Union européenne : titre, résumé, budget, partenaires, etc.

## 📈 Objectifs

- Identifier les projets en lien avec le changement climatique de manière reproductible
- Visualiser l'évolution de l'engagement climatique dans les programmes de recherche européens
- Fournir un cadre d’analyse réutilisable pour d’autres thématiques (biodiversité, transition énergétique…)

