# 📊 Prédiction du Churn Client - Télécom

## 📝 Contexte du Projet

En tant que Data Scientist Junior, ce projet constitue ma première mission professionnelle au sein d'une entreprise de télécommunications. L'objectif est de répondre à un défi stratégique majeur : **réduire le taux de désabonnement (churn)** qui impacte directement les revenus et la croissance de l'entreprise.

Actuellement, l'entreprise ne dispose d'aucune solution d'IA et base ses décisions sur des analyses descriptives basiques. Ce projet vise à fournir à l'équipe marketing un outil prédictif fiable pour lancer des campagnes de fidélisation ciblées.

---

## 🎯 Objectifs de la Mission

Développer un pipeline complet de **Machine Learning supervisé** pour identifier les clients à risque en se basant sur :

- Les informations contractuelles.
- Les services souscrits.
- Les données démographiques.
- L'historique de facturation et de paiement.

---

## 🛠️ Structure du Projet

Le projet est organisé de la manière suivante :

- **`Notebook_EDA.ipynb`** : Exploration complète des données (EDA), visualisations graphiques et premières analyses statistiques.
- **`pipeline.py`** : Script Python contenant les fonctions de préparation (nettoyage, encodage, normalisation), le split Train/Test et l'entraînement des modèles.
- **`test_pipeline.py`** : Tests unitaires automatisés pour valider la cohérence des données (ex: dimensions de X et y).
- **`models/`** : Comparaison des performances entre `LogisticRegression`, `SVC` et `RandomForestClassifier`.
- **`Rapport_Technique.pdf`** : Synthèse justifiant le choix du modèle final pour la mise en production.

---

## 📊 Métriques d'Évaluation

Pour garantir la fiabilité du modèle, les indicateurs suivants sont analysés :

- **Accuracy** (Précision globale)
- **Recall** (Sensibilité - crucial pour ne pas rater les départs clients)
- **F1-Score** (Équilibre précision/rappel)
- **Courbe ROC & PR Curve** (Performance de classification)

---

## 🚀 Fonctionnalités & Bonus

- [x] **Pipeline End-to-End** : De la donnée brute au modèle entraîné.
- [x] **Tests Automatisés** : Utilisation de tests unitaires pour la robustesse du code.
- [x] **Sélection de Features (Bonus)** : Implémentation de `VarianceThreshold` pour tester l'impact de la réduction de dimension sur les performances.

---
