# A Tale of Two Belongings

**Subtitle**: Exploring Social and Academic Belonging in University Students  
**Author**: Delwin Carter  
**Date**: June 21, 2025  

## Overview
- **Purpose**: This study employs Latent Class Analysis (LCA) to identify distinct profiles of social and academic belonging among 837 university students using polytomous (categorical) survey responses.
- **Findings**: Four unique profiles emerged: High Social, High Academic; Low Social, High Academic; High Social, Low Academic; and Low Social, Low Academic.
- **Implications**: Demonstrates the pivotal role of academic belonging in academic success and the joint impact of both belonging types on emotional well-being (GPA, self-esteem, stress).
- **Application**: Provides a roadmap for educators and researchers to develop tailored interventions using LCA with polytomous data.

[TOC]

---

## Introduction

This project leverages Latent Class Analysis (LCA) to uncover distinct profiles of social and academic belonging among university students. Unlike previous studies that combined these dimensions, we identify four unique profiles and analyze their predictive power on key outcomes (GPA, self-esteem, stress). The findings offer actionable insights for supporting student success through targeted interventions.

---

## Project Structure

- **`Belonging.qmd`**: Main Quarto document for analysis and visualization.
- **`A Tale of Two Belongings.pdf`**: Compiled report of the study.
- **`Belonging_files/`**: Supporting files (e.g., figures, data).
- **`figures/`**: Directory for generated plots and diagrams.
- **`data/`**: Contains the SPSS dataset.
- **`3step/`, `functions/`, `enum2/`, `enum/`**: Analysis submodules.

---

## Methodology

### Latent Class Analysis Model Visualization

This section visualizes the LCA model using a directed graph, illustrating the relationships between polytomous indicators (social and academic belonging), covariates (e.g., gender, ethnicity), and distal outcomes (GPA, self-esteem, stress).

![LCA Model](figures/lca_model.png)  
*Figure: Directed graph of the LCA model structure.*

---

## Dependencies

The analysis relies on the following R packages:
- `tidyverse`
- `haven`
- `glue`
- `MplusAutomation`
- `here`
- `janitor`
- `gt`
- `cowplot`
- `DiagrammeR`
- `webshot2`
- `stringr`
- `flextable`
- `officer`
- `dplyr`
- `tidyr`

To reproduce the analysis, install these packages in R using `install.packages("package_name")`.