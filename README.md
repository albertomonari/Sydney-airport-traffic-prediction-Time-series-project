# Sydney airport traffic prediction

The objective of this project is to apply Box-Jenkins methodology to forecast Sydney airport traffic time
series using a dataset of 132 monthly observations of the number of passengers who flew through Sydney airport (from January 2009 to December 2019). 
The prediction is done for the number of passengers that would frequent the airport in 2020 (if Covid-19 had not struck).



![sydney](https://www.applelanguages.it/it/img/top/sydney.jpg)



The procedure used in this project was:
- the description of the time series (trend, seasonality, random component)
- study of stationarity
- transformation from non-stationary to stationary through log transformation, first order difference, difference of lag 12
- Box-Jenkins methodology to build a model
- residual diagnostic
- quality of the fit
- forecasting (in-sample and out-of-sample)

