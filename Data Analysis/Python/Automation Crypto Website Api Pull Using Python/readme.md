# Projet d'Automatisation : Extraction de Données de Crypto-monnaies

## Introduction

Ce projet utilise Python pour extraire les données des crypto-monnaies à partir de l'API de CoinMarketCap. L'objectif est de récupérer les dernières informations sur les crypto-monnaies, de les transformer pour l'analyse et de les visualiser.

## Étapes du Projet

1. **Connexion à l'API** : Nous nous connectons à l'API de CoinMarketCap et récupérons les dernières données des crypto-monnaies. Les données sont ensuite converties en format JSON.

2. **Transformation des Données** : Nous transformons les données JSON en un DataFrame pandas pour une manipulation plus facile des données. Un timestamp est également ajouté pour chaque ligne de données pour suivre quand les données ont été collectées.

3. **Préparation des Données pour l'Analyse** : Nous préparons les données pour l'analyse. Les colonnes sont renommées pour une meilleure lisibilité.

4. **Visualisation des Données** : Nous visualisons les données. Un graphique à points est créé pour visualiser les changements de pourcentage des différentes crypto-monnaies. Ensuite, un graphique linéaire est créé pour visualiser l'évolution du prix du Bitcoin.

5. **Automatisation de l'Extraction des Données** : Nous automatisons l'extraction des données de l'API de CoinMarketCap. Le script est configuré pour s'exécuter 333 fois par jour (qui est la limite maximale pour une journée) et ajoute les nouvelles données au fichier CSV à chaque exécution. Un délai d'une minute est ajouté entre chaque exécution pour éviter de dépasser les limites de l'API.
