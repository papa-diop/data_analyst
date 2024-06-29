# Projet de nettoyage de données avec SQL

Ce projet utilise SQL pour nettoyer un ensemble de données sur les licenciements. Voici les étapes suivies :

1. Sélection de toutes les données de la table `layoffs`.
2. Création d'une table `layoffs_staging` identique à la table `layoffs`.
3. Insertion de toutes les données de la table `layoffs` dans la table `layoffs_staging`.
4. Suppression des doublons en utilisant la fonction `row_number()` pour attribuer un numéro de ligne unique à chaque ligne, puis suppression des lignes ayant un numéro de ligne supérieur à 1.
5. Standardisation des données en supprimant les espaces blancs inutiles et en uniformisant certaines valeurs.
6. Gestion des valeurs nulles ou vides en les remplaçant par des valeurs appropriées ou en supprimant les lignes contenant ces valeurs.
7. Suppression de toute colonne inutile.

N'oubliez pas de remplacer les noms de table et de colonne par ceux de votre choix. De plus, ce projet suppose que vous avez déjà installé un système de gestion de base de données SQL, comme MySQL ou PostgreSQL.
