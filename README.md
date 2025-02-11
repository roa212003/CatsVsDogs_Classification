# Classification des Images : Chiens vs Chats avec CNN

## Description du Projet
Ce projet utilise un réseau de neurones convolutif (CNN) pour classifier des images de chiens et de chats. L'objectif est de construire un modèle capable de distinguer efficacement ces deux catégories à partir d'un ensemble de données d'images.

## Fonctionnalités
- **Prétraitement des données** : Chargement, redimensionnement et normalisation des images pour une meilleure performance du modèle.
- **Construction du modèle CNN** : Architecture avec plusieurs couches convolutives et fully connected pour extraire et apprendre les caractéristiques visuelles des images.
- **Entraînement et validation** : Optimisation du modèle avec des techniques de régularisation telles que Dropout pour éviter le surapprentissage.
- **Évaluation** : Test du modèle sur un ensemble de données de validation pour calculer l'efficacité de la classification.
- **Visualisation des résultats** : Affichage des performances du modèle, y compris la précision et la matrice de confusion.

## Résultats
Le modèle atteint une précision de 77 % sur l'ensemble de test. Des améliorations potentielles incluent l'augmentation des données, l'optimisation de l'architecture du modèle et l'utilisation de techniques avancées telles que la fine-tuning de réseaux pré-entraînés.

## Prérequis
- Python 3.x
- Bibliothèques nécessaires : TensorFlow, Keras, NumPy, Matplotlib
