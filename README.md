# Food Nutrition Clustering Using Principal Component Analysis

PCA and clustering of Malaysian food nutrition data using Python (Jupyter Notebook).

## Overview
Food labels contain many nutritional values (calories, fats, sugars, vitamins, minerals), which makes it hard to see which foods are similar. This group project uses Principal Component Analysis (PCA) to reduce the complexity of the data and group foods with similar nutritional profiles.

## Dataset
Food nutrition data with 30+ nutritional features, compiled from the Malaysian Food Composition Database (myfcd.moh.gov.my) and Kaggle.

## Methodology
1. Data collection
2. Data preprocessing (cleaning, removing irrelevant columns, handling missing values, standardization)
3. Correlation analysis (heatmap)
4. PCA and scree plot to select the number of components
5. Component loadings analysis
6. Visualization and cluster interpretation

## Key Findings
- The first 3 principal components captured most of the variance in the data.
- PC1: energy-dense macronutrients (calories, protein, fat)
- PC2: micronutrient-rich foods (vitamins and minerals)
- PC3: fiber and minerals (calcium, magnesium)

## Files
- `FRUIT CODE.ipynb`: Jupyter Notebook with the full analysis
- `FRUIT CODE.html`: HTML export of the notebook
- `FOOD-DATA.csv`: dataset used
- `poster.pdf`: project poster

## Tools
Python, Jupyter Notebook

## Note
Group project for Introduction to Machine Learning, Universiti Malaysia Terengganu.
