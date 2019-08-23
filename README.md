### Predictive Methods for Large Geostatistical Data (A Plan B Paper)

Geostatistical predictive analysis conducts spatial interpolations to unobserved location points based on the observed attribute values at other locations. As large amounts of geospatial data become more accessible and an increasing demand for large spatial data analysis has been realized, classical methods for geostatistical analysis are challenged by the greater computational complexity. Heaton et al.
(2018) have gathered twelve different approaches for large geostatistical interpolations in a case study competition and compared their prediction performances as well as required computational resources. This study aimed to (1) provide a brief review of the twelve predictive methods from Heaton et al. (2018), (2) replicate the twelve methods on a simulated satellite image used by Heaton et al. (2018), (3) interpolate the missing values of a new large spatial dataset using two of the methods, Nearest Neighbor Gaussian Processes - Conjugate (NNGP Conjugate) and Fixed Rank Kriging (FRK), and (4) provide a further step of evaluating the prediction performances of NNGP Conjugate at some hold-out locations in the new dataset.

To read the full paper, please go to https://github.com/wanjingz/Academic-Projects/blob/master/Predictive%20Methods%20for%20Large%20Geostatistical%20Data.pdf.


### Parks and Trails in Seattle

This is an exploratory spatial data analysis(ESDA) project for park trail features in Seattle, WA. The analysis results might serve as a valuable reference for local planners to see how park trail conditions could interact with other location-related attributes and find out those potentially interesting regions easily. The project intended to help local planning agencies effectively allocate and update the associated recreational resources.

Key analysis procedures include: data wrangling, outlier detection and treament, Vector Space modeling application in surface type classification, PCA and clustering analysis as well as map visualizations. The project was originally completed in Rmarkdown (see the .html file output from Rmarkdown). I also replicated the key steps in python (see the .ipynb file) for learning and practice purpose. 


[Parks and Trails Project - (R version)](http://htmlpreview.github.io/?https://github.com/wanjingz/Academic-Projects/blob/master/Parks%20and%20Trails/Project2_Jingzhe_Wang.html), with a 4-by-4 'Map Matrix' created at the end of the document.

[Parks and Trails Project - (Python version for the key steps)](https://github.com/wanjingz/Academic-Projects/blob/master/Parks%20and%20Trails/Park%20Trail%20Project%20in%20Python.ipynb)

[A Static Map for Trail Grade Types](https://github.com/wanjingz/Academic-Projects/blob/master/Parks%20and%20Trails/Seattle%20Parks%20and%20Trails%20Static%20Map.pdf)

### Farm Sites Features Exploration Project

This is another exploratory data analysis project about farm sites related attributes. The area of interest (AOI) was selected in the mountain area of Mayaguez, Puerto Rico. The project was motivated by the devastating hurricane hits to Puerto Rico occured in 2017. Thinking that organic farming practice could help enhance the resilient capacity and relieve local unemployment rate, it is of great value to study the organic farm related attributes and filter out those most critical ones to support potential organic farm sites selection. However, it is noteworthy that there were not a lot public available data correspond to strict 'organic' farm sites for the selected AOI. Thus, my analysis then switched to explore and compare the features between farm sites and non-farm sites, which was still considered meaningful for checking some preliminary results.

Key analysis procedures include: data preprocessing using ArcMap, single decision tree and bagging method in R.

[Farm Sites Features Exploration Project - (R version)](https://github.com/wanjingz/Academic-Projects/blob/master/Farm%20Sites%20Features%20Exploration/farm_sites_attributes_project.pdf)

[Farm Sites Features Exploration Project - (PowerPoint)](https://github.com/wanjingz/Academic-Projects/blob/master/Farm%20Sites%20Features%20Exploration/farm_sites_attributes_ppt.pdf)
