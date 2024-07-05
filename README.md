# Pymaceuticals Analysis

## Table of Contents
- [Project Description](#project-description)
- [Results](#results)

## Project Description

### Overview
This project conducts a comprehensive analysis of mouse tumor volume versus drug regimen. It utilizes two datasets to derive insights about mice tumor volumes and outcomes and trends based on the drug regimen.

### Analysis Highlights

#### Summary Statistics

The analysis begins with showing summary statistics per drug regimen used on 248 mice grouped by the drug regimens; this includes the Mean Tumor Volume, Median Tumor Volume, Tumor Volume Variance, Tumor Volume Standard Deviation, and Tumor Standard Error of the Mean.  

![Summary statistics per drug regimen](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/summary_statistics.png)

#### Bar and Pie Charts
The bar chart shows the number of observed mouse timepoints per drug regimen in descending order.  As shown, Capomulin has the greated number of observed timepoints and propivera has the least.  This leads to further analysis of Capomulin results. 

![Bar chart of drug regimens vs number of observed mouse timepoints](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/bar_chart.png)

The pie chart shows that there are slightly more male mice, 51%, compared to female mice, 49%.  

![Pie chart of mouse sexes](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/pie_chart.png)

#### Quartiles, Outliers and Boxplots
The final tumor volume of each mouse across four of the treatment regimens is calculated: Capomulin, Ramicane, Infubinol, and Ceftamin.  

Using the data to calculate interquartile range, we see that Infubinol has a Tumor Volume outlier of 36.321346 mm3.  This was for mouse c326. There were not outliers for Capomulin, Ramicane or Ceftamin.  

We then plot the Final Tumor Volume using boxplots per drug regimens Capomulin, Ramicane, Infubinol, and Ceftamin.  

Note the following about boxplots and what they show about the final tumor volumes per drug regimen: 
   - The bottom of the box represents the first quartile (Q1; the 25th percentile) of the final tumor volumes. 
   - The top of the box represents the third quartile (Q3; the 75th percentile) of final tumor volumes. 
   - The line in the middle of the box represent the median (Q2; the 50th percentile) of final tumor volumes.

![Boxplots of Ramicane, Infubinol, and Ceftamin final tumor volumes](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/boxplots.png)

#### Line and Scatter Plots
The following line plot shows the Timepoint in days vs Tumor Volume for mouse l509 treated with Capomulin.  

![Line plot of Capomulin Treatment for Mouse l509](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/line_plot.png)

The following scaterplot shows mice weights vs their average tumor volume for the Capomulin drug regimen.  

![Scatterplot of Capomulin treatment: Weight of Mouse vs Average Tumor Volume](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/scatterplot.png)

#### Correlation and Regression
The following scaterplot shows mice weights vs their average tumor volume for the Capomulin drug regimen, but also plots the linear regression model.  

![Correlation and Regression of the scatterplot data](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/lin_reg.png)

#### Conclusions

- **Summary Statistics**:
- The drug regimen Ramicane has the lowest meadian tumor volume (40.673236) and also the lowest standard deviation of tumor volume (4.846308).  Having the lowest standard deviation indicates that the tumor volumes are more consistently closer or less spread out from the median.  This suggests that the drug regimen results are more consistent. 
- In contrast, Ketapril having the highest standard deviation (8.279709) indicates that the results were more spread out or that the tumor volumes were more inconsistent. 

- **Bar and Pie Charts**:
- Our bar chart shows that Capomulin has the greatest number of observed timepoints in the experiment, which Ramicane close second and Propriva last.  This lends more data that can be analyzed for Capomulin.
- The pie chart shows that there are slightly more male mice, 51%, compared to female mice, 49%. 

- **Quartiles, Outliers and Boxplots**:
- In our boxplots, we see an outlier for Final Tumor Volume for Infubinol, which was 36.321346 mm3.  

- **Line and Scatter Plots**:
- The line plot shows an increase in tumor volume for mouse l509 treated with Capomulin up until about day 20.  Then, we start to see a great decline in tumor volume.  This indicates progress in reducing the tumor volume of the mouse with this drug regimen.  
- Our scatter plot shows that as the weight of mice increases, so does the average tumor volume. This suggests that there is a correlation between average tumor volume and weight of the mice.  
 
- **Correlation and Regressions**:
- Our Correlation and Regression model, and Pearson's r correlation coefficient, confirm that there is a correlation between weight of the mice and average tumor volume of the mice.  The line shown on the graph increases from left to right.  Pearson's r correlation coefficient is 0.8419363424694724, which indicates a strong linear relationship.  

## Results 

### Summary Statistics
![Summary statistics per drug regimen](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/summary_statistics.png)

### Bar and Pie Charts
![Bar chart of drug regimens vs number of observed mouse timepoints](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/bar_chart.png)

![Pie chart of mouse sexes](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/pie_chart.png)

### Quartiles, Outliers and Boxplots
![Boxplots of Ramicane, Infubinol, and Ceftamin final tumor volumes](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/boxplots.png)

### Line and Scatter Plots
![Line plot of Capomulin Treatment for Mouse l509](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/line_plot.png)

![Scatterplot of Capomulin treatment: Weight of Mouse vs Average Tumor Volume](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/scatterplot.png)

### Correlation and Regression
![Correlation and Regression of the scatterplot data](https://github.com/pixare7/pymaceuticals-project/blob/main/results_images/lin_reg.png)
