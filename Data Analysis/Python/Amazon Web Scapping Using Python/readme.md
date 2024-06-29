# Projet de Web Scraping sur Amazon

## Introduction

Ce projet utilise Python pour scraper les données des articles sur Amazon. L'objectif est de suivre les prix des articles et d'envoyer un email lorsque le prix descend en dessous d'un certain seuil.

## Bibliothèques Utilisées

- BeautifulSoup
- requests
- time
- datetime
- smtplib

## Processus

1. **Connexion au site web** : Une requête est envoyée à la page de l'article sur Amazon et le contenu de la page est récupéré.
2. **Extraction des données** : Le titre de l'article et le prix sont extraits à l'aide de BeautifulSoup.
3. **Création d'un timestamp** : Un timestamp est créé pour chaque extraction de données afin de suivre quand les données ont été collectées.
4. **Création d'un fichier CSV** : Un fichier CSV est créé et les données extraites sont écrites dans le fichier.
5. **Ajout de données au CSV** : Les données sont ajoutées au fichier CSV à chaque fois que le script est exécuté.
6. **Automatisation du processus** : Le script est configuré pour s'exécuter automatiquement après un certain temps et ajouter les nouvelles données au fichier CSV.
7. **Envoi d'un email** : Un email est envoyé lorsque le prix de l'article descend en dessous d'un certain seuil.
