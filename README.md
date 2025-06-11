# ENVS-193DS_spring-2025_final

## General Information

The data is from Kui, L. 2024. Daily sea surface temperature in Santa Barbara channel between 1982 and 2023 ver 3. Environmental Data Initiative. https://doi.org/10.6073/pasta/e930954949b2635928b8be6824630f84. Accessed 2025-06-10. and from Stojanovic, Dejan; Owens, Giselle; Young, Catherine et al. (2021). Do nest boxes breed the target species or its competitors? A case study of a critically endangered bird [Dataset]. Dryad. https://doi.org/10.5061/dryad.83bk3j9sb.

This repository is for my workflow for completing the final for ENVS 193DS.

### Packages
```
library(tidyverse) # general use
library(here)      # file organization
library(MuMIn)     # choosing best model
library(janitor)   # cleaning data frames
library(DHARMa)    # running model diagnostics
library(lubridate) # cleaning up dates
library(ggeffects) # model predictions
```
## Data and File Information

File Structure:

```
.
├── ENVS-193DS_spring-2025_final.Rproj
├── README.md
├── code                                            # code folder
    ├── Final.html                                  # rendered html
    ├── Final.qmd                                   # quarto document
├── data                                            # data folder
    ├── SST_update2023.csv                          # sst data file
    └── occdist.csv                                 # Swift Parrot data file

```

All code is in the `code` folder. The code cleans and aanalyzes data and builds, runs, and visualizes models.

## Rendered Output

The rendered output is [here](https://eliasdewald.github.io/ENVS-193DS_spring-2025_final/code/Final.html).