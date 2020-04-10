
# Univariate Exploration of Data

We start our exploration of a dataset with univariate visualizations or visualizations of single variables.By looking at one variable at a time, we can build an intuition for how each variable is distributed before moving on to more complicated interactions between variables. 

This sections will focus on two different plot types, **bar charts for qualitative variables** and **histograms for quantitative variables**.  While both of these plot types take the appearance of rectangles on a pair of axes, you will see how datatype makes these plots distinct. 


# What is Tidy Data?

In this section, it is expected that your data is organized in some kind of tidy format. In short, a [tidy dataset](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html) is a tabular dataset where:

   * each variable is a column
   * each observation is a row
   *each type of observational unit is a table

The first three images below depict a tidy dataset. This tidy dataset is in the field of healthcare and has two tables: one for patients (with their patient ID, name, and age) and one for treatments (with patient ID, what drug that patient is taking, and the dose of that drug).

 <p align="right">
  <img src="../img/22.PNG" alt="" width="600" height="300" >
 </p>

Each variable in a tidy dataset must have its own column.
 
 <p align="right">
  <img src="../img/23.PNG" alt="" width="600" height="300" >
 </p>
Each observation in a tidy dataset must have its own row
 <p align="right">
  <img src="../img/24.PNG" alt="" width="600" height="300" >
 </p>
 
Each observational unit in a tidy dataset must have its own table


The next image depicts the same data but in one representation of a non-tidy format (there are other possible non-tidy representations). The Drug A, Drug B, and Drug C columns should form one 'Drug' column, since this is one variable. The entire table should be separated into two tables: a patients table and a treatments table.

 <p align="right">
  <img src="../img/25.PNG" alt="" width="600" height="300" >
 </p>
 
Only the second rule of tidy data is satisfied in this non-tidy representation of the above data: each observation forms a row

While the data provided to you in the section will all be tidy, in practice, you may need to perform tidying work before exploration. You should be comfortable with reshaping your data or perform transformations to split or combine features in your data, resulting in new data columns. This work should be performed in the wrangling stage of the data analysis process.

Note: tidy data is not the only useful form that data can take.In fact, as you work with a dataset, you might need to summarize it in a non-tidy form in order to generate appropriate visualizations.
