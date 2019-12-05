# Research Computing for the Earth Sciences: Final Project

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ccivanovich/RCES-Final_Assignment/master)

## Scientific Question/Hypothesis

Scientific Question: Has daily temperature variability increased anywhere in the world?

Around the world, we hear more and more people saying colloquially that the weather is getting weirder. However, recent analyses suggest that global daily temperature variability has not increased significantly in recent decades and that most sense of "weirder weather" can be explained by shifts in the global mean temperature. We strive to test additional metrics for measuring daily temperature variability in order to determine whether or not this conclusion is robust.

## Links to Relevant Datasets

Modern-Era Retrospective analysis for Research and Applications, Version 2 ([MERRA-2](https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/))

## Summary of Analysis

In this analysis, we visualize the seasonal climatologies provided by the MERRA2 2-meter air temperature data, as well as an example of seasonal anomalies in year 2013. Recognizing that some literature has suggested that Europe may be a regional exception of where we see increased temperature variability, we use Paris, France as a case study. We visualize the trend in summer temperature anomalies in Paris over the past 40 years, as well as the difference in the occurrence of hot and cold events in the city in 1980 versus 2018. Finally, as a more comprehensive analysis, we calculate the trend in hot to cold/cold to hot event flipping frequency around the globe over the past 40 years. We do so for two sets of criteria. The more stringent criteria must pass the following: 1) hot and cold events must be at least 5 ^{\circ}C above/below the climatology, 2) hot and cold events must persist for at least 2 days, and 3) the flip from hot to cold (or vice versa) must occur within the span of 3 days. In the relaxed criteria, events must only be 3 ^{\circ}C above the climatology and do not need to persist for more than 1 day.
