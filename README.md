# tabnet.fr

<!-- badges: start -->

<!-- badges: end -->

Le paquet d'internationalisation de **{tabnet}** en français (fr_FR)

## Installation

Vous pouvez installer la version de development de **{tabnet.fr}** depuis [GitHub](https://github.com/) via:

``` r
# install.packages("pak")
pak::pak("cregouby/tabnet.fr")
```

## Exemple

Voici comment utiliser {tabnet} avec l'aide en français :

``` r
# configure la session en langue française
Sys.setenv(LANGUAGE = "fr")

# charge la librairie d'aide de tabnet en traduction française, et {tabnet}
library(tabnet.fr)
library(tabnet)

# consulte l'aide normalement
?autoplot.tabnet_explain
```

![exemple de page de documentation en français dans l'onglet Help de RStudio](images/clipboard-3497452233.png)
