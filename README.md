# KDE-and-clustering-on-running-data

**To properly visualize the code, choice the raw data visualization of the .Rmd file**

## Part 1
Estimate and visualize properly and meaningfully the density of latitude and longitude data (Kernel Density Estimation)
Figure out a way to single out the places where the runner run the most.

## Part 2
**Functional data analysis**
Pick a possibly meaningful epsilon (and/or play around with different epsilon ’s). With this choice:

* find the top-5 paths with the highest local density,
* find the low-5 paths with the lowest local density,
* now that you have a kernel estimator, you can run mean-shift and cluster the tracks
