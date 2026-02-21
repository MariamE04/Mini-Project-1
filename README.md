## Project Overview
This project investigates the relationship between physicochemical properties of wine and wine quality using statistical analysis and exploratory data visualization techniques.
The objective was to identify which chemical attributes are most strongly associated with wine quality and to evaluate differences between red and white wine.
The analysis was conducted as part of a group mini project in Business Data Exploration and Visualization.

## Group members
Abbas Mahmoud Badreddine
Mariam Lumiere El Mir

## Datasets Used
### Primary Datasets
Red Wine Quality Dataset
White Wine Quality Dataset

The two datasets were cleaned, transformed, and aggregated into one combined dataset.

### Eksternal Dataset
An additional external dataset from Kaggle (Wine Reviews) was imported and stored locally for potential future market-based analysis.

This dataset contains:
- country
- price
- points (consumer rating)
- variety

The external dataset was not used in the statistical modelling but demonstrates integration of alternative public data sources.

## Data Preparation
The following preprocessing steps were applied:
- Removal of duplicate observations
- Column renaming for consistency
- Creation of categorical quality levels
- Aggregation of red and white wine datasets
- Correlation analysis
- Feature selection and removal of weak or redundant variables

Multicollinearity was identified between:
- free_sulfur_dioxide and total_sulfur_dioxide
- alcohol and density
  
Feature reduction was performed to improve interpretability.


## Exploratory Data Analysis
The analysis included:
- Descriptive statistics
- Distribution comparisons between red and white wine
- Boxplots and scatterplots
- Correlation matrix and heatmap visualization
- pH binning analysis (5 and 10 intervals)

## Key Findings
- White wine has a slightly higher average quality score than red wine (difference ≈ 0.23 points).
- White wine contains significantly higher residual sugar levels.
- Alcohol shows the strongest positive correlation with wine quality (r ≈ 0.47).
- Density and volatile acidity show moderate negative relationships with quality.
- Residual sugar shows weak correlation with quality.
- Strong multicollinearity was detected between sulfur dioxide variables.

These findings suggest that alcohol content is one of the most important measurable indicators associated with wine quality.

## Hypotheses Tested
**H1**: White wine has higher residual sugar than red wine ✔
**H2**: Alcohol is positively related to quality ✔
**H3**: Average quality differs between red and white wine ✔ (small difference)
**H4**: Higher residual sugar does not necessarily imply higher quality ✔
**H5**: Some chemical properties influence quality more than others ✔

## Business Implications
### Wine Producers
- Alcohol content appears to be strongly associated with higher quality scores.
- Optimization of specific chemical attributes may improve perceived quality.

## Wine Distributors
- Quality differences between wine types are relatively small.
- Chemical profiles may support product segmentation.

## Consumers
- Higher alcohol content tends to be associated with higher quality.
- Sweetness alone is not a reliable indicator of quality.
