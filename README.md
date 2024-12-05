
<!-- README.md is generated from README.Rmd. Please edit that file -->

# NebRUG 2024

<!-- badges: start -->

<!-- badges: end -->

Sign up to the Nebraska R User Group on
[meetup](https://www.meetup.com/neb-rug/?eventOrigin=event_home_page).

``` r
library(calendR)
#> ~~ Package calendR
#> Visit https://r-coder.com/ for R tutorials ~~
calendR(year = 2024,
        start = "M",
        special.days = c(9, 19, 56, 79, 102,  # Days to color
                         126, 257, 300, 342),
        special.col = "lightblue",            # Color of the specified days
        low.col = "white") # Start the week on Monday
```

![](README_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->
