# BankChurners
🏦 Prédiction de Churn Client - BankChurners

Ce projet vise à prédire si un client va quitter une banque à l’aide de données démographiques et transactionnelles. Il s'agit d'un cas classique de classification binaire utilisant des techniques de machine learning.

 🎯 Objectif
Déterminer les facteurs de churn et entraîner un modèle prédictif à l’aide du dataset "BankChurners".

 📁 Données

- Source : [Kaggle - Bank Churners](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)
- Colonnes : données clients, solde, fréquence d’utilisation, nombre de cartes, etc.
- Cible : `Attrition_Flag` (client ayant quitté ou non)

 ⚙️ Technologies

- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

 🔍 Analyse exploratoire

- Visualisation des distributions des variables
- Détection des valeurs manquantes
- Corrélations entre variables
- Analyse de l’équilibre des classes (churn vs non churn)

 🤖 Modélisation

- Encodage des variables catégorielles
- Normalisation
- Modèles testés :
  - Random Forest
  - Logistic Regression
  
 📊 Résultats

- Meilleur modèle : `Logistic Regression`
- Accuracy : 90,54% 

 📦 Installation

```bash
git clone https://github.com/ton-utilisateur/bank-churn-prediction.git
cd bank-churn-prediction
pip install -r requirements.txt
