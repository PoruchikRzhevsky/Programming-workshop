# Programming-workshop

Here are materials from two programming workshops. FP4 is from Physical Practicum 2, held in the third semester. Astro, respectively, is Fundamentals of Astronomy 1.

In the homework folder you are invited to try to visualise the data in the csv files yourself. These data hold photometric analyses of the star clusters NGC 6101: ui.adsabs.harvard.edu/abs/2012yCatp019002901F/abstract and Terzan 2: ui.adsabs.harvard.edu/abs/1997A%26A...326..614O/abstract . 

The procedure is summarised below: 
1. Import the necessary libraries (hint, you will need a library to plot and import the data).
2. Import the data from the csv tables into Jupyter Notebook.
3. Plot the graphs for all three data sets. You need to plot what is called a Color-Magniture Diagram. This is the ratio of V-I colour to V-magnitude. For the cluster NGC 6101, the errors for these magnitudes (columns e_V-I and e_Vmag) are also presented in the data. Try to plot them on the graph as well. Do not forget that according to the rules of astronomy, the V-magnitudes presented in our case on the Y-axis should be inverted (i.e. not from smaller to larger, but vice versa). This can be done with ax.invert_yaxis().
