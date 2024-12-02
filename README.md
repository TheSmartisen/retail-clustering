# README

## Introduction

Ce projet porte sur l'analyse et la segmentation des clients à l'aide de techniques de clustering. L'objectif principal est de comprendre les comportements des clients d'un commerce en ligne basé au Royaume-Uni et de proposer des stratégies marketing adaptées.

Le dataset utilisé contient les transactions effectuées entre le **1er décembre 2010** et le **9 décembre 2011**. Chaque ligne représente une transaction, avec des détails sur le produit, la quantité, le prix et les informations client.

---

## Structure du projet

### 1. Fichiers inclus

- **Dataset :**
  - `Online Retail.xlsx` : Fichier contenant les transactions à analyser.
- **Notebooks Jupyter :**
  - `01_exploration.ipynb` : Analyse exploratoire des données.
  - `02_clustering.ipynb` : Implémentation des modèles de clustering.
  - `03_feature_engineering.ipynb` : Création des variables FRM.
  - `04_dimensionality_reduction.ipynb` : Réduction de dimensionnalité avec PCA.
  - `05_interpretation_recommendations.ipynb` : Interprétation des clusters et recommandations.

---

### 2. Dossiers

- `data/` : Contient les données brutes et traitées.
- `models/` : Fichiers des modèles sauvegardés.

---

## Phases du projet

### Phase 1 : Exploration des données

- Objectif : Comprendre la structure, les distributions et les anomalies des données.
- Actions :
  - Chargement des données.
  - Analyse des statistiques descriptives.
  - Visualisation des distributions.
  - Identification des valeurs manquantes et des anomalies.

### Phase 2 : Prétraitement des données

- Objectif : Nettoyer les données et créer des variables pertinentes.
- Actions :
  - Gestion des valeurs manquantes.
  - Encodage des variables qualitatives.
  - Normalisation des variables quantitatives.

### Phase 3 : Feature Engineering

- Objectif : Créer des variables FRM (**Frequency, Recency, Monetary**) pour la segmentation.
- Actions :
  - Calcul des indicateurs par client.
  - Agrégation des données par client.

### Phase 4 : Clustering

- Algorithmes :
  - **K-means**
  - **Clustering hiérarchique**
  - **DBSCAN**
- Actions :
  - Réduction de dimensionnalité (PCA).
  - Calcul des scores de silhouette.
  - Visualisation des clusters.

### Phase 5 : Interprétation et Recommandations

- Objectif : Comprendre les segments de clients et proposer des stratégies marketing.
- Actions :
  - Analyse des caractéristiques de chaque cluster.
  - Recommandations marketing ciblées.

---

## Installation

### Prérequis

- Python 3.8+
- Bibliothèques Python :
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `plotly`

### Installation des dépendances

Pour installer les dépendances, exécutez :

```bash
pip install -r requirements.txt
```

---

## Utilisation

### 1. Exécution des notebooks

- Lancer le notebook `01_exploration.ipynb` pour analyser les données.
- Continuer avec les notebooks dans l'ordre suivant :
  - `02_clustering.ipynb`
  - `03_feature_engineering.ipynb`
  - `04_dimensionality_reduction.ipynb`
  - `05_interpretation_recommendations.ipynb`

---

## Résultats attendus

- Visualisations des clusters en 2D et 3D.
- Scores de silhouette pour évaluer les modèles.
- Segments de clients interprétés avec des recommandations associées.

---

## Auteur

Projet réalisé par HEM Patrick.