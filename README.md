# MolEco-MEC-24-1288

### Supplemental code materials for manuscript MEC-24-1288

[![DOI](https://zenodo.org/badge/915016816.svg)](https://doi.org/10.5281/zenodo.14791361)

This repository contains the codebook used for analyses in the publication. The four parts of the codebook correspond to the headers in the Methods section.

View the published codebook at this GitHub Pages [link](https://trklab-metabarcoding.github.io/MolEco-MEC-24-1288/).

The Quarto project containing the source code notebooks is available in this repository in the `geocodebook` directory. The empty `data/` directory can be used when running code notebooks locally with Supplemental Data files, available [here]().

### Software Requirements

We used R version 4.3.2 and RStudio 2024.12.1+563 to run the analysis and generate the codebook.

[`GDAL`](https://gdal.org/en/stable/) is required as a system dependency. This may also require setting the "PROJ_LIB" and "GDAL_HOME" environment variables for your system.

We used the R `pacman` package that will install R packages if necessary and then load the package libraries, all in the same call. The following R packages will install when running the notebooks: - `BiocManager` - `sangerseqR` - `bold` - `taxize` - `maps` - `ggplot2` - `dplyr` - `countrycode` - `data.table` - `raster` - `rgbif` - `mapproj` - `sf` - `glue` - `terra` - `usethis` - `stringr` - `curl` - `zip` - `readr` - `units` - `rnaturalearth` - `rnaturalearthdata` - `rnaturalearthhires` - `wesanderson` - `tictoc` - `beepr` - `crsuggest` - `reporter`
