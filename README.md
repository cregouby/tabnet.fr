# tabnet.fr

<!-- badges: start -->

<!-- badges: end -->

Le paquet d'internationalisation de {tabnet} en français (fr_FR)

## Installation

Vous pouvez installer la version de development de tabnet.fr depuis [GitHub](https://github.com/) via:

``` r
# install.packages("devtools")
devtools::install_github("eliocamp/rhelpi18n")
devtools::install_github("cregouby/tabnet.fr")
```

## Example

Voici comment obtenir l'aide de {tabnet} en français :

``` r
# configure la session en langue française
Sys.setenv(LANGUAGE = "fr")

# charge la librairie de traduction puis tabnet par sa traduction française
library(rhelpi18n)
library(tabnet.fr)

# consulte l'aide normalement
??autoplot.tabnet_explain
```

![exemple de page de documentation en français dans RStudio](images/clipboard-3497452233.png)
