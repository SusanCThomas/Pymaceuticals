# Matplotlib Homework - The Power of Plots

## [Pymaceuticals-Matplotlib](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/tree/main/Pymaceuticals)

Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. The most recent animal study identified 249 mice wtih SCC tumor growth that were treated through a variety of drug regimens. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. This analysis includes the generation of tables and figures needed for the technical part of the study. Also included is a top-level summary of the study results. 

## Analysis

This analysis of the [data](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/tree/main/Pymaceuticals/data) includes the below steps in a [Jupyter Notebook](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/pymaceuticals_.ipynb) with viewable Data Frames and [Images](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/tree/main/Pymaceuticals/Images) of all Plots:

### Data Transformation

Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID. Use the cleaned data for the remaining steps.

### Summary Statistics

Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

### Data Visualization

* Generate a bar plot using both [Pandas's](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/Images/pandas_bar.png) `DataFrame.plot()` and [Matplotlib's](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/Images/pyplot_bar.png) `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

* Generate a pie plot using both [Pandas's](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/Images/pandas_pie.png) `DataFrame.plot()` and [Matplotlib's](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/Images/pyplot_pie.png) `pyplot` that shows the distribution of female or male mice in the study.

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a [box and whisker plot](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/Images/boxplot.png) of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* Select a mouse that was treated with Capomulin and generate a [line plot](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/Images/lineplot.png) of tumor volume vs. time point for that mouse.

* Generate a [scatter plot](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/Images/scatterplot.png) of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the [linear regression model](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/Images/linear_regression.png) on top of the previous scatter plot.

### Data Analysis

Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

Three observations are included at the top of the [notebook](https://github.com/SusanCThomas/Pymaceuticals-Matplotlib/blob/main/Pymaceuticals/pymaceuticals_.ipynb) after reviewing the previously generated figures and tables.
