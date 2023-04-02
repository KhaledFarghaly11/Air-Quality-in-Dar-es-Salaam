# Air-Quality-in-Dar-es-Salaam 

## Dataset Description:

- Data from one of Africa's largest open data platforms openAfrica (https://africaopendata.org/).
- This data set contains PM (particulate matter), temperature, and humidity readings taken with low-cost sensors. These sensors measure the concentration of PM in the air, including particles with diameters less than or equal to 1 micrometer (PM1), 2.5 micrometers (PM2.5), and particles with diameters less than or equal to 10 micrometers (PM10). The data set includes information on the sensor type, date, time, and location of the readings, as well as the sensor’s specific measurement values for Temperature (C), Humidity (%), PM1, PM2.5, and PM10. The data set is ideal for researchers and individuals interested in studying air quality and low-cost sensors in PM measurement. The dataset is stored in CSV format and can be opened using editors like Microsoft Excel, Google Sheets, LibreOffice Calc, etc. Note that P0 in the data represents PM1, P2 represents PM2.5, and P1 represents PM10

## Objectives:

- I looked at air quality data from Dar es Salaam, and built a time series model to predict PM 2.5 readings throughout the day.
- I got data by querying a MongoDB database.
- I prepared time series data for analysis.
- I built an autoregression model.
- I improved a model by tuning its hyperparameters.
