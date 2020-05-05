
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

**Shape is a good encoding for categorical variables**, using one shape for each level of the categorical variable. Unfortunately, there is no built-in way to automatically assign different shapes in a single call of the **scatter or regplot** function. Instead, we need to write a loop to call our plotting function multiple times, isolating data points by categorical level and setting a different "marker" argument value for each one.check this [notebook]() to get more information.

### Encoding via Size

**Point size is a good encoding for numeric variables**. Usually, we want the numeric values to be proportional to the area of the point markers; this is the default functionality of the "s" parameter in scatter.check this [notebook]() to get more information.

### Encoding via Color Palettes
Color is a very common encoding for variables, for **both qualitative and quantitative variables**. Here, we'll look at how to employ color in scatterplots, as well as discuss more about color palette choices depending on the type of data you have to change the type of color palette that you use to depict your data. There are three major classes of color palette to consider: 
* Qualitative
* Sequential
* Diverging.

check this [notebook]() to get more information.







 <p align="right">
  <img src="../img/26.PNG" alt="" width="300" height="300" >
 </p>
 
