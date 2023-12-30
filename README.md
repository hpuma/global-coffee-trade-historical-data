# Global Coffee Production (1990-2019)

## Overview

This GitHub repository contains Jupyter Notebooks for conducting exploratory analysis on datasets related to the global coffee production from the years 1990 to 2019. The goal of this project is to provide insights in global coffee production worldwide during the specified period.

## Datasets

The dataset used in this project comprises comprehensive information on production volume of the global coffee industry.

- [International Coffee Organization](https://www.ico.org/new_historical.asp?section=Statistics) - data/total_production.xlsx
- [Global Countries Dataset](https://www.kaggle.com/datasets/andradaolteanu/country-mapping-iso-continent-region?resource=download) - data/additional/csv/global_countries.csv

## Key Features

**Data Cleaning and Preprocessing:** The notebooks include detailed data cleaning and preprocessing steps to ensure the quality and consistency of the dataset. This involves handling missing values, removing duplicates, and transforming data into a format suitable for analysis.

**Exploratory Data Analysis (EDA):** The heart of the project lies in the exploratory analysis of the global coffee production dataset. Through visualizations and statistical summaries, the notebooks uncover trends, variations, and correlations in the data. EDA is performed at both global and regional levels.

## File Structure

```
├── curation // Contains notebooks for data profiling and manipulation
│   ├── tp_data_profiling.ipynb
│   └── tp_data_wrangling.ipynb
├── data // Contains all incoming and final csv files, also contains notebooks for additonal datasets
│   ├── additional
│   │   ├── csv
|   │   │   ├── global_countries_v1.csv
|   │   │   └── global_countries.csv // Raw global countries dataset
|   │   └── global_countries_wrangling.ipynb
|   ├── total_production_v1.csv // Used in exploratory analysis notebook
|   └── total_production.xlsx  // Raw ICO dataset
└── tp_exploratory_analysis.ipynb
```

## Getting Started

#### To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies specified in `requirements.txt`.
3. Open and run the Jupyter Notebooks in the order specified to ensure a logical flow of analysis.
   1. `curation/tp_data_profiling.ipynb`
   2. `curation/tp_data_wrangling.ipynb`
   3. `data/additonal/global_countries_wrangling.ipynb`
   4. `tp_exploratory_analysis.ipynb`

## Dependencies

The project relies on data science libraries such as:

- Pandas
- Matplotlib
