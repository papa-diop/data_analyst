# Projet de nettoyage de données avec Pandas

Ce projet utilise la bibliothèque Pandas pour nettoyer un ensemble de données de clients. Voici les étapes suivies :

1. Lecture du fichier Excel contenant les données des clients.
2. Création d'une copie du DataFrame original.
3. Suppression de la colonne inutile "Not_Useful_Column".
4. Nettoyage de la colonne "Last_Name" en supprimant les caractères indésirables.
5. Nettoyage de la colonne "Phone_Number" en supprimant les caractères indésirables.
6. Séparation de la colonne "Address" en plusieurs colonnes : "Street_Address", "State" et "Zip_Code".
7. Remplacement des valeurs 'Yes' et 'No' par 'Y' et 'N' respectivement dans la colonne "Do_Not_Contact".
8. Remplacement des valeurs manquantes par une chaîne vide.
9. Suppression des lignes où "Do_Not_Contact" est 'Y' ou vide.
10. Réinitialisation de l'index du DataFrame.

N'oubliez pas de remplacer le chemin du fichier Excel par le chemin de votre fichier. De plus, ce projet suppose que vous avez déjà installé la bibliothèque `pandas`. Si ce n'est pas le cas, vous pouvez l'installer en utilisant la commande `pip install pandas` dans votre terminal.
