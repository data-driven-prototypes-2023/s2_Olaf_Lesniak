# Open Food Facts Yogurt Analysis Dashboard
## Overview
This repository contains a Dash application for analyzing yogurt products sold in the US, based on data from the Open Food Facts database. The application provides interactive plots and features to help users compare different yogurt products, find healthier substitutes, and visualize nutrient distributions.
## Raw Data
The raw data used in this project is sourced from the Open Food Facts database, specifically focusing on yogurt products sold in the US. The dataset includes various nutritional values, product names, brands, labels, and Nutri-Score grades.

##Data Cleaning
The data was cleaned and preprocessed using the following steps:

- Handling Missing Values: Imputing or removing missing values as necessary.
- Removing Outliers: Using the Interquartile Range (IQR) method to identify and remove outliers.
- Standardizing Values and Units: Converting all nutritional values to standard units (e.g., grams per 100g) for consistency.
- Formatting Labels: Stripping leading/trailing spaces and converting text to lowercase.
After cleaning, the dataset consists of over 3,500 data points.

##Features and Interactivity
The Dash application includes the following features and interactive elements:

## Nutrient Distribution Plot
-Select a Nutrient: Choose a nutrient (e.g., Fat, Carbohydrates) to visualize its distribution across different yogurt products.
- Plot Types: Toggle between line plots and histograms.
- View Types: Switch between frequency and density views.
# Nutrient Comparison by Nutri-Score Grade
- Box Plots: Compare nutrient levels across different Nutri-Score grades.
- Hover Data: Hover over points to see detailed product names.
# Product Clusters Scatter Plot
- Scatter Plots: Visualize clusters of products based on two selected nutrients.
- Point Sizing: Optionally size points by a third nutrient.
- Adjustable Point Size: Manually adjust the size of points using a slider.
## Find Healthier Substitutes
- Product Selection: Select a product to find healthier substitutes.
- Similarity Scores: View similarity scores and Nutri-Score improvements for substitute products.
## Filtering and Selection
- Brand Filter: Filter products by brand.
- Label Filter: Filter products by label.
- Clear Selection: Clear all filters and selections with a single button click.

# Conclusion
This Dash application provides a comprehensive tool for analyzing yogurt products sold in the US, leveraging data from the Open Food Facts database. With interactive plots and features, users can explore nutrient distributions, compare products by Nutri-Score, and find healthier alternatives with ease.
