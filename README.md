# ISyE-6414-Regression-Modelling
# ISyE-6414 Regression Modelling

This repository contains the final project materials for **ISyE 6414** focused on regression modelling with a NASA near-Earth comet dataset.

## Project Overview

The project investigates how orbital elements can be used to model and predict comet-related response variables (including MOID-related outcomes) using linear and regularized regression approaches.

Core tasks shown in the notebooks include:
- Data loading and cleaning.
- Missing-value assessment and feature removal decisions.
- Outlier screening using z-scores.
- Exploratory visualization of orbital relationships.
- Regression modelling and inference.

## Repository Structure

- `NASA Comet Dataset Prediction/code_MKT_06112024.Rmd`  
  Main analysis notebook with EDA, preprocessing, plotting, and regression modelling workflow.

- `NASA Comet Dataset Prediction/code_inference.Rmd`  
  Additional inference/modeling notebook.

- `NASA Comet Dataset Prediction/Near-Earth_Comets_-_Orbital_Elements_20240605.csv`  
  Source orbital-elements dataset.

- `NASA Comet Dataset Prediction/comet_data_cleaned.csv`  
  Cleaned dataset used for downstream modelling.

- `NASA Comet Dataset Prediction/ISyE6414_Project_06132024.html`  
  Rendered project output.

- `NASA Comet Dataset Prediction/ISYE6414_Group1_Presentation_06132024.pptx`  
  Project presentation slides.

- `NASA Comet Dataset Prediction/ISyE6414_Group#1_report_06192024.docx`  
  Written report.

## Authors

- Troy Allen
- Roy Gabriel
- Nattakorn Kittisut
- Corey Smith
- Moe Kyaw Thu

## How to Run the Analysis

1. Open either `.Rmd` file in RStudio.
2. Install required packages if missing. Packages referenced in the notebooks include:
   - `tidyverse`
   - `caret`
   - `glmnet`
   - `stargazer`
   - `ggplot2`
   - `dplyr`
   - `car`
   - `lmtest`
   - `faraway`
   - `MASS`
3. Ensure the CSV files are available in the paths expected by the notebook.
4. Knit the `.Rmd` document to HTML or run chunks interactively.

## Notes

- File paths in the notebooks are relative and assume execution from within the `NASA Comet Dataset Prediction/` directory.
- This repo includes both source files and submission artifacts (HTML, PPTX, DOCX) for reproducibility and documentation.
