# Historical horse population in Canada
[Report](doc/hist_horse_pop.md) that explores the historical population of horses in Canada between 1906 and 1972 per province.

## Dependencies:
- R and R packages:
  - tidyverse
  - knitr
  - here

## Instructions to reproduce report:
1. clone or download this repository
2. open RStudio and set this project root as the working directory
3. Open `doc/hist_horse_pop.md` and click the "knit" button. `source("plot_horses.R")` or run the script interactively through the editor **or** install the `ezknitr` package and type: `ezknitr::ezknit("doc/hist_horse_pop.Rmd", out_dir = "doc", keep_html = FALSE)`
