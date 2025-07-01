# Explorative-Analysis-and-Correlation-in-the-Film-Industry-with-Python

Project Description

This notebook performs an Exploratory Data Analysis (EDA) on the "Movie Industry" dataset, focusing on identifying patterns and relationships among key variables such as budget, gross earnings, score, votes, and release year. The analysis uses libraries like pandas, seaborn, and matplotlib, and concludes with an investigation into significant correlations among both numerical and transformed categorical features.

Steps Performed

1. Library Imports

Imported essential libraries for data manipulation and visualization.

2. Dataset Loading

Loaded the movies.csv file containing data from the movie industry.

3. Missing Data Detection & Visualization

    Calculated the percentage of missing values per column

    Visualized the distribution of missing data using a heatmap

4. Initial Cleaning

    Removed duplicate entries in the company column
   
    Removed rows where critical financial info is missing

6. Budget vs Gross Earnings Analysis

    Created a scatter plot comparing budget and gross

    Plotted a linear regression line using sns.regplot to observe trends

7. Correlation Matrix for Numeric Features

    Selected only int64 and float64 columns

    Calculated Pearson correlation coefficients

    Visualized the results using a heatmap

8. Categorical Feature Transformation

    Converted object columns into numeric codes using .astype('category').cat.codes

9. Full Correlation Matrix

    Computed correlations across all (now numeric) columns

    Identified strongly correlated variable pairs (absolute correlation > 0.5)
