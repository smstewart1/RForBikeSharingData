# RForBikeSharingData

In this Coursera project I utilized pre-cleaned bikeshare data in order to analyze time series data. Relevant packages used for this analysis were tidyverse, dbplyr, timetk, tseries, and forecast.  The purpose of this project was to identify the stationarity of the data set, then use the tseries package to predict future bike rentals.  The ARIMA package was used to generate predictive models of the number of reservations, number of bike rentals, and the ratio of bike rentals to reservations.  The Shapiro-Wilk normality test was used to determine if residual errors were truly randomly distributed.

Key findings such as the periodicity of the data set and the symmetry of distribution of the residuals were reported.

Below: Image of the analysis of the models used to extract the stationarity of the data.
![image](https://github.com/smstewart1/RForBikeSharingData/assets/107202785/463a2c7e-6669-48f5-92e5-65d4a724612c)

Below: Image of the model with predictions of the final models:
![image](https://github.com/smstewart1/RForBikeSharingData/assets/107202785/1dfda578-6840-4005-82d2-9afd216d55d6)

