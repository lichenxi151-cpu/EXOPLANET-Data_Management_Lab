# Exoplanet & Stellar Systems Data Management Lab

An exploratory data analysis of an exoplanetary system consisting of 866 planets and 561 host stars using R and the Tidyverse ecosystem.

## Key Analysis Highlights
- **Data Integrity & Ingestion**: Validated dataset dimensions and numeric data types with `readr` and `dplyr`.
- **Relational Data Joins**: Merged planetary physical characteristics with host star spectral types via `inner_join`.
- **Multivalued Column Reshaping**: Expanded composite strings (climates and terrains) into tidy rectangular data using `tidyr::separate_longer_delim`.
- **Data Visualization**: Generated distributions, boxplots (log10 scaled), and scatter plots using `ggplot2`.

## Tech Stack
- **Language**: R
- **Packages**: `readr`, `dplyr`, `tidyr`, `ggplot2`
- **Tooling**: Quarto (`.qmd`), RStudio Project (`.Rproj`)
