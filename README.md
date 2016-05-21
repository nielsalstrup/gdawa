<!-- README.md is generated from README.Rmd. Please edit that file -->
gdawa
=====

**gdawa** makes it easy to retrieve geocoding data from Danmarks Adressers Web API - [DAWA](https://dawa.aws.dk/).

``` r
library(gdawa)

us <- c(left = -125, bottom = 25.75, right = -67, top = 49)
map <- get_stamenmap(us, zoom = 5, maptype = "toner-lite")
ggmap(map)
```



``` r
ggmap(map, extent = "device")
```




Installation
------------

-   From CRAN: `install.packages("gdawa")`

-   From Github: `devtools::install_github("nielsalstrup/gdawa")`
