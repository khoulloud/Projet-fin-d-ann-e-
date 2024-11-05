# Projet de Fin d'Année : Prédiction du Cancer Colorectal avec Machine Learning et Deep Learning

Ce projet de fin d'année consiste à développer un modèle de prédiction du cancer colorectal en utilisant des techniques de Machine Learning et Deep Learning, axé sur le traitement d'images médicales. Ce modèle utilise des réseaux de neurones convolutionnels (CNN), le transfert d'apprentissage avec UNet, ainsi qu'un autoencodeur pour la segmentation et le prétraitement des images. Une interface interactive est développée avec Streamlit pour la visualisation des résultats de prédiction.

## Sommaire

- [Aperçu du projet](#aperçu-du-projet)
- [Contenu du projet](#contenu-du-projet)
- [Technologies utilisées](#technologies-utilisées)
- [Objectifs](#objectifs)
- [Installation](#installation)
- [Utilisation](#utilisation)

## Aperçu du projet

Le projet se concentre sur la prédiction de cancer colorectal à partir d'images médicales, avec des modèles de Machine et Deep Learning pour optimiser la segmentation et la précision des prédictions. Le pipeline complet comprend l'exploration et le prétraitement des données, la modélisation, et la mise en place d'une interface pour les utilisateurs.

## Contenu du projet

- **Exploration et Prétraitement des Données** : Analyse exploratoire, nettoyage et normalisation des images pour une meilleure qualité de données.
- **Modélisation** : Mise en œuvre de modèles CNN et d'un transfert d'apprentissage avec UNet pour la segmentation de polypes.
- **Autoencodeur** : Utilisation d'un autoencodeur pour débruiter et segmenter les images efficacement.
- **Framework Utilisé** : PyTorch est utilisé pour la conception, l'entraînement et l'optimisation des modèles.
- **Interface Utilisateur** : Développement d'une interface interactive avec Streamlit pour visualiser les prédictions et évaluer les résultats.

## Technologies utilisées

- **Langage** : Python
- **Frameworks** : PyTorch, Streamlit
- **Modèles de Deep Learning** : CNN, UNet, Autoencodeur
- **Outils de Visualisation** : Streamlit pour une interface utilisateur conviviale

## Objectifs

1. Améliorer la précision de la prédiction des risques de cancer colorectal grâce à l'analyse d'images.
2. Développer un pipeline complet allant de l'exploration des données à la visualisation des résultats.
3. Fournir une interface accessible pour permettre aux utilisateurs d'examiner et d'interpréter les prédictions.

## Installation

1. Cloner ce dépôt :
    ```bash
    git clone https://github.com/votre-utilisateur/projet-fin-d-annee.git
    ```
2. Installer les dépendances :
    ```bash
    pip install -r requirements.txt
    ```

## Utilisation

Lancer l'interface Streamlit pour visualiser les résultats de prédiction :

```bash
streamlit run app.py
