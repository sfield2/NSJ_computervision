# <kbd>[**Button Text**](https://example.com/)</kbd>

# Research compendium for Field and Dean (under revision)
This R- and Python-based research compendium supports a semi-autonomous computer vision survey of the Northern San Juan for detecting archaeological sites.

# Overview
There are two main scripts fieldanddean2026.qmd and fieldanddean2026.ipny. The first is a Quarto markdown document that includes code to perform all of the data scraping and image creation steps reported in the manuscript. The second is a Jupyter Notebook that includes code to perfrom the computer vision training and deployment.

fieldanddean2026.qmd performs the following steps:
1. Import `R` and `Python` dependencies
2. Import custom R-functions and establish directories
3. Import Study Region Shapefiles
4. Import Elevation Data
5. Train PyTorch Classifier on Training Data (MVNP Sites)
6. Deploy PyTorch Classifier

# Directory Strucutre
1. `FieldandDean2026.qmd`: `R` and `Python` scripts to conduct analyses
2. DATA/: Directory containing un-processed datasets used in the analysis. Not archived on Github, as many of these data are quite large.
4. FIGURES/: Directory containing low resolution figures used in the manuscript.
5. TABLES/: Directory containing tabular outputs used in the manuscript.
6. README.Rmd: This `README` file

# Citation
When using the code included in this research compenidum, please cite all of the following:

Field, S and L. Dean. A Computer Vision Survey of the Northern San Juan and the Case for Image Classification in Archaeology. American Antiquity, In review.

Field, S and L. Dean. Research compendium for: Computer Vision Survey of the Northern San Juan and the Case for Image Classification in Archaeology, 2026. Version 1.0.0. Zenodo. [DOI]

# Requirements
This analysis requires R (≥ 4.2.0) and the following packages:
`sf`  `terra`  `ggplot2`  `tidyterra`  `dplyr`  `tidyverse` `elevatr` `whitebox` `giscoR` `ggnewscale` `ggblend` `magick` `stringr` `filesstrings` `purrr`

This analysis also requires `Python` (≥3.11.6) and the following libraries:
`os` `splitfolders` `torch` `torch.nn` `torch.optim` `torchvision` `torchvision.transforms` `timm` `csv` `matplotlib.pyplot` `pandas` `numpy` `sys` `tqdm` `PIL`
Ensure
