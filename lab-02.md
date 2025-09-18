Lab 02 - Plastic waste
================
Lara Prodanovic
18/09/2025

## Questions Warm up

Quelles sont les quatre zones présentes sur RStudio ?

- Les quatre zones qui constituent la fenêtre RStudion sont les
  suivantes : une zone ‘source’ où l’on peut retrouver le code sur
  lequel on travaille, une zone ‘environnement’ où l’on retrouve
  notamment les options pour le Git, une zone ‘console’ avec la console
  et le terminal et une dernière zone où l’on retrouve les différents
  fichiers en rapport avec notre projet ainsi que d’autres
  fonctionnalités.

Combien y a-t-il d’observations dans le jeu de données ?

- En regardant la zone ‘environnement’ on peut voir qu’il y a 240
  observations dans le jeu de données

En regardant les données, vous voyez que certaines cellules ont comme
valeurs NA. Que cela signifie-t-il ?

- N/A signifie ‘Non Applicable’. Cela veut surement dire que les
  informations en question manquent et ne peuvent donc pas être ajoutées
  au jeu de données.

## Chargement des packages et des données

``` r
library(tidyverse) 
```

``` r
plastic_waste <- read_csv("data/plastic-waste.csv")
```

Commençons par filtrer les données pour retirer le point représenté par
Trinité et Tobago (TTO) qui est un outlier.

``` r
plastic_waste <- plastic_waste %>%
  filter(plastic_waste_per_cap < 3.5)
```

## Exercices

### Exercise 1

``` r
# insert code here
```

### Exercise 2

``` r
# insert code here
```

Réponse à la question…

### Exercise 3

Boxplot:

``` r
# insert code here
```

Violin plot:

``` r
# insert code here
```

Réponse à la question…

### Exercise 4

``` r
# insert code here
```

Réponse à la question…

### Exercise 5

``` r
# insert code here
```

``` r
# insert code here
```

Réponse à la question…

## Conclusion

Recréez la visualisation:

``` r
# insert code here
```
