
# Bivariate Exploration of Data

In this section, you will continue to develop your insights through Bivariate Visualizations. 
Bivariate Visualizations are those that involve two variables. We use Bivariate Visualizations to look at relationships when we change the level or value of one variable to see what kind of changes do we expect from the second?  

We will look at three major bivariate plots. 

* For quantitative versus quantitative variables, there are scatter plots. 

* For quantitative versus qualitative, we use violin plots. 

* For qualitative versus qualitative, we discuss clustered bar charts. 



 <p align="right">
  <img src="../img/26.PNG" alt="" width="300" height="300" >
 </p>
 
# Scatterplots

If you want to inspect the relationship between two numeric variables, the standard choice of plot is the scatterplot. check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Scatterplots%20and%20Correlation.ipynb) to get more familiar with it.

# Overplotting, Transparency, and Jitter

If we have a very large number of points to plot or our numeric variables are discrete-valued, then it is possible that using a scatterplot straightforwardly will not be informative. The visualization will suffer from overplotting, where the high amount of overlap in points makes it difficult to see the actual relationship between the plotted variables. check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/%20Overplotting%2C%20Transparency%2C%20and%20Jitter.ipynb) to get more familiar with it.

# Heat Maps

A heat map is a 2-d version of the histogram that can be used as an alternative to a scatterplot. Like a scatterplot, the values of the two numeric variables to be plotted are placed on the plot axes. Similar to a histogram, the plotting area is divided into a grid and the number of points in each grid rectangle is added up. check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Heat%20Maps.ipynb) to get more familiar with it.

# Violin Plots

There are a few ways of plotting the relationship between one quantitative and one qualitative variable, that demonstrate the data at different levels of abstraction. The violin plot is on the lower level of abstraction. For each level of the categorical variable, a distribution of the values on the numeric variable is plotted. . check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Violin%20Plots.ipynb) to get more familiar with it.

# Box Plots

A box plot is another way of showing the relationship between a numeric variable and a categorical variable. Compared to the violin plot, the box plot leans more on summarization of the data, primarily just reporting a set of descriptive statistics for the numeric values on each categorical level. check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Box%20Plots.ipynb) to get more familiar with it.
