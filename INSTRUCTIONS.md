# Instructions d'Utilisation - Projet PyCaret Émotions

## Problèmes d'Installation Rencontrés

Le projet a rencontré des problèmes de compatibilité entre les versions de packages. Voici les solutions :

## Solution 1 : Environnement Virtuel (Recommandée)

```bash
# 1. Créer un environnement virtuel
python -m venv pycaret_env

# 2. Activer l'environnement
# Windows:
pycaret_env\Scripts\activate
# macOS/Linux:
source pycaret_env/bin/activate

# 3. Installer les packages compatibles
pip install pandas==1.5.3 numpy==1.24.3
pip install pycaret wordcloud plotly matplotlib seaborn
pip install textblob nltk spacy

# 4. Lancer Jupyter
jupyter notebook main.ipynb
```

## Solution 2 : Installation Directe

```bash
# Réinstaller avec versions compatibles
pip uninstall pandas numpy -y
pip install pandas==1.5.3 numpy==1.24.3
pip install pycaret[nlp] wordcloud plotly
```

## Solution 3 : Conda (Alternative)

```bash
# Créer environnement conda
conda create -n pycaret_env python=3.9
conda activate pycaret_env

# Installer les packages
conda install pandas numpy matplotlib seaborn plotly
pip install pycaret wordcloud textblob
```

## État Actuel du Notebook

**Fonctionnel :**
- Structure complète du projet
- Toutes les étapes PyCaret documentées
- Visualisations NLP spécialisées
- Code pour 6 émotions différentes
- Tests interactifs du modèle

**Nécessite correction :**
- Problèmes d'imports dans la cellule 2
- Versions incompatibles pandas/numpy

## Étapes du Projet

1. **Exploration des données** (21,461 échantillons, 6 émotions)
2. **Visualisations NLP** (nuages de mots, distribution)
3. **Comparaison automatique** de 7+ modèles ML
4. **Optimisation** des hyperparamètres
5. **Évaluation** avec métriques détaillées
6. **Test interactif** avec exemples personnalisés

## Visualisations Incluses

- Distribution des émotions (graphiques interactifs)
- Nuages de mots par émotion
- Analyse des mots les plus fréquents
- Matrices de confusion
- Métriques de performance

## Modèles Comparés

- Régression Logistique
- Naive Bayes
- Random Forest
- SVM
- Decision Trees
- K-Nearest Neighbors
- XGBoost

## Prochaines Étapes

1. **Résoudre les imports** (solutions ci-dessus)
2. **Exécuter les cellules** en séquence
3. **Analyser les résultats**
4. **Tester avec vos données**
5. **Déployer en production**

## Avantages de PyCaret

- **Low-code** : Peu de code pour beaucoup de fonctionnalités
- **Automatisation** : Preprocessing, feature engineering automatiques
- **Comparaison** : Teste plusieurs modèles en une ligne
- **Optimisation** : Hyperparameter tuning automatique
- **Déploiement** : Intégration cloud simplifiée
- **Visualisations** : Graphiques intégrés

## Ressources Supplémentaires

- [Documentation PyCaret](https://pycaret.org/)
- [Tutoriels NLP PyCaret](https://pycaret.org/nlp/)
- [Exemples GitHub](https://github.com/pycaret/pycaret)

---

**Le projet est prêt ! Il suffit de résoudre les problèmes d'imports pour commencer l'analyse.**
