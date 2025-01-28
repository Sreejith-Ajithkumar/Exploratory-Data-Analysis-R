# Exploratory Data Analysis with R

## Overview
This repository contains all the necessary files and instructions to perform exploratory data analysis on a dataset related to school board achievements in Ontario. The analysis is carried out using **Base R**, with no additional packages required.

---

## Repository Structure
- **`Exploratory_Sreejith.Rmd`**: The R Markdown file containing the R code, comments, and answers to the analysis questions.
- **`Exploratory_Sreejith.pdf`**: The rendered PDF output of the R Markdown file, displaying results and analysis.
- **`PROG8430-25W-Assign01.txt`**: The dataset used for analysis. Ensure this file is in the same directory as the `.Rmd` file.
- **`README.md`**: This instruction file, explaining how to set up and run the project.

---

## Prerequisites

1. **Install R**: You can download it from [CRAN](https://cran.r-project.org/).
2. **Install RStudio**: Download RStudio Desktop from [Posit](https://posit.co/download/rstudio-desktop/).

This project uses **Base R functionality**, so there’s no need to install additional packages.

---

## How to Run the Project

1. **Clone or Download the Repository**:
   - Clone the repository using:
     ```bash
     git clone https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
     ```
   - Or, download the repository as a ZIP file and extract it.

2. **Open the R Markdown File**:
   - Launch **RStudio**.
   - Open the `Exploratory_Sreejith.Rmd` file in RStudio.

3. **Ensure the Dataset is Accessible**:
   - Place the dataset file (`PROG8430-25W-Assign01.txt`) in the same folder as `Exploratory_Sreejith.Rmd`.

4. **Render the File**:
   - In RStudio, click the **Knit** button to render the `.Rmd` file into a PDF, HTML, or Word document.
   - The output will show your analysis, results, and visualizations.

---

## Tasks Covered in the Project

### Part 1: Written Answers
- Transform a managerial statement into data analytics questions using logic and reasoning.
- Compare your interpretation with a generative AI tool's response and explain differences.

### Part 2: Data Analysis Tasks
- **Basic Manipulation**:
  - Load, clean, and format the dataset.
  - Handle missing values and adjust variable formats.
  - Analyze dataset dimensions and structure.

- **Statistical Summaries**:
  - Calculate mean, standard deviation, and coefficient of variation for key variables.
  - Determine data percentiles.

- **Visualizations**:
  - Create bar plots, histograms, scatter plots, and box plots with proper labels and formatting.
  - Interpret visualizations to answer project questions.

- **Organizing Data**:
  - Summarize data using tables and cross-tabulations.
  - Identify patterns and distributions across regions and other attributes.

---

## Dataset Description

The dataset `PROG8430-25W-Assign01.txt` provides insights into school board achievements and progress in Ontario. Each row represents a school board, with the following key variables:

- **`Name`**: School board name.
- **`Region`**: Geographic district.
- **`G6_EQAO`**: Grade 6 EQAO reading results.
- **`G10_Cr_Acc`**: Credit accumulation to the end of Grade 10.
- **`G4_Grad_Rate`**: Four-year graduation rates.

Additional attributes include board type, language, and credit progress rates.

---

## Source

**Government of Ontario, School Board Achievements and Progress**  
Dataset: [School board achievements and progress - Ontario Data Catalogue](https://data.ontario.ca/dataset/school-board-achievements-and-progress)

---


## Troubleshooting

- **Dataset Issues**: If the dataset does not load, ensure the file path is correct and matches the working directory in RStudio.
- **Rendering Errors**: Check that all required files are in the same directory and that RStudio has read/write permissions.

---


