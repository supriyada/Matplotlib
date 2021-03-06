# Matplotlib
## Overview
> 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. Using various plots, the dataset is analysed to summarize the study results.
## Pre-requisites
> Two datasets: Mouse_metadata.csv & Study_results.csv.<br>
> Mouse ID with duplicate time points is checked and removed any data associated with that mouse ID before beginning analysis.<br>
## Final Report:

> - Summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.<br>
> - Bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen<br>
> - Pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.<br>
> - Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens: `Capomulin, Ramicane, Infubinol, and Ceftamin`.<br>
> - Line plot of tumor volume vs. time point for the mouse treated with `Capomulin`.<br>
> - Scatter plot of mouse weight versus average tumor volume for the `Capomulin treatment regimen`.<br>
> - The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment is calculated and the linear regression model is plotted on top of the previous scatter plot.<br>
## Observations:
> - The response to the treatment regimen Capomulin, is more promising as the days passby on few mice.

> - The bar chart shows that the treatment regimens Capomulin(230 measurements) and Ramicane(228 measurements) took more measurements than other treatment regimens.

> - Based on the calculation of IQR, quartiles and outliers, the treatment regimen's data of Capomulin, Ramicane, and Ceftamin doesnot have any outliers. Whereas Infubinol, has an outlier(the value is less the lower bound).

> - The scatter plot generated between mouse weight and average tumor volume for treatment regimen,Capomulin shows that points are close to each other. It show a strong relationship between them. The correlation coefficient calculated proves the same.

> - The correlation coefficient between mouse weight and average tumor volume is 0.84. Since it is greater than 0.7, the mouse weight and average tumor volume has strong positive correlation.
