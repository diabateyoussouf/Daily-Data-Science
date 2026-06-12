# 🎯 Daily Machine Learning & Data Science Challenge

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

Bienvenue sur mon dépôt de suivi quotidien ! Ce projet est un espace d'entraînement personnel où je documente mon apprentissage du Machine Learning, jour après jour, à travers des cas pratiques et des notebooks concrets.

L'objectif est de pratiquer régulièrement le nettoyage de données (Preprocessing), le Feature Engineering, la sélection de modèles et l'optimisation des hyperparamètres.

---

## 📚 Table des Matières des Défis

| Défi | Dataset / Sujet | Objectif ML | Modèles Testés | Statut |
| :---: | :--- | :--- | :--- | :---: |
| **01** | [Titanic](./dailly_01_dataset_titanic.ipynb) | Classification binaire, gestion des doublons/NaN, feature engineering, overfitting. | Régression Logistique, SVM, Random Forest | ✅ |
| **02** | [House_price](./dailly_02_dataset_house_price.ipynb) | Regression lineaire multiVar,Gestions des doublons,features engineering,Overfitting |Ridge,RandomForestRegressor,HistGradientBoostingRegressor | ✅ |
| **03** |[Forecasting](./dailly_03_dataset_time-series-forecasting.ipynb)  | Groupement,Historique,Serie Temporaire  | HistGradientBoostingRegressor | ✅|
| **04** | ... | ...  | .. | ..|


---

## 🚀 Compétences clés développées au quotidien

### 🔍 1. Data Cleaning & Preprocessing Robustes
* Détection automatisée de la redondance et du *Data Leakage* via des scripts de similitude universels (appliqué sur `alive`/`survived` dans le Titanic).
* Imputation chirurgicale des données manquantes (`NaN`) basée sur des agrégations logiques (`groupby` + `transform`).
* Encodage propre (Binaire, One-Hot) et standardisation des échelles avec `StandardScaler`.

### 🧠 2. Modélisation sans concession
* Évaluation systématique sur un ensemble de validation distinct (`X_test`, `y_test`).
* Traque de l'**Overfitting** en comparant scrupuleusement les performances entre le *Train* et le *Test*.
* Création de fonctions d'automatisation pour entraîner et comparer visuellement plusieurs algorithmes et leurs matrices de confusion.
