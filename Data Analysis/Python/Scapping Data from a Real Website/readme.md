# Projet d'extraction de données de tableau avec BeautifulSoup et Pandas

Ce projet utilise les bibliothèques BeautifulSoup et pandas pour extraire des données à partir d'un tableau sur une page Wikipedia et les enregistrer dans un fichier CSV. Voici les étapes suivies :

1. Utilisation de BeautifulSoup pour trouver le tableau dans le contenu HTML de la page.
2. Extraction des titres de colonnes du tableau.
3. Création d'un DataFrame pandas vide avec les titres de colonnes extraits.
4. Extraction des données de chaque ligne du tableau et ajout de ces données au DataFrame.
5. Enregistrement du DataFrame dans un fichier CSV.

N'oubliez pas de remplacer l'URL et le chemin du fichier CSV par ceux de votre choix. De plus, ce projet suppose que vous avez déjà installé les bibliothèques `beautifulsoup4`, `requests` et `pandas`. Si ce n'est pas le cas, vous pouvez les installer en utilisant la commande `pip install beautifulsoup4 requests pandas` dans votre terminal.
