# Diablo 3 statistics

Collection of scripts tackling various statistics in Diablo 3

## Contents

### primals

Visualizing what are your chances of obtaining primal items

## Reading

These articles are published on a subsite of [shitcoin.ninja](https://d3.shitcoin.ninja) , but you can read them [directly from project directory](https://github.com/PPFilip/d3/blob/main/out/) - just select a .md notebook of interest and open it.

## Building output

If you want to build files yourself, I suggest you use

```r
install.packages("ezknitr")
library(ezknitr)
ezknit(file = 'primals.Rmd', out_dir = 'out')
```

In order to properly send output to a directory of your choice.
