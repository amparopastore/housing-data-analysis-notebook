# Housing Data Analysis Notebook

This repository contains a Jupyter notebook for analyzing housing data. The notebook includes data loading, visualization, and feature engineering tasks.

## Contents

- `housing_data_analysis.ipynb`: The main Jupyter notebook with the data analysis.
- `housing.header.txt`: The dataset used for analysis.
- `README.md`: This file.

## Description

The notebook performs the following tasks:

1. **Data Loading**
   - Reads `housing.header.txt` into a pandas DataFrame.
   - Reports the number of instances and features.

2. **Data Visualization**
   - Scatter plot of `Crim` index vs. sample index.
   - Histogram and density plot of `Crim` index.
   - Scatter plots for `Crim-Medv`, `Rm-Medv`, `Age-Medv`, and `Tax-Medv`.
   - Scatter plots showing relationships between various attributes and `Medv`.
   - Pairwise correlation heatmap of all attributes.

3. **Feature Engineering**
   - Subsets the data based on specific criteria.
   - Adds a new instance to the DataFrame.
   - Creates a new feature (`Dummy`) with random values.

4. **Correlation Analysis**
   - Identifies the most positively and negatively correlated variables with `Medv`.
