# Cartographie des Aires d'Accueil en Ille-et-Vilaine

Ce projet utilise l'API OpenStreetMap pour cartographier les aires d'accueil dans le département d'Ille-et-Vilaine en France. Le script en R interroge les données OSM et les visualise sur une carte interactive avec le package `leaflet`.

## Prérequis

- R (version 4.0 ou supérieure)
- Les packages R suivants : `osmdata`, `leaflet`

## Installation des Packages

Vous pouvez installer les packages nécessaires en exécutant les commandes suivantes dans votre console R :

```r
install.packages("osmdata")
install.packages("leaflet")
```

## Exécution du Script

Pour exécuter le script, ouvrez le fichier `aire_accueil_ille_et_vilaine.R` dans RStudio ou un autre environnement R, puis exécutez toutes les lignes de code. La carte interactive s'affichera dans le visualiseur de votre environnement R.

## Résultat

Le script interroge les données OpenStreetMap pour les aires d'accueil (`caravan_site`) dans le département d'Ille-et-Vilaine et les visualise sur une carte interactive.

## Auteurs

- [arthurb35](https://github.com/arthurb35)

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
