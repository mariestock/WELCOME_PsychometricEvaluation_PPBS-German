# WELCOME_PsychometricEvaluation_PPBS-German

This repository contains materials related to the psychometric evaluation of the German 5-item Pre- and Postnatal Bonding Scale (PPBS) in the WELCOME trial.

It is provided for transparency and reproducibility of the reported analyses. It includes an annotated R/Jupyter notebook with the analysis code and explanatory notes, as well as supplementary materials referenced in the manuscript.

## Repository contents

- `PPBS_German_Psychometric_Evaluation_Annotated_Notebook.ipynb`  
  Annotated R/Jupyter notebook containing the analysis code used for the psychometric evaluation.

- `Supplementary_Materials/`  
  Additional supplementary tables and figures referenced in the manuscript.

## Data availability

The original WELCOME trial data and the original Dutch validation dataset are not included in this repository due to ethical and data protection restrictions. The repository contains analysis code and aggregated supplementary materials only.

To run the notebook locally, authorised users need to place the required data files in a local, non-versioned `data_raw/` folder and adapt the file paths if necessary.

## Software and analytic reproducibility

All analyses were conducted in R 4.5.0 (R Core Team, 2025) using RStudio Server Professional version 2025.09.2+418.pro4 (Posit team, 2025). The following R packages were used for data management, psychometric analyses, visualisation, and reporting: dplyr, ggplot2, haven, knitr, lavaan, lmtest, psych, purrr, RColorBrewer, semTools, tibble, tidyr, and vioplot. Analysis code is provided in the accompanying GitHub repository; trial data are not publicly shared due to ethical and data protection restrictions.

- Posit team. (2025). RStudio: Integrated Development Environment for R. In Posit Software, PBC. http://www.posit.co/
- R Core Team. (2025). R: A Language and Environment for Statistical Computing. In R Foundation for Statistical Computing. https://www.R-project.org/
