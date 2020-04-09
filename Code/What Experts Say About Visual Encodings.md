
# What Experts Say About Visual Encodings 

Experts and researchers have determined the types of visual patterns that allow humans to best understand certain information. In general, humans are able to best understand data encoded with **positional changes (differences in x- and y- position as  scatterplots)** and **length changes (differences in box heights as  bar charts and histograms)**.

Alternatively, humans struggle with understanding data encoded with **color hue changes** (as are unfortunately commonly used as an additional variable encoding in scatter plots) and **area changes** (as pie charts, which often makes them not the best plot choice).

# Chart junk

From Wikipedia, [Chart junk](https://en.wikipedia.org/wiki/Chartjunk) refers to all visual elements in charts and graphs that are not necessary to comprehend the information represented on the graph or that distract the viewer from this information.

Examples of chart junk include:

   * Heavy grid lines
   * Unnecessary text
   * Pictures surrounding the visual
   * Shading or 3d components
   * Ornamented chart axes

# Data-ink ratio
As you know, we can better our visualizations by removing extraneous elements. We can conceptualize this relationship using something called the data-to-ink ratio. As the ratio of the amount of ink used to describe the data to the total amount of ink in the visual.
In general, the higher the data-to-ink ratio, the better (Limiting chart junk increases the data-ink ratio.). 
 
 <p align="right">
  <img src="../img/15.PNG" alt="" width="400" height="200" >
 </p>

The **data-ink ratio**, credited to Edward Tufte, is directly related to the idea of chart junk. The more of the ink in your visual that is related to conveying the message in the data, the better. This means that a large amount of the ink in the visual is being used to actually describe the data, while low data-ink ratio suggests that you are using ink that is added for other purposes rather than describing the data. These elements should be removed. Let's take a look at an example. 
 
  <p align="right">
  <img src="../img/16.PNG" alt="" width="500" height="350" >
 </p>
 
 As  you can easily see the effect of improving the data-to-ink ratio.The visualization with the high data-to-ink ratio(on the right side) is far more clear, more interpretable, and has all the elements you need for a great visualization. 

# Design Integrity

It is key that when you build plots you maintain integrity for the underlying data. One of the main ways discussed here for looking at data integrity was with the **lie factor**. Lie factor depicts the degree to which a visualization distorts or misrepresents the data values being plotted. It is calculated in the following way:

  <p align="right">
  <img src="../img/17.PNG" alt="" width="300" height="120" >
 </p>
 
 The delta symbol (Δ) stands for difference or change. In words, the lie factor is the relative change shown in the graphic divided by the actual relative change in the data. Ideally, the lie factor should be 1: any other value means that there is some mismatch in the ratio of depicted change to actual change.
 
The lie factor shown below was in comparing the largest to the smallest doctor in terms of pixels.

  <p align="right">
  <img src="../img/18.png" alt="" width="500" height="400" >
 </p>
 
 The number of pixels related to the largest image is 79,000 and 16,500 for the smallest. The percentage change is 27% to 12%. So, the lie factor is calculated as:
 
 
  <p align="right">
  <img src="../img/19.PNG" alt="" width="500" height="150" >
 </p>
 
**Any lie factor different than 1 suggests that a visual is distorting the data. When the factor is greater than 1, we are making an effect larger than it actually is and factors less than 1 are hiding the magnitude of an effect.** 

Further Reading: [Flowing Data: How to Spot Visualization Lies](https://flowingdata.com/2017/02/09/how-to-spot-visualization-lies/)

