# thesis1

This file includes data, codes and files about the implementation of methods (for forecasting crime events) in R Studio (https://rstudio.com/). 
Necessary input data is a file with the spatial features of study area (e.g. blocks of boroughs for the NYC) ( https://data.cityofnewyork.us/City-Government/2010-Census-Blocks/v2h8-6mxf) and retrospective crime data. Crime data has been collected by the NYPD (https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc) and 3 categories describe them; property, violent and all as crime incidents. The division into these categories was based on theoretical background (similar projects and scientific papers) and were combined with the NCJRS (https://www.ncjrs.gov/App/Topics/Topic.aspx?TopicID=56). 
The methods that will be implemented are the KDE (Kernel Density Estimation), the Local Moran's I and the Spatiotemporal Autoregressive Moving Average (starma).
The selected crime data are included in this repository; one for the train period of one year ("FINAL_DESC") and another one for the "predictive" / test period of one month ("FINAL_DESC_PRED"). However, the above mentioned methods will be first tested on a sample of data and more particularly by using 3 months to predict the fourth month in an area of 30 blocks. The visualisation of the three sample train months can be seen through the uploaded figures.


