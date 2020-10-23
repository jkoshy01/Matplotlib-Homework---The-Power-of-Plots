# Matplotlib Homework - The Power of Plots

# Objective:

So let us explore what you have learned about Python Matplotlib and be able to apply using this data set:

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

Please follow these instructions:

  Before you start your analysis, check the data for any mouse ID that has a duplicate time points and remove any data that has the mouse ID.

* Use the cleaned data for the remaining steps.

* Create a summary statistics table consisting the following  mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Then you will generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that will show the number of total mice for each treatment regimen throughout the course of the study.

  * Side note: These plots should look similair.

*  Create a pie plot that uses both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` which shows the distribution of female or male mice in the study.

  * Side note: These plots should look similair.


*  You should be able to calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then you will calculate the "quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens."

* By using the Matplotlib, create a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

  **Tip**: All four box plots should be within the same figure. Use this  resource [Matplotlib documentation page](https://matplotlib.org/gallery/pyplots/boxplot_demo_pyplot.html#sphx-glr-gallery-pyplots-boxplot-demo-pyplot-py) for help with changing the style of the outliers.

* Then you will select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Create a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Then you will calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. You will Plot the linear regression model on top of the previous scatter plot.

* Make sure you generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

Here are some considerations:

* Maker sure you use the proper labeling of your plots, to include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.

* Use the starter workbook](Pymaceuticals/pymaceuticals_starter.ipynb) that will help you create the modules to import and expected format of the notebook.



*  there are many ways to approach a data problem. The key is to break up your task into small parts. Try answering questions like:

  

  " How do I build a basic scatter plot?

  * How do I add a label to that scatter plot?

  * Where would the labels for that scatter plot come from?"

  
    This assignment can be challeging so try to get some help ! There is never any shame in asking. They are also resources that can guide you.
