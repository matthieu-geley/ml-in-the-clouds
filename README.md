# ml-in-the-clouds : Machine Learning

## Contexte du projet
Dans un contexte marqué par l’essor de l’intelligence artificielle, le Machine Learning as a Service (MLaaS) permet d’accéder facilement à la puissance du machine learning via des services cloud. Ce projet vise à explorer ces solutions, notamment l’AutoML, à travers une application concrète en traitement automatique du langage naturel (NLP).

## Objectif du projet
L’objectif est de tester des outils AutoML (comme PyCaret et des plateformes MLaaS telles que Google Vertex AI, AWS SageMaker, Azure ML ou DataRobot) pour construire, évaluer et déployer un modèle de classification permettant d’identifier au moins 6 émotions dans des textes narratifs écrits.

## Veille technologique : AutoML et MLaaS
### AutoML – Définition et avantages

L’AutoML (Automated Machine Learning) désigne l’automatisation du processus de création de modèles de machine learning. Cela comprend :

Le nettoyage et le prétraitement des données,

La sélection et l’entraînement de modèles,

L’optimisation des hyperparamètres,

L’évaluation et le déploiement.

Avantages de l’AutoML :

Gain de temps : réduit considérablement la durée des projets ML.

Accessibilité : permet à des non-experts d’obtenir des résultats performants.

Productivité : les data scientists peuvent se concentrer sur l’analyse métier.

Optimisation automatique : permet d’atteindre des performances compétitives.

MLaaS – Définition et avantages

Le Machine Learning as a Service (MLaaS) regroupe les services cloud proposant des outils et environnements pour exécuter des tâches de machine learning via des API, des interfaces web ou des SDK.

Avantages du MLaaS :

Pas d’infrastructure à gérer : tout est hébergé sur le cloud.

Scalabilité : capacité d’adapter automatiquement les ressources.

Outils intégrés : AutoML, visualisation, monitoring, MLOps.

Déploiement rapide : les modèles sont mis en ligne en quelques clics ou commandes.

Sécurité et maintenance assurées par les fournisseurs cloud.

Focus sur les principales plateformes MLaaS
1. Google Cloud Platform – Vertex AI
Intègre AutoML, entraînement personnalisé et déploiement dans un seul environnement.

Fonctionne avec BigQuery, Dataflow, TensorFlow, etc.

Permet la gestion du cycle de vie complet via Vertex Pipelines (MLOps).

Interface web + API + Jupyter Notebooks.

2. Amazon Web Services – SageMaker
Offre complète allant de la préparation des données au déploiement.

Inclut SageMaker Autopilot pour l’AutoML.

Outils collaboratifs (SageMaker Studio) et gestion des workflows (SageMaker Pipelines).

Forte intégration avec tous les services AWS.

3. Microsoft Azure – Azure Machine Learning
Propose des expériences code et low-code.

Support d’AutoML avec visualisation des modèles, pipelines visuels, ou Jupyter.

Intégration complète avec Azure Data Lake, Power BI.

Fonctionnalités avancées de MLOps : suivi des expériences, gestion des modèles, CI/CD.

4. DataRobot
Plateforme spécialisée 100% AutoML.

Ciblée pour les entreprises et les utilisateurs métiers.

Interprétabilité avancée des modèles (ex : Feature Impact, Shap values).

Déploiement et monitoring intégrés.

Moins flexible pour les cas très spécifiques ou sur mesure.