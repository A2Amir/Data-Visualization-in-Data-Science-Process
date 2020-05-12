
# Multivariate Exploration of Data.md

In this section, you will continue to develop your insights through Multivariate Visualizations. 

# Non-Positional Encodings for Third Variables

There are four major cases to consider when we want to plot three variables together:


  * three numeric variables
  * two numeric variables and one categorical variable
  * one numeric variable and two categorical variables
  * three categorical variables


If we have **at least two numeric variables**, as in the first two cases, one common method for depicting the data is by using a scatterplot to encode two of the numeric variables, then using a non-positional encoding (Shape, Color, Size) on the points to convey the value on the third variable, whether numeric or categorical. 

Three main non-positional encodings stand out: 
* Shape
* Size
* Color


### Encoding via Shape

**Shape is a good encoding for categorical variables**, using one shape for each level of the categorical variable. Unfortunately, there is no built-in way to automatically assign different shapes in a single call of the **scatter or regplot** function. Instead, we need to write a loop to call our plotting function multiple times, isolating data points by categorical level and setting a different "marker" argument value for each one.check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Encoding%20via%20Shape.ipynb) to get more information.

### Encoding via Size

**Point size is a good encoding for numeric variables**. Usually, we want the numeric values to be proportional to the area of the point markers; this is the default functionality of the "s" parameter in scatter.check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Encoding%20via%20Size.ipynb) to get more information.

### Encoding via Color 
Color is a very common encoding for variables, for **both qualitative and quantitative variables**. Here, we'll look at how to employ color in scatterplots, as well as discuss more about color palette choices depending on the type of data you have to change the type of color palette that you use to depict your data. There are three major classes of color palette to consider: 
* Qualitative
* Sequential
* Diverging.

check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Encoding%20via%20Color%20.ipynb) to get more information.

# Faceting in Two Directions


In the this [section](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Faceting.ipynb), you saw how FacetGrid could be used to subset the dataset across levels of a categorical variable, and then create one plot for each subset or you saw in this [section](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Encoding%20via%20Color%20.ipynb) how to facet bivariate plots to create a multivariate visualization.


FacetGrid also allows for faceting a variable not just by columns, but also by rows. We can set one categorical variable on each of the two facet axes for one additional method of depicting multivariate trends.check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Faceting%20in%20Two%20Directions.ipynb) to get more information.

# Other Adaptations of Bivariate Plots


You also saw earlier in this section one other way of expanding univariate plots into bivariate plots by substituting count on a [bar chart](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Adapted%20Bar%20Charts.ipynb) or [histogram](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Adapted%20Histograms.ipynb) for the mean, median, or some other statistic of a second variable. This adaptation can also be done for bivariate plots like the heat map, clustered bar chart, and line plot, to allow them to depict multivariate relationships. check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Other%20Adaptations%20of%20Bivariate%20Plots.ipynb) to get more information.

# Plot Matrices and Correlation Matrices

If you want to look at the relationship between many pairs of variables rather than generate the bivariate plots one by one, a preliminary option you might consider for exploration is the creation of a plot matrix. In a plot matrix, a matrix of plots is generated. Each row and column represents a different variable, and a subplot against those variables is generated in each plot matrix cell. This contrasts with faceting, where rows and columns will subset the data, and the same variables are depicted in each subplot. check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Plot%20Matrices.ipynb) to get more information.

# Feature engineering

feature engineering is a tool that you can leverage as you explore and learn about your data. As you explore a dataset, you might find that two variables are related in some way. Feature engineering is all about creating a new variable with a sum, difference, product, or ratio between those original variables that may lend a better insight into the research questions you seek to answer. check this [notebook](https://github.com/A2Amir/Data-Visualization-in-Data-Science-Process/blob/master/Code/Feature%20Engineering.ipynb) to get more information.
