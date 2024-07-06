# Ensemble-Forecasting
Program that ingests raw weather model data from NOAA's database for a specific location.
We are using the GFS Ensembles for this project.
The data is then spatially and temporally sliced and filtered using Xarray and Pandas.
The units of our data (temperature, winds, pressure, and visibility) are then converted from SI to Imperial.
The mean, minimum, and maximum data points from the 18 ensemble members are plotted for each of our variables for up to 72 hours out using MatPlotLib.
Note: This project was deployed onto AWS but was stopped in February to avoid fees.
