# tabnet.fr

<!-- badges: start -->

<!-- badges: end -->

Le paquet d'internationalisation de **{tabnet}** en français (fr_FR)

## Installation

Vous pouvez installer la version de development de **{tabnet.fr}** depuis [GitHub](https://github.com/) via:

``` r
# install.packages("devtools")
devtools::install_github("eliocamp/rhelpi18n")
devtools::install_github("cregouby/tabnet.fr")
```

## Exemple

Voici comment utiliser {tabnet} avec l'aide en français :

``` r
# configure la session en langue française
Sys.setenv(LANGUAGE = "fr")

# charge la librairie tabnet en traduction française
library(tabnet.fr)

# consulte l'aide normalement
??autoplot.tabnet_explain
```

![exemple de page de documentation en français dans l'onglet Help de RStudio](images/clipboard-3497452233.png)
