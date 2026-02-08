# Research compendium for Field and Dean (under revision)
This R- and Python-based researchcompendium supports an semi-autonomous computer vision survey of the Northern San Juan for detecting archaeological sites.

# Overview
There are two main scripts fieldanddean2026.qmd and fieldanddean2026.ipny. The first is a Quarto markdown document that includes code to perform all of the data scraping and image creation steps reported in the manuscript. The second is a Jupyter Notebook that includes code to perfrom the computer vision training and deployment.

fieldanddean2026.qmd performs the following steps:
1. 
2.
3.

fieldanddean2026.qmd performs the followings teps:

# Directory Strucutre
1. fieldanddean2026.qmd:
2. fieldanddean2026.ipny:
3. data-raw/: Directory containing un-processed datasets used in the analysis. Not archived on Github, as many of these data are quite large.
4. data-derived/: Directory containing processed datasets created in the analysis.
5. figures/: Directory containing figures used in the manuscript.
6. tables/: Directory containing tabular data used in the manuscript.
7. README.Rmd

# Citation
When using the code included in this research compenidum, please cite all of the following:

Field, S and L. Dean. A Computer Vision Survey of the Northern San Juan and the Case for Image Classification in Archaeology. American Antiquity, In review.

Field, S and L. Dean. Research compendium for: Computer Vision Survey of the Northern San Juan and the Case for Image Classification in Archaeology, 2026. Version 1.0.0. Zenodo. [DOI]

# Requirements
This analysis requires R (≥ 4.2.0) and the following packages:
`sf`
'terra','ggplot2','tidyterra','dplyr','tidyverse',
             'elevatr','whitebox','giscoR','ggnewscale','ggblend',
             'magick','stringr','filesstrings','purrr')

Ensure
