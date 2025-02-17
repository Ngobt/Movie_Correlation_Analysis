# Movie Correlation Analysis

## Overview
This project analyzes the correlation between various factors in a dataset of movies. The goal is to identify relationships between features such as box office revenue, budget, runtime, ratings, and other numerical attributes. The analysis is conducted using **Pandas**, **NumPy**, and **Matplotlib/Seaborn** for data visualization.

## Dataset
The dataset consists of movie-related attributes, including:
- **Title**: Movie name
- **Budget**: Production budget
- **Revenue**: Box office earnings
- **Runtime**: Duration of the movie
- **Ratings**: IMDB or other aggregated scores
- **Genre, Release Date, etc.**: Additional categorical features

## Key Features
- **Data Cleaning**: Handling missing values, dropping duplicates, and ensuring numerical data types.
- **Correlation Computation**: Analyzing relationships between numeric features.
- **Data Visualization**: Using heatmaps and scatter plots to highlight significant correlations.
- **Filtering Numeric Data**: Ensuring that correlation calculations only use valid numerical columns.

## Requirements
Install the required Python libraries before running the notebook:
```bash
pip install pandas numpy matplotlib seaborn
```

## How to Use
1. Open the **Movie_Correlation_Analysis.ipynb** notebook.
2. Run the data cleaning and preprocessing steps.
3. Generate correlation matrices and visualizations.
4. Interpret results and insights from the correlation findings.

## Insights
- How budget correlates with gross earnings.
- The relationship between numeric values.
- How votes correlate with gross earnings.

