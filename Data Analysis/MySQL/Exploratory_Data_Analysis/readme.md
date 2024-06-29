Il semble que vous souhaitiez documenter un processus d'analyse exploratoire de données (AED) SQL dans votre fichier `readme.md`. Voici comment vous pouvez structurer cela sans les extraits de code :

```markdown
# Projet d'analyse exploratoire de données avec SQL

Ce projet utilise SQL pour effectuer une analyse exploratoire de données sur un ensemble de données sur les licenciements. Voici les étapes suivies :

1. Sélection de toutes les données de la table `layoffs_staging2`.
2. Calcul des valeurs maximales des colonnes `total_laid_off` et `percentage_laid_off`.
3. Sélection des données où `percentage_laid_off` est égal à 1, triées par `funds_raised_millions` en ordre décroissant.
4. Agrégation des données par entreprise et calcul du total des licenciements pour chaque entreprise.
5. Calcul des dates minimale et maximale dans la colonne `date`.
6. Agrégation des données par industrie et calcul du total des licenciements pour chaque industrie.
7. Agrégation des données par année et calcul du total des licenciements pour chaque année.
8. Calcul de la progression des licenciements en calculant le total cumulé des licenciements pour chaque mois.
9. Agrégation des données par entreprise et par année, et calcul du total des licenciements pour chaque combinaison entreprise-année.
10. Classement des entreprises par année en fonction du total des licenciements, et sélection des cinq premières entreprises pour chaque année.

N'oubliez pas de remplacer les noms de table et de colonne par ceux de votre choix. De plus, ce projet suppose que vous avez déjà installé un système de gestion de base de données SQL, comme MySQL ou PostgreSQL.
```
