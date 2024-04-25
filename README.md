# Pharmaceutical Data Analysis

## Overview
The pharmaceutial data analysis project focuses on analyzing the results of a study on the performance of various drug regimens on tumor treatment in mice. The data includes information about the drug regimen, tumor volume, timepoints, and mouse characteristics like weight and sex. The project aims to provide insights into the effectiveness of different drug regimens based on various statistical analyses and visualizations.

## Analysis Overview
* Summary Statistics: Provides mean, median, variance, standard deviation, and SEM of the tumor volume by drug regimen.
* Bar and Pie Charts: Displays the total number of timepoints for each drug regimen and the distribution of male vs. female mice in the study.
* Quartiles, Outliers, and Boxplots: Illustrates the effect of specific drugs on tumor volume, highlighting potential outliers.
* Line Plot: Tracks the tumor volume changes over time for a single mouse treated with Capomulin.
* Scatter Plot: Shows the relationship between mouse weight and average tumor volume for mice treated with Capomulin.
* Correlation: Demonstrates a strong positive correlation between average mouse weight and tumor volume.
* Regression Analysis: Provides a regression model to predict tumor volume based on mouse weight.

## Dependencies and Setup
The project requires several Python libraries for data manipulation and visualization. These include:
* matplotlib.pyplot: For creating plots and visualizations.
* pandas: For data manipulation and analysis.
* scipy.stats: For statistical computations.
* numpy: For numerical computations.
* scipy.stats.sem: For calculating the standard error of the mean.
* scipy.stats.linregress: For performing linear regression analysis.


## Data Preparation
The project begins by loading two CSV files containing mouse metadata and study results. These datasets are then merged based on the common column 'Mouse ID' to create a comprehensive DataFrame.

## Data Analysis
### Summary Statistics
The summary statistics are calculated to determine the central tendency, dispersion, and variability of the tumor volume across different drug regimens.

### Bar and Pie Charts
Bar charts are used to visualize the total number of timepoints recorded for each drug regimen. Pie charts display the distribution of male and female mice in the study.

### Quartiles, Outliers, and Boxplots
The final tumor volume for specific treatments is calculated, and quartiles are used to identify potential outliers. A boxplot is then generated to visualize the distribution of tumor volumes for each treatment regimen.

### Line and Scatter Plots
A line plot is created to track the changes in tumor volume over time for a mouse treated with Capomulin. A scatter plot is used to examine the relationship between mouse weight and average tumor volume for mice treated with Capomulin.

### Correlation and Regression
The correlation coefficient between mouse weight and average tumor volume is calculated to determine the strength and direction of their relationship. Additionally, a linear regression model is generated to predict tumor volume based on mouse weight.

## Conclusion
The analysis of the Pymaceuticals Inc. study provides valuable insights into the efficacy of various drug regimens in treating tumors in mice. The data visualizations and statistical analyses offer a comprehensive view of the outcomes, aiding in making informed decisions for further research and drug development.

## Pymaceuticals Folder: 
1. main.py --> Contains python pandas script for the SCC study analysis 
2. data folder --> Contains the csv file from which the data was acquired 




