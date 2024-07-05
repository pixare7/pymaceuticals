# Pymaceuticals Analysis

## Table of Contents
- [Project Description](#project-description)
- [Results](#results)

## Project Description

### Overview
This project undertakes a comprehensive analysis of mouse tumor volumes in relation to various drug regimens. It utilizes two datasets to derive insights about tumor volume dynamics and treatment outcomes based on different drug regimens.

### Analysis Highlights

#### Summary Statistics

The analysis begins by presenting summary statistics per drug regimen for 248 mice. This includes Mean Tumor Volume, Median Tumor Volume, Tumor Volume Variance, Tumor Volume Standard Deviation, and Tumor Standard Error of the Mean.

![Summary statistics per drug regimen](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/summary_statistics.png)

#### Bar and Pie Charts

The bar chart displays the number of observed mouse timepoints per drug regimen in descending order. Notably, Capomulin has the highest number of observed timepoints, while Propivera has the least, guiding further analysis into Capomulin's efficacy.

![Bar chart of drug regimens vs number of observed mouse timepoints](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/bar_chart.png)

The pie chart indicates a slightly higher presence of male mice (51%) compared to female mice (49%).

![Pie chart of mouse sexes](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/pie_chart.png)

#### Quartiles, Outliers, and Boxplots

Final tumor volumes are analyzed across four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. The interquartile range calculation identifies an outlier for Infubinol with a tumor volume of 36.321346 mm3 for mouse c326. No outliers were found for Capomulin, Ramicane, or Ceftamin.

![Boxplots of Ramicane, Infubinol, and Ceftamin final tumor volumes](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/boxplots.png)

#### Line and Scatter Plots

A line plot illustrates the progression of tumor volume over time for mouse l509 treated with Capomulin.

![Line plot of Capomulin Treatment for Mouse l509](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/line_plot.png)

The scatter plot depicts the relationship between mice weights and their average tumor volumes under the Capomulin regimen, showing a positive correlation.

![Scatterplot of Capomulin treatment: Weight of Mouse vs Average Tumor Volume](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/scatterplot.png)

#### Correlation and Regression

The scatter plot with a linear regression model highlights the relationship between mice weights and average tumor volume for the Capomulin regimen.

![Correlation and Regression of the scatterplot data](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/lin_reg.png)

#### Conclusions

- **Summary Statistics**:
  - Ramicane exhibits the lowest median tumor volume (40.673236) and standard deviation (4.846308), indicating more consistent results compared to other regimens like Ketapril, which has the highest standard deviation (8.279709).

- **Bar and Pie Charts**:
  - The bar chart underscores Capomulin's dominance in observed timepoints, followed closely by Ramicane, and highlights areas for deeper investigation.

- **Quartiles, Outliers, and Boxplots**:
  - Infubinol shows an outlier in final tumor volume (36.321346 mm3), suggesting potential variability in treatment efficacy.

- **Line and Scatter Plots**:
  - The line plot reveals a significant reduction in tumor volume for mouse l509 under the Capomulin treatment regimen, indicating promising therapeutic outcomes.

  - The scatter plot confirms a positive correlation between mouse weight and average tumor volume, reinforcing the need to consider weight variations in treatment outcomes.

- **Correlation and Regression**:
  - The strong linear relationship (Pearson's r correlation coefficient of 0.8419363424694724) between mouse weight and average tumor volume validates the correlation observed in the scatter plot.

## Results

### Summary Statistics
![Summary statistics per drug regimen](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/summary_statistics.png)

### Bar and Pie Charts
![Bar chart of drug regimens vs number of observed mouse timepoints](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/bar_chart.png)

![Pie chart of mouse sexes](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/pie_chart.png)

### Quartiles, Outliers, and Boxplots
![Boxplots of Ramicane, Infubinol, and Ceftamin final tumor volumes](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/boxplots.png)

### Line and Scatter Plots
![Line plot of Capomulin Treatment for Mouse l509](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/line_plot.png)

![Scatterplot of Capomulin treatment: Weight of Mouse vs Average Tumor Volume](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/scatterplot.png)

### Correlation and Regression
![Correlation and Regression of the scatterplot data](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/lin_reg.png)
