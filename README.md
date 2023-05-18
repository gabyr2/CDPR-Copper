# CDPR-Copper

This repository is for code used for exploratory data analyses and specific figure-making of a large dataset of pesticide applications.  The dataset contains all copper-based pesticide applications made from 2008 through 2018 in California, and was queried from the California Department of Pesticide Regulation's (CDPR) Pesticide Information Portal (CalPIP, https://calpip.cdpr.ca.gov/main.cfm).

Initially, this work was done for a class's final project, DATA_SCI 7040.  Work was conducted in Jupyter and was saved initially as a notebook file.  The following code was used to convert it into an R script.

> library(rmarkdown)
> convert_ipynb(input = "C:/Users/gidge/OneDrive - University of Missouri/PhD Thesis Files/Data/CDPR Copper/L8_Exercise.ipynb")

4 Jan 2023: Made repo, pushed code to GitHub, ensured functionality.  Code requires clean-up.

### Notes About Data
Spatial data are saved in the repo.  
- The folder `ca_air_basins` contains spatial files for the polygons of the Air Basins of California.
- The folder `Statewide_CA_PLSS_NAD83AlbersCA` contains spatial files for the PLSS data.

CDPR data are *NOT* saved in the repo.
- File name: `CalPIP_Cu_2008-2021.csv`
- The file is too large for github (>100MB).
- It is saved on the external hard drive: `D:/LocalRepos/CDPR-Copper_ExternalData`