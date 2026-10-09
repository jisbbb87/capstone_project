# capstone_project
The project consists of codes used of analysis of tb data on R studio. 
# R Capstone Project: Clinical Parameters of TB Patients

Capstone project for my R data analysis course. It analyses clinical parameters of tuberculosis (TB) patients and presents the work as a Quarto report.

**Author:** Jishnu Sathees Lalu

## Objective

Clean messy data 
Do basic analysis
conduct advance analysis

## Contents

| File | Description |
|------|-------------|
| `Capstone Analysis.qmd` | Quarto source: code and narrative |
| `capstone Analysis.html` | Rendered report |

## Data

- Source: Aswath Karunakaran
- Format: Excel file, loaded in R as the object `tb`
- Variables: [key clinical parameters, e.g. age, sex, weight, delay in assessment, abnormal parameters, specialist consulation]

The dataset is **not included** in this repository because it contains patient-level clinical data.

## Methods

- [Data cleaning and recoding steps]
- [Descriptive statistics]
- [Statistical tests or models used]

## How to reproduce

1. Install [R](https://cran.r-project.org/), [RStudio](https://posit.co/download/rstudio-desktop/) and [Quarto](https://quarto.org/).
2. Install the required packages:

   ```r
   install.packages(c("tidyverse", "readxl"))  # [edit to match your report]
   ```

3. Place the dataset in the project folder.
4. Open the `.qmd` file in RStudio and click **Render**.

## Tools

R, RStudio, Quarto [add packages used]
