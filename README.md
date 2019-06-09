# ACRES visualization tutorial

## Before class starts:

1. Either install the Anaconda python distribution on your laptop (which you can find at [https://www.anaconda.com/distribution/](https://www.anaconda.com/distribution/)), or if you have a different version of Python on your laptop make sure that you have matplotlib, numpy, and Pandas installed!

2. After you've done #1, load up the Jupyter notebook  named "data\_vis\_pre\_session\_assignment.ipynb", which is in this directory.  Follow the instructions in there and try to make a simple plot of the data in the 'statistical' directory. For more information about both of the included datasets, see the end of this file!

3. Find two examples of visualizations of scientific data from the papers that you've been reading for the REU (or some other academic source you're famililar with).  Identify one that you feel does a good job conveying the message the authors seem to intend to send, and one that doesn’t do a good job.  Send copies of those plots to me via email at [oshea@msu.edu](mailto:oshea@msu.edu), along with a paragraph or so for each one describing what the particular aspects of each plot are which you find effective or ineffective.  **Note:** no infographics, please!  The plots need to be presentations of data that is being analyzed for a scientific purpose.  If you're unclear on the distinction, check out [this blog post](https://blog.prototypr.io/getting-it-right-why-infographics-are-not-the-same-as-data-visualizations-a23da7de745e).

## Useful visualization sites:

[Duke library "visualization types" web page](https://guides.library.duke.edu/datavis/vis_types) - breaks things down into categories

[The Data Visualization Catalogue](https://datavizcatalogue.com/) - great resource, has explanations for what things do and where they're commonly used.

[Matplotlib visualization gallery](https://matplotlib.org/gallery.html) 

## Books

["The Truthful Art: Data, Charts, and Maps for Communication," by Alberto Cairo](https://www.amazon.com/Truthful-Art-Data-Charts-Communication/dp/0321934075/)

["The Visual Display of Quantitative Information," by Tufte](https://www.amazon.com/Visual-Display-Quantitative-Information/dp/0961392142/)

## Datasets

In the "statistical" subdirectory:  you will find a data file, congress-terms.csv, which includes an entry for every member of the US Congress who served between January 1947 and Februrary 2014 (and which was downloaded from the [FiveThirtyEight.com GitHub repository](https://github.com/fivethirtyeight/data/tree/master/congress-age)). This information contains the number of the Congress where they served, their name, birthday, starting date, and the age they were when they began that particular Congress.  For this project, let’s focus on the starting ages of congresspeople and senators - how old are they when they start their terms?  Come up with two substantially different ways to visualize this data, write a piece of Python code to make those visualizations, and include the code and visualization in the repository.  You may want to use either [Pandas](https://pandas.pydata.org/) or NumPy's [genfromtxt method](https://docs.scipy.org/doc/numpy-1.13.0/reference/generated/numpy.genfromtxt.html) to ingest the data, and then some sort of [matplotlib plot](https://matplotlib.org/gallery.html) to visualize it.  

In the "time_series" subdirectory: you will find a file showing hourly temperature readings for a variety of cities around the world over several years, from 2012 through 2017 (extracted from [this Kaggle dataset](https://www.kaggle.com/selfishgene/historical-hourly-weather-data)). Plot the temperature reading for Detroit for this time using a standard matplotlib line plot. In addition, try to calculate the average temperature for each month, as well as the minimum and maximum temperature for that month, and plot it on top of the raw data. What does this reveal, if anything, that the raw data does not?