
<!-- README.md is generated from README.Rmd. Please edit that file -->

# stats101verse

The stats101verse organization exists to explore how new, pedagogically
motivated statistical packages may be used in introductory statistics
and probability curriculum.

ggplot2 extensions plays a central role among the packages, given the
accessibility of visuals and given the step-by-step process that ggplot2
uses in building data visualizations. The step-by-step graphical
construction framework allows exposition and discussion of statistical
topics that is unparalleled by other graphics tools.

Beyond ggplot2 extension packages, data frame manipulation tools like
‘tidybernoulli’ allow for a computationally friendly approach to
probabalistic branching of repeated, independent trials.

Within the ggplot2 extensions, there’s a notable use of the stamp\_\*
prefix which ggplot2 users may not find familiar. stamp\_\* functions
provide annotation layers in concise and easy-to-use functions, but the
syntax is not native to base ggplot2.

<!-- badges: start -->

<!-- badges: end -->

The goal of .github is to …

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/v1/examples>.

You can also embed plots, for example:

![](README_files/figure-gfm/pressure-1.png)<!-- -->

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub.
