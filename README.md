# COVID-19 OWID Exploratory Data Analysis

A notebook-based, exploratory analysis of the Our World in Data COVID-19 dataset, including data cleaning, summary analysis, and interactive geographic visualizations.

## Project Description

This repository contains a notebook-driven analysis of global COVID-19 trends using OWID data. The analysis includes:

- data ingestion and cleaning
- summary statistics and missing-data checks
- country- and continent-level visualization
- interactive maps and charts using Plotly

The goal is to explore pandemic patterns, visualize geographic trends, and create reproducible outputs for reporting or presentation.

## Repository Contents

- `exploratory_analysis.ipynb` — main Jupyter notebook with analysis code and visualization cells
- `owid-covid-data.csv` — the raw OWID COVID-19 dataset

## Recent changes

- Added an analysis comparing `population_density` to `new_cases_per_million` at the continent level.
- Added a continent-level scatter plot with regression-style trend line to assess whether higher density is associated with higher case rates.
- Included a written interpretation of the plot results, showing that the relationship is weakly positive but not strong.
- Added density quartile and case-rate ratio checks to help identify continent-level outliers.

## Getting Started

1. Install the required packages:

```bash
pip install pandas numpy seaborn matplotlib plotly
```

2. Open the notebook in Jupyter or VS Code.

3. Run the notebook cells in order to load the data, inspect the dataset, and generate visualizations.

## Notes

- For Plotly charts to display correctly in VS Code notebooks, ensure the notebook kernel has Plotly installed and the renderer is configured.

