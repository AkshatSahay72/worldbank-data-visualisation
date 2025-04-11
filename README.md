# World Bank Development Indicators Analysis

## Introduction

This project focuses on analyzing key socio-economic indicators across countries using data sourced from the World Bank. The aim is to derive meaningful insights into development trends, relationships between different indicators, and patterns across regions and time. The analysis leverages Python’s powerful data science libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## Objectives

1. **Clean and preprocess the dataset** to make it analysis-ready.
2. **Perform Exploratory Data Analysis (EDA)** to explore the structure, distribution, and characteristics of the dataset.
3. **Handle missing values effectively** using appropriate imputation techniques for both numerical and categorical data.
4. **Visualize key socio-economic indicators** to identify trends and anomalies.
5. **Analyze relationships between development indicators** (e.g., Internet usage vs. population density, education vs. GDP).
6. **Communicate insights through visualizations and summaries** to make findings accessible and interpretable.

## Methodology

1. **Data Loading**
   - Imported the dataset from an Excel file containing multiple World Bank development indicators.

2. **Data Cleaning**
   - Dropped unnecessary metadata columns.
   - Renamed columns for better readability.
   - Identified and handled missing data using:
     - **Mean imputation** for numerical columns.
     - **Mode imputation** for categorical columns.

3. **Exploratory Data Analysis (EDA)**
   - Generated summary statistics and visualized distributions.
   - Examined trends over time and differences across countries.

4. **Visualization & Insight Extraction**
   - Created scatter plots, heatmaps, and line graphs to analyze relationships like:
     - Population Density vs. Internet Usage
     - GDP per Capita vs. School Enrollment
   - Used these visualizations to extract and interpret meaningful patterns.
