# Analyse des Émotions avec PyCaret

Ce projet présente une analyse complète des émotions dans des textes en utilisant PyCaret, une bibliothèque d'apprentissage automatique low-code et open-source.

## Objectifs

- **Prétraitement et analyse** des données textuelles
- **Visualisations spécialisées** pour le NLP (nuages de mots, distribution des émotions)
- **Entraînement automatique** de plusieurs modèles de classification
- **Comparaison des performances** selon différentes métriques d'évaluation
- **Optimisation automatique** des hyperparamètres

## Dataset

Le projet utilise un dataset d'émotions contenant :
- **21,461 échantillons** d'entraînement
- **6 émotions** : sadness, anger, love, surprise, fear, joy
- **Textes en anglais** avec leurs émotions associées

## Installation et Utilisation

### 1. Environnement virtuel (recommandé)
```bash
# Créer un environnement virtuel
python -m venv venv

# Activer l'environnement (Windows)
venv\Scripts\activate

# Activer l'environnement (macOS/Linux)
source venv/bin/activate
```

### 2. Installation des dépendances
```bash
pip install -r requirements.txt
```

### 3. Lancement du notebook
```bash
jupyter notebook main.ipynb
```

## Technologies Utilisées

- **PyCaret** : Framework low-code pour l'apprentissage automatique
- **Pandas** : Manipulation des données
- **Matplotlib/Seaborn** : Visualisations statiques
- **Plotly** : Visualisations interactives
- **WordCloud** : Génération de nuages de mots
- **Scikit-learn** : Modèles de machine learning

## Résultats

Le projet compare automatiquement plusieurs algorithmes :
- **Régression Logistique**
- **Naive Bayes**
- **Random Forest**
- **SVM**
- **XGBoost**
- **K-Nearest Neighbors**
- **Decision Trees**

Les modèles sont évalués selon :
- **Accuracy** (Précision)
- **Precision** (Précision par classe)
- **Recall** (Rappel)
- **F1-Score**
- **AUC**

## Visualisations

Le notebook inclut :
- **Distribution des émotions** avec graphiques interactifs
- **Nuages de mots** par émotion
- **Analyse des mots les plus fréquents**
- **Matrices de confusion**
- **Métriques de performance**

## Fonctionnalités PyCaret

- **Setup automatique** de l'environnement ML
- **Comparaison automatique** de modèles
- **Optimisation des hyperparamètres**
- **Validation croisée** automatique
- **Déploiement simplifié**

## Structure du Projet

```
ml-in-the-clouds/
├── main.ipynb           # Notebook principal
├── requirements.txt     # Dépendances Python
├── README.md           # Documentation
└── data/
    ├── emotions_train.csv  # Dataset d'entraînement
    └── emotions_test.csv   # Dataset de test
```

## Prochaines Étapes

1. **Collecte de données** supplémentaires
2. **Test d'autres techniques** de preprocessing
3. **Déploiement en production**
4. **Intégration dans une application web**
5. **Support multilingue**

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Ouvrir des issues pour signaler des bugs
- Proposer des améliorations
- Ajouter de nouvelles fonctionnalités

## Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

---

**Développé avec PyCaret - Le framework low-code pour l'apprentissage automatique**-