﻿
# Using Color

Color is an important tool in visualizations and it's important to use it appropriately to have the largest impact. Color can both help and hurt a data visualization. Three tips for using color effectively.

   1. Before adding color to a visualization, start with black and white.Many times, black, white and shades of grey will be enough to effectively convey your information. 

   2. When using color, use less intense colors such as natural colors or pastels.  - not use all the colors of the rainbow, which is the default in many software applications. Colors with higher gray values have a softer feel and the eye can concentrate on them for longer periods of time. 

   3. Color for communication. Use color to highlight your message and separate groups of interest. Don't add color just to have color in your visualization.


# Designing for Color Blindness

Humans perceive color through signals produced by cells in the retina called cones. Light comes into the eye, hits the cones and the cones set off electrical signals to the brain. There are typically three types of cones, S, M and L, for short, medium and long. They are sensitive to different frequencies or colors of light. **Short cones prefer blue, medium prefer green and long prefer red**. 

 <p align="right">
  <img src="../img/20.PNG" alt="" width="300" height="350" >
 </p>

 However around 10% of men and 1% of women, have mutations that affect these cones and produce what is known as **colorblindness**. 
 The most common form,is a **red green colorblindness**,typically caused by the medium cone shifting sensitivity towards red light. People with this condition can't distinguish between red and green. There is actually a pretty large fraction of people that are colorblind.as shown in the below image of a red and a green apple.
 
 You should design your visualizations to include them. Try to stay away from **red green palettes** and use **blue orange** instead.

 <p align="right">
  <img src="../img/21.PNG" alt="" width="600" height="200" >
 </p>

To be sensitive to those with colorblindness, you should use color palettes that do not move from **red to green** without using another element to distinguish this change like shape, position, or lightness. Both of these colors appear in a yellow tint to individuals with the most common types of colorblindness. Instead, use colors on **a blue to orange** palette.

# Shape, Size, & Other Tools

We typically try to use position on the x- and y- axes to encode, or depict the value of variables. If we have more than two variables, however, we have to start considering other visual encodings for the additional variables.

In general, **color and shape are best for categorical variables**, while the **size of marker can assist in adding additional quantitative data**.

Only use these additional encodings when absolutely necessary. Often, overuse of these additional encodings suggest you are providing too much information in a single plot. Instead, it might be better **to break the information into multiple individual messages, so the audience can understand every aspect of your message**. 

Color, shape, size, and other tools of data visualization are additional tools as a [skid loader](https://en.wikipedia.org/wiki/Skid-steer_loader). You might need to use it, but it isn't good for digging every hole. Most data visualizations used for explanatory purposes should not use all (or any) of these tools.
