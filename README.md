# Code and data for the manuscript "Multitrophic assembly: a perspective from modern coexistence theory"

# System requirements
- Software dependencies: R (has been tested with R version 4.2.2 ).
- Required R packages:
  - tidyverse (version 1.3.2)
  - deSolve (version 1.0.1)
  - geomtextpath (version 0.1.1)
  - patchwork (version 1.1.0)
  - reticulate (version 1.28)
- Required non-standard hardware: none.

# Repository contents
- `Reproduce.qmd`. The main file (in [Quarto](https://quarto.org/)) to reproduce the results of the manuscript. It contains the code to reproduce the figures of the manuscript. 
- `Reproduce.html`. The html file provides an easy-to-read version of the main file.
- `LV_multi_functions.py` and `numerical_NFD.py`. Companion python file to `Reproduce.qmd`. It contains the functions to compute niche and fitness differences in Lotka-Volterra dynamics.
- `Data` dircetory. Contains the empirical data used in the manuscript. This data are from [Sauve & Barraquand 2020](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2656.13227).